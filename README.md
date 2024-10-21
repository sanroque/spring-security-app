# Spring Security + JWT Authentication Project

This project demonstrates how to implement **JWT (JSON Web Token)** authentication with **Spring Security**.
It includes user authentication, authorization, and JWT-based stateless authentication.

## Features

- JWT-based authentication and authorization.
- Secure REST API endpoints with role-based access control.
- Stateless session management.
- Token validation and expiry handling.
- Custom user details service for user authentication.

## Prerequisites

Before running this project, ensure that you have:

- **Java 21** or later installed.
- **Maven** installed to manage project dependencies.
- **PostgreSQL** configured (if using database authentication).

## Getting Started

Follow the steps below to set up and run the project on your local machine.

### 1. Clone the repository

```bash
git clone https://github.com/sanroque/spring-security-app.git
cd spring-security-app
```

### 2. PostgreSQL

```bash
spring.datasource.url=jdbc:postgres://localhost:6000/your-database
spring.datasource.username=your-username
spring.datasource.password=your-password
spring.jpa.hibernate.ddl-auto=update
```

### 3. Build the project

```bash
mvn spring-boot:run
```
