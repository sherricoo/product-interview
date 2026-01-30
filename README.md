# Product Management Application

## Interview Scenarios

### Scenario: Display list of products
**Given** the backend is running  
**When** the user opens the product page  
**Then** the system displays a list of products  

---

### Scenario: Add a new product
**Given** the user is on the product page  
**When** the user enters a product name  
**And** clicks the Add button  
**Then** the product is saved  
**And** the product list is updated  

---

## Spring Boot Backend

### Description
This Spring Boot application provides a simple REST API for managing products.

It supports:
- Retrieving a list of products
- Adding a new product with basic validation

### Tech Stack
- Spring Boot
- Spring Web
- Spring Data JPA
- PostgreSQL

### Prerequisites
- Java 17
- Maven 3.8+
- PostgreSQL running locally

### Build & Run

```bash
mvn clean install
mvn spring-boot:run
