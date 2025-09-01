# User Management API

Educational API for user management developed in C# with ASP.NET Core.
Includes full CRUD, validation, and logging and error handling middleware.

---

## Technologies Used

- .NET 7 / ASP.NET Core Web API
- C#
- Swagger for interactive documentation

## Available Endpoints

| Method | Path | Description |
|--------|-------------------|----------------------------------|
| GET | /api/Users | List all users |
| GET | /api/Users/{id} | Get user by ID |
| POST | /api/Users | Create new user |
| PUT | /api/Users/{id} | Update existing user |
| DELETE | /api/Users/{id} | Delete user |

## Middleware

LoggingMiddleware: Logs each request and response to the console with a duration.

ErrorHandlingMiddleware: Captures global errors and returns JSON with an error message.

## Run the project
1. Clone the repository.
```bash
git clone <repository-URL>
cd UserManagementAPI
```
2. Run the program.
```bash
dotnet restore
dotnet build
dotnet run
```

## API
API:
http://localhost:<IP_SEE_TERMINAL>

API tests at:
http://localhost:<IP_SEE_TERMINAL>/swagger

