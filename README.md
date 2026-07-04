# Spring Boot User Management

A simple Spring Boot application built to practice backend development using Java and Spring Boot.

## Tech Stack

- Java
- Spring Boot
- Spring Data JPA
- H2 Database

## Features

- CRUD operations
- REST APIs
- Database integration using Spring Data JPA

## Project Structure

```
src/
├── controller/
├── repository/
├── model/
└── UserManagementApplication.java
```

## Running the Application

```bash
./mvnw spring-boot:run
```

Or run the project directly from your IDE.

## Docker

Build the Docker image

```bash
docker build -t springboot-user-management .
```

Run the container

```bash
docker run -p 8080:8080 springboot-user-management
```

Docker Hub Image

```
vedansh12/usermanagement:latest
```

## Deployment

The application was containerized using Docker and successfully deployed on an AWS EC2 instance.
