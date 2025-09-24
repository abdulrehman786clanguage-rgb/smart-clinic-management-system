# Smart Clinic Management System

This repository contains the backend codebase for the Smart Clinic Management System built with Java Spring Boot and MySQL. It includes Docker configuration and CI/CD workflows for deployment and testing.

## Features
- Patient Management
- Doctor Management
- Appointment Scheduling
- Medical Records
- User Authentication
- RESTful API

## Tech Stack
- Java 17
- Spring Boot
- MySQL
- Docker
- GitHub Actions

## Getting Started

### Prerequisites
- Java 17+
- Docker
- MySQL

### Setup Instructions
1. Clone the repository:
   ```
   git clone https://github.com/abdulrehman786clanguage-rgb/smart-clinic-management-system.git
   ```
2. Configure your MySQL database connection in `src/main/resources/application.properties`.
3. Build and run the project:
   ```
   ./mvnw spring-boot:run
   ```
4. Or use Docker to run the project:
   ```
   docker-compose up --build
   ```

## License
MIT
