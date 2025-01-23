# Microservices Project

This is a microservices-based architecture project with four services:
- Event Service
- Booking Service
- User Service
- Notification Service

## Running the Project
1. Install Docker and Docker Compose.
2. Run `docker-compose up` to start all services.

## Structure
Each service has:
- `controllers`: Business logic.
- `models`: Database schemas.
- `routes`: API routes.
- `middlewares`: Custom middleware.
- `config`: Configuration files.
- `utils`: Utility functions.
- `docs`: Documentation.
- `tests`: Unit and integration tests.
- `logs`: Log files.

## Notes
- Each service has a `Dockerfile` for containerization.
- Environment variables are managed via `.env` files.
- Services are connected through Docker Compose.
