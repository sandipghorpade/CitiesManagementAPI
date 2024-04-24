# City Management API

This is a RESTful API built with .NET Core for managing cities. It provides endpoints for performing CRUD operations on cities, as well as authentication and authorization functionality.

## Features

- **City Management**
  - Get a list of all cities
  - Get details of a specific city
  - Add a new city
  - Update an existing city
  - Delete a city
- **Authentication and Authorization**
  - User registration
  - User login
  - Logout
  - Generate new JWT token

## Technologies Used

- .NET Core
- ASP.NET Core Web API
- Entity Framework Core
- SQL Server
- Swagger UI

## Getting Started

### Prerequisites

- .NET Core SDK
- SQL Server or any other compatible database

### Installation

1. Clone the repository
2. Open the solution file in Visual Studio or your preferred IDE
3. Update the connection string in `appsettings.json` to point to your database
4. Run the application

### API Documentation

Once the application is running, you can access the Swagger UI by navigating to `https://localhost:<port>/swagger`. The Swagger UI provides detailed documentation for all available endpoints, request/response models, and authentication methods.

## Contributing

Contributions are welcome! Please follow the [contributing guidelines](CONTRIBUTING.md) when submitting pull requests.

## License

This project is licensed under the [MIT License](LICENSE).
