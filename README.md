# NexaMart - E-Commerce Platform

A full-stack e-commerce web application that allows users to browse products, manage their shopping carts, and place orders with integrated online payments. The platform includes dedicated portals for Administrators to manage the catalog and for Delivery Personnel to track assigned orders.

## Project Structure

This repository is divided into two main parts:

* **`/frontend`**: Contains the React.js user interface.
* **`/backend`**: Contains the Java Spring Boot REST API.

## High-Level Features

* **Role-Based Access:** Three distinct user roles: Admin, Customer, and Delivery Person.
* **Product Catalog:** Admins can add, update, and manage product categories and inventory.
* **Shopping & Checkout:** Customers can add items to their cart and checkout securely.
* **Payment Integration:** Integrated with Razorpay for handling online transactions.
* **Order Tracking & Delivery:** Admins can assign orders to Delivery Personnel, who can then update the delivery status.
* **Email Verification:** OTP-based verification for password resets and secure actions.

## Getting Started

To run this project locally, you will need to start the backend server and the frontend development server separately. 

* For frontend setup instructions, see the [Frontend README](./frontend/README.md).
* For backend setup instructions, see the [Backend README](./backend/README.md).