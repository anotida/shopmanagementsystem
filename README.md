
# Spring Developer Coding Interview Test

### Spring Boot Developer Test: Shop and Departments API

This test simulates an e-commerce scenario where a Spring Boot REST API needs to be developed for managing shops and departments within those shops.

### Technical Skills Assessed:
* Spring Boot application creation
* JPA or similar ORM for data persistence
* RESTful API design with Spring MVC or WebFlux
* Basic CRUD operations (Create, Read, Update, Delete)

### Story:
Imagine a retail company with multiple shops across different locations. Each shop has various departments selling specific product categories (e.g., clothing, electronics, books).

#### Task:
* Design the entities representing Shop and Department:
    * Define attributes for each entity (e.g., Shop: id, name, location; Department: id, name, shop (reference to Shop entity))
    * Consider relationships between Shop and Department (One-to-Many)
* Develop a Spring Boot application with the following functionalities:
    * API Endpoints
      * GET /shops: Retrieve all shops
      * GET /shops/{id}: Retrieve a shop by its ID
      * POST /shops: Create a new shop
      * PUT /shops/{id}: Update a shop's details
      * DELETE /shops/{id}: Delete a shop
      * GET /shops/{shopId}/departments: Retrieve all departments within a specific shop
      * POST /shops/{shopId}/departments: Create a new department within a specific shop
      * PUT /shops/{shopId}/departments/{departmentId}: Update a department's details
      * DELETE /shops/{shopId}/departments/{departmentId}: Delete a department
* Implement basic CRUD operations for both Shop and Department entities using appropriate HTTP methods.
* (Optional) Implement security measures for the API (e.g., user authentication)

### Evaluation Criteria:
* Code clarity and adherence to best practices
* Functionality and completeness of the API endpoints
* Use of JPA or similar ORM for data persistence
* Exception handling and error responses
* (Optional) Security implementation

