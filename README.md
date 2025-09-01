# User Management API

API con fines educativos para gestión de usuarios desarrollada en **C# con ASP.NET Core**.  
Incluye CRUD completo, validaciones, y middleware de logging y manejo de errores.

---

## Tecnologías utilizadas

- .NET 7 / ASP.NET Core Web API
- C#
- Swagger para documentación interactiva

## Endpoints disponibles

| Método | Ruta                | Descripción                       |
|--------|-------------------|-----------------------------------|
| GET    | /api/Users        | Listar todos los usuarios         |
| GET    | /api/Users/{id}   | Obtener usuario por ID            |
| POST   | /api/Users        | Crear nuevo usuario               |
| PUT    | /api/Users/{id}   | Actualizar usuario existente      |
| DELETE | /api/Users/{id}   | Eliminar usuario                  |


## Middleware

LoggingMiddleware: registra en consola cada request y response con duración

ErrorHandlingMiddleware: captura errores globales y devuelve JSON con mensaje de error


## Ejecutar el proyecto
1. Clonar repositorio.
```bash
git clone <URL-del-repositorio>
cd UserManagementAPI
```
2.Ejecutar programa.
```bash
dotnet restore
dotnet build
dotnet run
```

## API 
API:
http://localhost:5039


Pruebas de la API en: 
http://localhost:5039/swagger
