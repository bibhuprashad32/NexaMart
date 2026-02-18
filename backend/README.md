# NexaMart Backend

The backend for the NexaMart E-commerce application is built as a monolithic REST API using Java and Spring Boot. 

## Tech Stack

* **Java 17+**
* **Spring Boot (2.7.x)**
* **Spring Data JPA / Hibernate:** For ORM and database interactions.
* **MySQL:** Relational database for storing users, products, categories, carts, and orders.
* **Razorpay Java SDK:** For processing online payment transactions.
* **Spring Boot Mail:** For sending OTPs and email notifications.
* **Log4j2:** For application logging.
* **Maven:** Dependency management.

## Core Modules

* **User Module:** Handles user registration, login, profile management, and OTP verification via email.
* **Product & Category Module:** Manages the e-commerce catalog, allowing CRUD operations on products and categories.
* **Cart & Order Module:** Handles adding items to the cart, generating order summaries, and managing the order lifecycle.
* **Payment Module:** Communicates with the Razorpay API to generate transaction requests and verify payment success.
* **Delivery Module:** Maps orders to specific delivery personnel and tracks fulfillment status.

## How to Run Locally

### Prerequisites
* Java Development Kit (JDK 17) installed.
* Maven installed.
* MySQL Server running locally.

### Database Setup
Ensure you have MySQL running. Check the `src/main/resources/application.properties` file to verify the database name, username, and password. You will need to create the empty database in your MySQL server before starting the app. Spring Data JPA will automatically generate the required tables.

### Steps
1. Open your terminal and navigate to the `backend` folder.
2. Run the application using Maven:
```bash
mvn spring-boot:run
```