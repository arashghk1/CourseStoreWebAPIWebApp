# Web API Project for CRUD Operations with C# and ASP.NET Core MVC
This is a web API project that implements CRUD operations for a data model. The project is built with C# and ASP.NET Core MVC, and it utilizes Swagger for testing the API endpoints.

# Features
- Create, read, update, and delete operations for a data model
- Swagger for testing the API endpoints

# Technologies Used
C#
ASP.NET Core MVC
Entity Framework Core
Swagger

# Installation
- Clone the repository to your local machine
- bash
- Copy code
- git clone https://github.com/arashghk1/CourseStoreWebAPIWebApp
- Open the solution in Visual Studio
- Run the application

# Usage
- Configure the connection string in program.cs
- Open package manager console --> default package = coursestore.dal --> Add-Migration init --> Update-Database
- Run the program and Open the Swagger UI in your web browser at https://localhost:5001/swagger/index.html
- Test the API endpoints using the Swagger UI

# Endpoints
The following endpoints are available for testing in the Swagger UI:

- GET /api/data: Retrieves all data items
- GET /api/data/{id}: Retrieves a single data item by ID
- POST /api/data: Creates a new data item
- PUT /api/data/{id}: Updates an existing data item by ID

# Contributing
Contributions are welcome! Please open an issue or pull request for any changes.

# License
This project is licensed under the MIT License.
