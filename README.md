# BestBuy Product Management System

This project is a CRUD (Create, Read, Update, Delete) web application built with ASP.NET Core MVC, C#, SQL Server, and Dapper ORM to manage a mock Best Buy product database.

## Features:

- **Comprehensive CRUD Functionality:** Users can seamlessly add, view, edit, and delete products from the database.
- **Dapper ORM Integration:** Ensures smooth interaction between the application and the database for optimal performance and data integrity.
- **Secure Product Deletion:** Alert prompts confirm user intentions before deleting products, preventing accidental data loss.

## Benefits:

- **Enhanced User Experience:** Streamlines product management for Best Buy staff.
- **Operational Efficiency:** Improves workflow and data manipulation.
- **Increased Productivity:** Empowers staff to effectively manage the product database.

## Technologies:

- ASP.NET Core MVC (Backend Framework)
- C# (Programming Language)
- SQL Server (Database)
- Dapper ORM (Object Relational Mapper)
- HTML (User Interface)

## How to Use:

1. Clone this repository.
2. Download and run this mock database setup file in MySQL: [BestBuy MockDB](https://drive.google.com/file/d/1JK7j9pREUf5r2OHGO_b8B2n0JyWLmMLz/view?usp=sharing).
3. Create an appsettings.json file in the project with this format:
  ```txt
    {
    "ConnectionStrings": {
    "bestbuy": "Server=probablyLocalhost;Database=bestbuy;uid=probablyRoot;Pwd=yourPasswordHere;Port=3306;"
    },
    "Logging": {
    "LogLevel": {
        "Default": "Warning"
    }
    },
    "AllowedHosts": "*"
}
  ```
4. Configure the connection string in `appsettings.json` to point to your MySQL instance of the database.
5. Build and run the application.

## This project demonstrates proficiency in:

- Web development with ASP.NET Core MVC
- C# programming
- SQL database management
- Object-Relational Mapping (ORM) with Dapper
- Building user-friendly and secure web applications

## Stay Connected:

- Email: [mackmc9924@gmail.com](mailto:mackmc9924@gmail.com)
- GitHub: [MackMcCall](https://github.com/MackMcCall)
- LinkedIn: [Mack McCall](https://www.linkedin.com/in/mackmccall/)
