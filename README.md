# Restaurant-App
Full-stack restaurant management system built with Blazor WebAssembly and ASP.NET Core, featuring Identity authentication, CQRS + MediatR, Clean Architecture, EF Core, Dapper, and SQL Server running in Docker.

Restaurant Management System

A modern full-stack restaurant management application designed to streamline restaurant operations such as menu management, orders, users, and administration workflows.

Built using Blazor WebAssembly for the frontend and ASP.NET Core for the backend, the project follows Clean Architecture principles to ensure scalability, maintainability, and separation of concerns.

🚀 Tech Stack
Frontend
Blazor WebAssembly
Bootstrap
Responsive UI components
Client-side routing and state handling
Backend
ASP.NET Core Web API
ASP.NET Identity for authentication and authorization
MediatR
CQRS pattern
Clean Architecture
Entity Framework Core
Dapper for optimized data access
SQL Server
Docker containerization
🏗 Architecture

The solution is structured following Clean Architecture, separating:

Presentation layer
Application layer
Domain layer
Infrastructure layer

This design promotes:

low coupling
high cohesion
testability
maintainability
scalability
🔐 Security

Authentication and authorization are implemented using ASP.NET Identity, providing secure user registration, login, role management, and protected endpoints.

🐳 Infrastructure

The database runs on SQL Server inside a Docker container, allowing consistent local development and deployment environments.
