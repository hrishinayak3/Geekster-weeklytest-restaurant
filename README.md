# Restaurant API Application

## Overview

Restaurant Management Application is a Spring Boot-based web application designed to help manage restaurant information.

## Technologies Used

- **Framework:** Spring Boot
- **Language:** Java
- **Build Tool:** Maven

### Controller

The Controller layer is responsible for handling incoming HTTP requests and delegating them to the appropriate services. It defines API endpoints for the following operations:


1. **Get All Restaurants:** `GET /restaurants`
2. **Get Restaurant by ID:** `GET /restaurant/{id}`
3. **Add Restaurant:** `POST /restaurant`
4. **Add Restaurants:** `POST /restaurants`
5. **Update Restaurant Specialty:** `PUT /restaurant/id/{id}/specialty/{specialty}`
6. **Delete Restaurant:** `DELETE /restaurant/{id}`


### Services
The Services layer implements the core business logic, data processing, and interaction with the data repository. Key responsibilities include:

Validating input data.
Performing CRUD operations on restaurant data.
Handling data transformations and interactions with external systems (if applicable).

### Repository

The Repository layer manages data access to the underlying database. It handles database operations such as Create, Read, Update, and Delete (CRUD) for restaurant data.

## Project Summary

The Restaurant Management Application is a robust Spring Boot application designed for efficient restaurant data management. It offers a set of RESTful API endpoints for various restaurant-related operations, including adding, retrieving, updating, and deleting restaurant information.

- RESTful API endpoints for restaurant management.
- Data validation to ensure data integrity.
- Clean code separation with a layered architecture (Controller, Services, Repository).
- Robust error handling for improved reliability.
- Java-based backend and Maven for build management.

# Thank You
