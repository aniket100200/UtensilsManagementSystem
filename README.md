# 🍽️ Utensile Management System (UMS)

![Java](https://img.shields.io/badge/Backend-Spring%20Boot-green)
![React](https://img.shields.io/badge/Frontend-Next.js-blue)
![Database](https://img.shields.io/badge/Database-MySQL-orange)
![Build](https://img.shields.io/badge/Build-Maven-red)

> A comprehensive full-stack inventory tracking solution designed for commercial kitchens to streamline procurement, track usage, and prevent stock shortages.

## 📖 Overview

The **Utensile Management System** is an enterprise-grade web application developed to solve the chaos of inventory management in high-volume culinary environments. It replaces manual spreadsheet tracking with a real-time, digital solution.

The system allows administrators to track utensil lifecycles, monitor stock levels in real-time, and automate purchase requests when inventory dips below a defined threshold.

### 🌟 Key Features

* **📊 Interactive Dashboard:** Visual analytics showing total inventory, low stock alerts, and recent transactions.
* **🔔 Low Stock Alerts:** Automated logic that flags items when they fall below the safety stock threshold.
* **📦 Inventory CRUD:** Full capability to Add, Update, Delete, and View utensil details (Categories, Material, Price, Supplier).
* **🔐 Secure Authentication:** JWT-based login system with Role-Based Access Control (Admin vs. Kitchen Staff).
* **🛒 Purchase Management:** Generate and track purchase orders for suppliers.
* **🔍 Search & Filter:** Advanced sorting using ag-grid/custom tables to find items instantly.

---

## 🛠️ Tech Stack

### Backend
* **Framework:** Java Spring Boot (v3.x)
* **Security:** Spring Security & JWT (JSON Web Tokens)
* **Database:** MySQL 8.0
* **ORM:** Hibernate / Spring Data JPA
* **API Documentation:** Swagger UI / OpenAPI 3.0
* **Build Tool:** Maven

### Frontend
* **Framework:** React.js
* **Styling:** SCSS
* **State Management:** Redux Toolkit / Context API
* **HTTP Client:** Axios
* **Icons:** React Icons / Lucide

---

## 🚀 Getting Started

Follow these instructions to set up the project locally.

### Prerequisites
* Java Development Kit (JDK) 17+
* Node.js (v18+)
* MySQL Server

### 1. Backend Setup (Spring Boot)

```bash
# Clone the repository
git clone [https://github.com/yourusername/utensile-management-system.git](https://github.com/yourusername/utensile-management-system.git)

# Navigate to backend directory
cd backend

# Update database configuration
# Open src/main/resources/application.properties and check:
# spring.datasource.url=jdbc:mysql://localhost:3306/utensile_db
# spring.datasource.username=root
# spring.datasource.password=your_password

# Run the application
./mvnw spring-boot:run
