# 💇  Eau Claire's Salon Database ✂️
##### By Derrak Richard
A stylist and client tracking system for a hair salon demonstrating basic SQL database principals

#### Technologies Used ✂️ ✂️ ✂️ ✂️ ✂️ ✂️ ✂️ ✂️ ✂️ ✂️ ✂️ ✂️ ✂️ ✂️ ✂️ ✂️ ✂️ ✂️
* C#
* .NET 5
* ASP.Net Core
* Entity Framework Core
* MySQL
* LINQ
* HTML
* CSS
* Bootstrap

#### Description ✂️ ✂️ ✂️ ✂️ ✂️ ✂️ ✂️ ✂️ ✂️ ✂️ ✂️ ✂️ ✂️ ✂️ ✂️ ✂️ ✂️ ✂️ ✂️ ✂️ ✂️
A web application for a hair salon that allows a salon manager to view, add, edit, and delete stylists and their clients.

#### Setup/Installation Requirements
* Download and install [MySQL Workbench](https://www.mysql.com/products/workbench/) and create a local instance using localhost:3306
* Clone this repository to your desktop
* Open MySQL Workbench and in the Navigator > Administration window, select Data Import/Restore
* Under Import Options, select Import from Self-Contained File
* Navigate to the root folder of the cloned repository and select the file `derrak_richard.sql`
* Under Default Schema to be Imported To, select the New button and enter a name for the database, then click Start Import
* Using the terminal, navigate to the root folder of the project directory and run `code .` to launch the project in [VS Code](https://code.visualstudio.com/download)
* Create a `.gitignore` file in the root directory and add the following: `*/bin/` `*/obj/` `appsettings.json`
* From the HairSalon directory, create an `appsettings.json` file and add the following code: 
```
  {
  "ConnectionStrings": {
    "DefaultConnection": "Server=localhost;Port=3306;database=[database_name];uid=root;pwd=[password];"
    }
  }
```
* Replace `[database_name]` and `[password]` with your database name and password
* From the HairSalon directory, run the following commands in your terminal:
    * `dotnet add package Microsoft.EntityFrameworkCore -v 5.0.0`
    * `dotnet add package Microsoft.EntityFrameworkCore.Proxies -v 5.0.0`
    * `dotnet add package Pomelo.EntityFrameworkCore.MySql -v 5.0.0-alpha.2`
    *  `dotnet restore`
* Launch the application from your terminal by running the command `dotnet run`, then navigate to http://localhost:5000 in your preferred browser

#### Known Bugs ✂️ ✂️ ✂️ ✂️ ✂️ ✂️ ✂️ ✂️ ✂️ ✂️ ✂️ ✂️ ✂️ ✂️ ✂️ ✂️ ✂️ ✂️ ✂️ ✂️
* None at this time

#### License ✂️ ✂️ ✂️ ✂️ ✂️ ✂️ ✂️ ✂️ ✂️ ✂️ ✂️ ✂️ ✂️ ✂️ ✂️ ✂️ ✂️ ✂️ ✂️ ✂️ ✂️ ✂️ 
[MIT](https://opensource.org/licenses/MIT)

Copyright (c) 2022 Derrak Richard