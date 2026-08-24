# Food Delivery App

A backend application built with **Spring Boot** and **MySQL** to manage food delivery operations.  
It provides REST APIs for handling users, restaurants, menus, and orders.

---

## Features
- User registration and login
- Restaurant and menu management
- Place and track orders
- Role-based access (Admin / Customer)
- CRUD operations with validation

---

## Tech Stack
- **Backend:** Spring Boot, Spring Data JPA, Hibernate  
- **Database:** MySQL  
- **Frontend (optional):** Thymeleaf, HTML, CSS  
- **Tools:** Maven, Git/GitHub, Postman  

---

## Project Structure


## Project Structure

```bash
src/
├── main/
│   ├── java/
│   │   └── com.example.foodfrenzy/
│   │       ├── controller/      # Contains all controllers
│   │       ├── model/           # Contains entity classes
│   │       ├── repository/      # Repository interfaces for database interaction
│   │       └── service/         # Service layer with business logic
│   ├── resources/
│   │   ├── templates/           # Thymeleaf templates for views
│   │   ├── static/              # Static assets (CSS, JavaScript)
│   │   └── application.properties  # Project configuration
│   └── webapp/
│       └── WEB-INF/
│           └── views/           # Additional view files
└── test/                        # Test cases for unit testing
