# Items - ASP.NET Core MVC Project

## Overview
Items is an ASP.NET Core MVC application following the N-Tier architecture. It is designed to demonstrate clean code practices, separation of concerns, and maintainability by structuring the application into different layers.

## Features
- **N-Tier Architecture**: Separation of models, services, and controllers.
- **Entity Framework Core**: Database interaction with migrations.
- **ASP.NET Core MVC**: Implements controllers, views, and models.
- **Dependency Injection**: Follows best practices for maintainability and testability.
- **CRUD Operations**: Basic operations for managing items in the application.

## Technologies Used
- **ASP.NET Core MVC**
- **Entity Framework Core**
- **SQL Server**
- **C#**
- **Bootstrap (for UI styling)**

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/ivane98/items.git
   ```
2. Navigate to the project directory:
   ```bash
   cd items
   ```
3. Restore dependencies:
   ```bash
   dotnet restore
   ```
4. Apply database migrations:
   ```bash
   dotnet ef database update
   ```
5. Run the application:
   ```bash
   dotnet run
   ```
6. Open your browser and navigate to `https://localhost:5001` (or the specified port).

## Project Structure
```
/items
│-- Models/           # Entity models
│-- Data/            # Database context
│-- Services/        # Business logic layer
│-- Controllers/     # Application logic
│-- Views/           # UI components (Razor views)
│-- wwwroot/        # Static files (CSS, JS, Images)
│-- appsettings.json # Configuration file
```

## Contributing
If you would like to contribute to this project, feel free to fork the repository and submit a pull request with improvements.

## License
This project is open-source and available under the MIT License.

---

### Contact
For any questions or suggestions, feel free to reach out!

---
Happy Coding! 🚀

