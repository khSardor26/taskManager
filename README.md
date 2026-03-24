📝 Task Manager (Spring Boot)
📌 Overview

Task Manager is a RESTful backend application built with Spring Boot that allows users to create, manage, and track tasks efficiently. The system provides full CRUD functionality with clean layered architecture and database integration.
This project demonstrates backend development best practices including DTO usage, validation, exception handling, and structured API design.

🚀 Features
✅ Create new tasks
📖 Retrieve all tasks or task by ID
✏️ Update task details
❌ Delete tasks
🔍 Filter tasks by status (optional)
🗂️ Persistent storage with PostgreSQL

⚠️ Global exception handling
🧱 Layered architecture (Controller → Service → Repository)
🏗️ Tech Stack
Java 17+
Spring Boot
Spring Data JPA
Hibernate
PostgreSQL
Maven
Lombok (if used)



🗄️ Database Configuration

Set environment variables:
export DB_URL=jdbc:postgresql://localhost:5432/taskdb
export DB_USER=postgres
export DB_PASSWORD=password

No hardcoded credentials are used.
▶️ Build & Run
Prerequisites
Java 17+
Maven
PostgreSQL
Build
mvn clean package
Run
java -jar target/taskmanager-1.0-SNAPSHOT.jar
📬 Sample API Endpoints
Method	Endpoint	Description
POST	/api/tasks	Create task
GET	/api/tasks	Get all tasks
GET	/api/tasks/{id}	Get task by ID
PUT	/api/tasks/{id}	Update task
DELETE	/api/tasks/{id}	Delete task
🎯 Purpose

This project is designed for:

Backend practice
Interview preparation
Portfolio demonstration
Understanding REST API development
How the integration with SQL db works
