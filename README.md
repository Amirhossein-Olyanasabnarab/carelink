# CareLink

**A Veterinary Clinic Management REST API**

CareLink is a backend project designed to support veterinary clinic workflows by organizing pet profiles, medical records, and veterinary visits.

The project is being developed with Java and Spring Boot, with a focus on maintainable code, REST API design, automated testing, and backend development best practices.

## Tech Stack

- **Java 21**
- **Spring Boot 4**
- **Maven**
- **Spring Web**
- **Spring Boot Actuator**
- **JUnit** for automated testing

PostgreSQL and Spring Data JPA are planned for a future development stage.

## Current Features

- Spring Boot application setup
- Application health monitoring with Spring Boot Actuator
- Maven-based build and test configuration

## Getting Started

### Prerequisites

- Java 21
- Git
- An IDE such as IntelliJ IDEA

### Run Tests

On Windows, open a terminal in the project root and run:

```powershell
.\mvnw.cmd clean test
```

### Start the Application

```powershell
.\mvnw.cmd spring-boot:run
```

### Check Application Health

Once the application is running, open:

`http://localhost:8080/actuator/health`

A successful health check returns a response similar to:

```json
{
  "status": "UP"
}
```

## Roadmap

- [ ] Implement pet management REST endpoints
- [ ] Add service and repository layers
- [ ] Integrate PostgreSQL with Spring Data JPA
- [ ] Add input validation and centralized exception handling
- [ ] Expand automated test coverage
- [ ] Document API endpoints with OpenAPI/Swagger
- [ ] Add authentication and authorization
- [ ] Introduce Docker and continuous integration

## Project Status

CareLink is under active development. The roadmap describes planned work; features will be marked as completed only after implementation and testing.

## Purpose

This project is part of a practical backend development journey focused on Java, Spring Boot, API development, testing, and software engineering fundamentals.
