# Spring Boot Examples
A showcase of **Spring Boot applications** covering key use cases:

- **REST CRUD** – REST API with full CRUD operations and database integration.
- **MVC CRUD with Thymeleaf** – web application using Spring MVC + Thymeleaf templates.
- **REST Security (optional)** – starter project with authentication and authorization setup.

---

## Projects

### 1. REST CRUD
- **Location**: `apps/rest-crud/`
- **Features**: REST API, CRUD operations, JPA, database integration.
- **Run**:
  ```bash
  mvn spring-boot:run
Example endpoint:
curl http://localhost:8080/api/employees

### 2. MVC CRUD with Thymeleaf
Location: apps/mvc-thymeleaf/

Features: Spring MVC, Thymeleaf templates, CRUD web interface.

- **Run**:
  ```bash
  mvn spring-boot:run
Open: http://localhost:8080/employees

### 3. REST Security
Location: apps/rest-security/

Features: Spring Security starter with authentication/authorization.

- **Run**:
  ```bash
  mvn spring-boot:run
  
Default credentials:

pgsql
user / password

Requirements
Java 21+
Maven 3.9+

Docker (optional, for running databases with docker-compose)

Using Docker (optional)
Start a local PostgreSQL database with Docker Compose:
- **Run**:
  ```bash
  docker compose up -d
  
About
This repository is a collection of essential Spring Boot examples:
REST APIs, MVC web applications, and basic Security setup.

It can be used as a learning resource or as a starting point for new projects.
