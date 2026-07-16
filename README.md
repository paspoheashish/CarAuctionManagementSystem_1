CarAuctionManagementSystem_Simple
================================

This is a small, educational .NET 8 solution that contains multiple microservice-style projects for a sample car auction system.

Projects included
- ApiGateway - API gateway and lightweight HTTP clients
- AuctionService - Auction business logic and repository
- ItemService - Vehicle management
- AuthService - Authentication and token generation
- UserService - User management
- NotificationService - (simple placeholder)
- *.Test - NUnit test projects using Moq for lightweight unit tests

Quick notes
- This solution targets .NET 8.
- Tests use NUnit and Moq.

Run locally
1. From the solution folder run: dotnet build
2. To run tests: dotnet test

Conventions
- Test projects are kept simple and beginner-friendly.
- The repository ignores build artifacts (see .gitignore).

If you need a specific README section (architecture, endpoints, docker, infra), tell me which part and I will add it.
