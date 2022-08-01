# Eau Claire's Salon (C# Project 3)

#### By Sue Roberts

####  MVC web application for the employer to manage employees (stylists) and their clients.

## Technologies Used

* C#
* .NET 5.0
* SQL Workbench
* Entity Framework
* ASP.NET
* REPL
* CSS
* Bootstrap
* HTML

## Description

When the employer runs this application, they are able to see a list of all stylists, add new stylists, hired dates, and add new clients to a specific stylist. They should not be able to add a client if no stylists have been added. The stylists page  includes their details and see a list of all clients that belong to that stylist. 

## Setup/Installation Requirements

* Clone repository: $ git clone https://github.com/SueRtx/HairSalonProject.solution.git  
* Download MySQL WorkBench  
* Open MySQL WorkBench  
* Importing [sun_roberts.sql] from HairSalon.Solution     
  - Administration window → Data Import/Restore     
  - Import Options → Import from Self-Contained File    
    (Use [sue_roberts.sql] from [HairSalon.Solution])  
  - Import Progress → Start Import    
  - Reopen Navigator → Schemas tab → Right click → Refresh All   
* Navigate to "HairSalonProject.solution": $ cd HairSalonProject.solution   
* Open Vs Code: $ code .   
* Open TERMINAL in Vs Code
* Go to HairSalon directory: $ cd HairSalon
* Create folder: $ touch "appsettings.json"
* Add following code to "appsettings.json" (Add your own password)
```
{
  "ConnectionStrings": {
      "DefaultConnection": "Server=localhost;Port=3306;database=sun_roberts;uid=root;pwd=[YOUR-PASSWORD];"
  }
}

```  
* Run Program: Go to terminal  → $ dotnet restore → $ dotnet build → $ dotnet run  
* Open web browser: http://localhost:5000/  

## Known Bugs

* none

## License

MIT

Copyright (c) 2022 Sue Roberts
