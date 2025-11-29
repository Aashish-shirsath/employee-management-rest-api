# Employee Management REST API (Spring Boot)

A simple CRUD (Create, Read, Update, Delete) REST API built using Spring Boot for managing employee data.

This project demonstrates how to create RESTful endpoints, use service layers, connect to a database, and handle common API operations.

## Features

- Add a new employee
- Get all employees
- Get a single employee by ID
- Update employee information
- Delete an employee

## Technologies Used

- **Java** 21
- **Spring Boot** (Web, JPA, DevTools)
- **Hibernate**
- **MySQL**
- **Maven**
- **Postman**  (for testing)


## Project Structure

```bash
  src/main/java/com/employeemanagementsystem/demo
  |
  controller/  →  REST API endpoints
  service/     →  Business logic 
  repository/  →  JPA repository
  model/       →  Employee entity

```
## Running Tests

 1. Clone the repository
```bash
  git clone https://github.com/Aashish-shirsath/employee-management-rest-api
```

2. Open the project in your IDE (IntelliJ/Eclipse).

3. Configure the database in application.properties.

4. Run the Spring Boot application:
```bash
mvn spring-boot:run
```
5. Test APIs using Postman or browser.

## Future Work

- Add validation, error handling, and JWT security.

- Integrate with a front-end and Docker deployment.
