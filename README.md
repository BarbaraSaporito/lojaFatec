# Clothing Store - Atlética Fatec Ipiranga

Welcome to the Clothing Store of the Atlética Fatec Ipiranga! This project is a web application built with Spring Boot for the backend and Angular for the frontend. The store offers essential functionalities to manage customers, products, shopping carts, and orders.

<a href="https://imgur.com/UtmKs7D"><img src="https://i.imgur.com/UtmKs7D.png" title="source: imgur.com" /></a>

## Features

### 1. Customer
   - **Customer Registration:** Users can register as customers, providing information such as name, address, and contact details.

### 2. Product
   - **Product Management:** Administrators can add, edit, and delete products from the store. Each product has information such as name, description, price, and stock quantity.

### 3. Cart
   - **Shopping Cart:** Customers can add products to the shopping cart while browsing the store.

### 4. Order
   - **Order Placement:** Customers can review the items in their cart and place orders, providing delivery details.

## Project Structure

The project is organized into various directories, each responsible for a specific functionality. Additionally, there are main files that play crucial roles in the application.

### Directories

1. **customer:** Contains files related to the customer functionality.
2. **product:** Manages the products available in the store.
3. **cart:** Responsible for the logic of the shopping cart.
4. **order:** Involves the placement and processing of orders.

### Main Files

1. **AppController.java:** Main controller of the Spring Boot application.
2. **CustomerComponent.ts:** Angular component for customer management.
3. **ProductService.java:** Spring Boot service for product management.
4. **CartComponent.ts:** Angular component for the shopping cart.
5. **OrderController.java:** Spring Boot controller for order placement.

## How to Run the Project

Follow these instructions to run the application on your local environment:

1. **Backend (Spring Boot):**
   - Navigate to the `backend` directory.
   - Run the command `./mvnw spring-boot:run` to start the server.

2. **Frontend (Angular):**
   - Navigate to the `frontend` directory.
   - Run the command `ng serve` to start the development server.

3. Open your browser and access `http://localhost:4200/` to view the application.

## How to Contribute

Your contribution is valuable to improve this clothing store! If you have ideas, corrections, or new features, feel free to open an issue or submit a pull request.

Thank you for contributing to the Atlética Fatec Ipiranga clothing store! 🎉
