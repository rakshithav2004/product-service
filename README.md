# Product Service

A Spring Boot REST API for managing products using basic CRUD operations.

## Tech Stack

* Java
* Spring Boot
* Spring Data MongoDB
* MongoDB
* REST API
* Bean Validation
* Swagger / OpenAPI
* Maven

## Features

* Create a product
* Get product by ID
* Get all products
* Update product
* Delete product
* Product validation
* MongoDB database integration
* Exception handling
* Pagination and filtering

## API Endpoints

| Method   | Endpoint                | Description       |
| -------- | ----------------------- | ----------------- |
| `POST`   | `/api/v1/products`      | Create a product  |
| `GET`    | `/api/v1/products/{id}` | Get product by ID |
| `GET`    | `/api/v1/products`      | Get products      |
| `PUT`    | `/api/v1/products/{id}` | Update a product  |
| `DELETE` | `/api/v1/products/{id}` | Delete a product  |

## Sample Product Request

```json
{
  "sku": "PHONE-001",
  "name": "Smartphone",
  "category": "Electronics",
  "description": "Sample smartphone",
  "price": 29999.00,
  "stock": 10
}
```

## Running the Application

### Prerequisites

* Java 21
* Maven
* MongoDB

### Run the Application

**Windows:**

```bash
mvnw.cmd spring-boot:run
```

**Linux/macOS:**

```bash
./mvnw spring-boot:run
```

## API Documentation

Swagger/OpenAPI documentation is available through Swagger UI when the application is running.

## Project Structure

```text
src/
└── main/
    ├── java/
    │   └── ...
    │       ├── controller/
    │       ├── service/
    │       ├── repository/
    │       ├── model/
    │       ├── dto/
    │       └── exception/
    └── resources/
        └── application.properties
```

# 🙌 Thank You

**Thank you for visiting this project!**
I hope you found it useful and informative. 😊
