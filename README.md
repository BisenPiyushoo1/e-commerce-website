🛒 E-Commerce Platform API
📌 Overview

A scalable full-stack E-Commerce application built using Java and Spring Boot for backend services and React for frontend. The system supports product management, user authentication, cart operations, and order processing with a focus on performance and secure API design.

🚀 Features
User Management
User Registration & Login
JWT-based Authentication
Role-Based Access Control (Admin/User)
Product Management
Add, update, delete products (Admin)
View all products with filtering
Pagination for large datasets
Cart Functionality
Add items to cart
Remove items from cart
Update product quantity
Persistent cart handling
Order Management
Place orders securely
View order history
Order processing and tracking
🔐 Security Implementation
Stateless authentication using JWT
Role-based authorization with Spring Security
Password encryption using BCrypt
Secured REST APIs with proper access control
🛠 Tech Stack

Backend

Java 17
Spring Boot
Spring Security
Spring Data JPA (Hibernate)

Frontend

React.js
HTML, CSS, JavaScript
Bootstrap

Database

MySQL

Tools

Maven
Postman
Git & GitHub
🏗️ Architecture
Controller → Service → Repository → Database
Controller: Handles API requests
Service: Business logic
Repository: Database interaction
🔗 API Endpoints (Sample)
POST /api/auth/register → Register user
POST /api/auth/login → Login user
GET /api/products → Get all products
POST /api/products → Add product (Admin)
POST /api/cart/add → Add item to cart
GET /api/cart → View cart
POST /api/orders → Place order
GET /api/orders → View user orders
🗄 Database
MySQL relational database
Entities:
User
Product
Cart
Order
Managed relationships using JPA
