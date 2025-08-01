# Product Application

## Overview
The Product Application is a Spring Boot project that provides a RESTful API for managing products. It utilizes Spring Data JPA for database interactions, Spring Security for securing the application, and MySQL as the database.

## Features
- Create, Read, Update, and Delete (CRUD) operations for products.
- Secure endpoints using Spring Security.
- Connects to a MySQL database for persistent storage.

## Technologies Used
- Spring Boot
- Spring Web
- Spring Data JPA
- MySQL
- Spring Security

## Getting Started

### Prerequisites
- Java 11 or higher
- Maven
- MySQL Server

### Setup Instructions

1. **Clone the repository**
   ```
   git clone <repository-url>
   cd product-application
   ```

2. **Configure MySQL Database**
   - Create a new database in MySQL.
   - Update the `src/main/resources/application.properties` file with your database connection details.

3. **Build the project**
   ```
   mvn clean install
   ```

4. **Run the application**
   ```
   mvn spring-boot:run
   ```

5. **Access the API**
   - The application will be running on `http://localhost:8080`.
   - Use tools like Postman or curl to interact with the API.

## API Endpoints
- `GET /products` - Retrieve all products
- `GET /products/{id}` - Retrieve a product by ID
- `POST /products` - Create a new product
- `PUT /products/{id}` - Update an existing product
- `DELETE /products/{id}` - Delete a product

## License
This project is licensed under the MIT License.