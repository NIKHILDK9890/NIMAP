# NimapProject - Category & Product Management API

This API is designed to handle the management of products and their associated categories. It supports various CRUD (Create, Read, Update, Delete) operations, allowing users to add, modify, retrieve, and remove products. Each product is linked to a specific category for efficient data organization and management.

This project is a Spring Boot-based RESTful API for managing products and categories with MySQL integration. It provides easy-to-use endpoints for performing CRUD actions on both categories and products.

# Key Features:
Full CRUD support for Categories.
Full CRUD support for Products.
Relational mapping between categories and products.
MySQL database integration for storing data.
API tested using Postman for functionality validation.
APIs can be tested directly through the browser.
Prerequisites:
Before setting up and running the application, make sure you have the following installed:

# Database Configuration:
This project uses MySQL for data storage. You’ll need to configure the database credentials in application.properties:

spring.datasource.url=jdbc:mysql://localhost:3306/NIMAP
spring.datasource.username=root
spring.datasource.password=Password
spring.jpa.hibernate.ddl-auto=update
