# 🍔 Swiggy Food Ordering System

## 📌 Project Overview

Swiggy Food Ordering System is a backend REST API application developed using Java, Spring Boot, Spring Security, Hibernate, and MySQL. The application allows Admins to manage restaurants and food items, Customers to browse the menu and place orders, and Delivery Partners to deliver customer orders.

---

## 🚀 Features

- User Registration
- Role-Based Authentication (Admin, Customer, Delivery Partner)
- Restaurant Manaements
- Food Item Management
- View Food Menu
- Place Food Order
- Assign Delivery Partner
- Order Status Management
- RESTful APIs
- MySQL Database Integration

---

## 🛠️ Technologies Used

- Java 21
- Spring Boot
- Spring Data JPA
- Hibernate
- Spring Security
- MySQL
- Maven
- Postman

---

## 👥 User Roles

### Admin
- Register
- Add Restaurant
- Add Food Items
- Assign Delivery Partner

### Customer
- Register
- View Food Menu
- Place Order

### Delivery Partner
- Register
- Deliver Assigned Orders

---

## 📂 Project Structure

```
src
 ├── controller
 ├── model
 ├── dao
 ├── security
 ├── service
 └── SwiggyApplication
```

---

## 🗄️ Database Tables

- User
- Restaurant
- FoodItem
- FoodOrder

---

## 🔄 Project Flow

1. Register Users (Admin, Customer, Delivery Partner)
2. Admin Login
3. Add Restaurant
4. Add Food Items
5. Customer Login
6. View Menu
7. Place Order
8. Admin Assign Delivery Partner
9. Order Delivered

---

## 🔐 Security

Spring Security is used for Role-Based Authentication.

- ADMIN → Restaurant & Food Management
- CUSTOMER → View Menu & Place Order
- DELIVERY_PARTNER → Delivery Operations

Authentication Method:
- Basic Authentication

---

## 📬 API Endpoints

### Authentication
- POST `/auth/register`

### Admin
- POST `/admin/addrest`
- POST `/admin/addfood`
- PUT `/admin/assign/{orderId}/{partnerId}`

### Customer
- GET `/customer/menu`
- POST `/customer/order/{customerId}`

---

## 🧪 API Testing

All REST APIs were tested using Postman.

---

## 🎯 Future Enhancements

- JWT Authentication
- Password Encryption (BCrypt)
- Payment Integration
- Order Tracking
- Email Notifications
- Swagger Documentation

---

## 👨‍💻 Developed By

**Marisha Ragavi**

Java Full Stack Developer
