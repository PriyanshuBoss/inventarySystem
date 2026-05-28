# Inventory Management System

A complete web-based **Inventory Management System** developed using **PHP** and **MySQL**. This system helps businesses manage inventory levels, customer orders, sales, deliveries, and billing efficiently. It also supports PDF bill generation and OTP verification using SMS APIs.

---

## Features

* Manage inventory levels
* Add, update, and delete products
* Manage product categories and brands
* Customer order management
* Sales and delivery tracking
* Generate customer bills in PDF format
* User registration and authentication
* Forgot password with OTP verification
* Dashboard for inventory overview

---

## Technologies Used

### Frontend

* HTML5
* CSS3
* JavaScript
* Bootstrap 4
* jQuery

### Backend

* PHP 7

### Database

* MySQL

### APIs

* Time and Date API
* TextLocal API (for sending One Time Passwords)

### Libraries

* FPDF Library (for PDF bill generation)

---

## Project Structure

```bash
├── database/
├── images/
├── includes/
├── javascript/
├── templates/
├── dashboard.php
├── index.php
├── register.php
├── orders.php
├── manage_products.php
├── manage_category.php
├── manage_brands.php
├── forgotPassword.php
├── changelog.htm
└── README.md
```

---

## Installation Guide

### Prerequisites

Make sure you have the following installed:

* XAMPP / WAMP / LAMP
* PHP 7+
* MySQL

---

## Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/inventory-management-system.git
```

### 2. Move the Project Folder

Move the project folder into your server directory.

For XAMPP:

```bash
htdocs/
```

### 3. Import the Database

* Open **phpMyAdmin**
* Create a new database
* Import the `localhost.sql` file

### 4. Configure Database Connection

Update database credentials inside the project configuration files if required.

### 5. Run the Project

Open your browser and visit:

```bash
http://localhost/project-folder/index.php
```

---

## Default Functionalities

* Admin login and registration
* Product and inventory management
* Billing and invoice generation
* Order tracking
* Password recovery using OTP

---

## PDF Billing

Bills are automatically generated in **PDF format** using the **FPDF Library**.

---

## Screenshots

*Add project screenshots here*

---

## Future Improvements

* Role-based authentication
* Advanced analytics dashboard
* Barcode scanning support
* Email notifications
* REST API integration

---

## License

This project is open-source and available for educational purposes.

---

## Author

Developed by **PriyanshuBoss**
