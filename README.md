# Employee Management Application

## Introduction
This Employee Management Application is built using Spring Boot framework and utilizes REST API for communication. It provides CRUD operations for managing employee data stored in a MySQL database. The application also includes API testing using Postman.

## Technologies Used
- Spring Boot
- REST API
- Spring Boot
- JPA (Java Persistence API)
- MySQL
- Postman

## Features
- Create, Read, Update, and Delete (CRUD) operations for managing employee data.
- Secure endpoints using Spring Security.
- API documentation using Swagger UI.
- API testing using Postman.

## Installation
1. **Clone the repository:**
    ```bash
    git clone https://github.com/yourusername/employee-management.git
    ```
2. **Import project into IDE:**
    - Import the project into your preferred IDE (Eclipse, IntelliJ IDEA, etc.).
3. **Configure MySQL database:**
    - Create a MySQL database named `employee_management`.
    - Update `application.properties` with your database configuration.
4. **Run the application:**
    - Run the `EmployeeManagementApplication.java` class to start the Spring Boot application.

## Usage
- Access the application at `http://localhost:8080`.
- Use Postman or any other API client to interact with the endpoints.
- API documentation can be accessed at `http://localhost:8080/swagger-ui.html`.

## API Endpoints
- **GET /api/employees**: Get all employees.
- **GET /api/employees/{id}**: Get employee by ID.
- **POST /api/employees**: Create a new employee.
- **PUT /api/employees/{id}**: Update an existing employee.
- **DELETE /api/employees/{id}**: Delete an employee by ID.

## API Testing
- Import the Postman collection provided in the `postman` directory.
- Run the collection to test the API endpoints.
