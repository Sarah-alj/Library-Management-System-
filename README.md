# Library-Management-System-

# 📚 Library Management System - SE411 Project

This project is a Java-based Library Management System developed as part of the SE411 Software Engineering course. It allows basic CRUD operations for managing books using a RESTful API built with Spring Boot.

## 🚀 Features

- Add, view, update, and delete books
- RESTful API using Spring Boot
- MVC architecture with clearly separated layers
- Persistence with Spring Data JPA
- Maven project structure for easy build and dependency management

## 🛠️ Tech Stack

- **Java 17+**
- **Spring Boot**
- **Spring Data JPA**
- **Maven**
- **H2 Database** *(or configure your own in `application.properties`)*

## 📁 Project Structure

- `controller/` — Contains REST API controllers.
- `model/` — Defines the `Book` entity.
- `repository/` — Interface for Spring Data JPA to handle database operations.
- `resources/` — Configuration files and static resources.
- `test/` — Unit tests for the application.

## 🧪 Running the Project

### Prerequisites
- Java JDK 17 or above
- Maven

### Steps
```bash
cd manageLibrary
./mvnw spring-boot:run

mvnw.cmd spring-boot:run

Then navigate to:
http://localhost:8080/

🧑‍💻 Author

Sarah Sarah-alj
