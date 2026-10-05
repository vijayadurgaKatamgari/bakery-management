# 🍰 Home Bakery Order Management System

A full-stack PBL project using Java 17, Spring Boot, React, MySQL, JPA/Hibernate and REST APIs.

## Features
- Bakery product listing
- Product categories
- Product customization
- Quantity and delivery date
- Customer contact/address validation
- Order creation
- Order confirmation
- Delivery status model
- Baker-side order API
- Product CRUD APIs
- MySQL persistence

## Architecture
React → REST API → Spring Boot Controller → Service → JPA Repository → Hibernate → MySQL

## Backend setup
1. Install Java 17 and Maven.
2. Install MySQL.
3. Create the database using `database/bakery.sql`.
4. Edit `backend/src/main/resources/application.properties` and replace `YOUR_MYSQL_PASSWORD`.
5. Run:
   `cd backend`
   `mvn spring-boot:run`

Backend: http://localhost:8080

## Frontend setup
1. Install Node.js.
2. Run:
   `cd frontend`
   `npm install`
   `npm run dev`

Frontend: http://localhost:5173

## Main APIs
GET `/api/products`
POST `/api/products`
PUT `/api/products/{id}`
DELETE `/api/products/{id}`

GET `/api/orders`
POST `/api/orders`
GET `/api/orders/{id}`
PUT `/api/orders/{id}/status`

## GitHub
Push the complete folder to GitHub after testing locally.
