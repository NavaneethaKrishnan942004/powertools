# Power Tools Management System

## Overview

Power Tools Management System is a web-based application designed to manage power tool sales and rentals efficiently. It provides separate dashboards for users and administrators, enabling smooth handling of orders, rentals, and inventory.

This system helps automate manual shop operations such as order tracking, rental management, and product handling.

## Features

## User Panel

* User Registration & Login
* Browse Power Tools & Rental Tools
* Add to Cart / Wishlist
* Place Orders & Book Rentals
* View Order History
* Submit Product Reviews

### Admin Panel

* Dashboard with User Activity Overview
* Manage Categories
* Add/Edit/Delete Power Tools
* Rental Tool Management (Check-in / Check-out)
* Order Management:

  * Today’s Orders
  * Pending Orders
  * Delivered Orders
* Sales Notes Management
* Reports for Rentals & Sales


## Technologies Used

### Frontend

* HTML
* CSS
* JavaScript
* Bootstrap

### Backend

* PHP

### Database

* MySQL

### Environment

* Windows 11
* XAMPP / WAMP Server

---

## Database Structure

Main tables used:

* Admin
* Users
* Categories
* Power Tools
* Rental Tools
* Orders
* Order Tracking History
* Product Reviews
* Wishlist
* Tool Rental List

---

## Installation & Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/zamzam-power-tools.git
   ```

2. Move project folder to:

   ```
   htdocs (for XAMPP)
   ```

3. Import database:

   * Open phpMyAdmin
   * Create a new database
   * Import the provided `.sql` file

4. Configure database connection:

   * Open `config.php`
   * Update database name, username, and password

5. Run the project:

   ```
   http://localhost/power-tools
   ```

---

## 🔐 Admin Login (Sample)

* Username: admin
* Password: admin123

---

## 📊 Project Highlights

* Full-stack web application using PHP & MySQL
* Role-based access (Admin & User)
* Real-time order and rental tracking
* Structured database design
* Scalable for small business operations

---

## 📈 Future Enhancements

* Online Payment Integration
* Mobile Responsive UI Improvements
* Notification System (Email/SMS)
* Advanced Analytics Dashboard

---

## 👨‍💼 Author

Navaneetha Krishnan

---

## 📜 License

This project is for educational purposes.
