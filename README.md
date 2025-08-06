Warehouse Management System (WMS)
A simple PHP-based Warehouse Management System that allows managing products, suppliers, sales, and users with a secure login system.

📦 Features
User Authentication: Login & Logout functionality

Product Management: Add, edit, delete, and view products

Supplier Management: Maintain supplier records

Sales Management: Track sales and generate sales reports

User Management: Admin can manage user accounts

Database Support: Includes database.sql for easy setup

🔑 Default Login Credentials
Username: anmol

Password: anmol

(Change these after first login for security.)

🛠️ Technologies Used
Frontend: HTML, CSS, JavaScript

Backend: PHP

Database: MySQL

Server: Apache (XAMPP/WAMP recommended)

🚀 Installation
Clone the repository

bash
Copy
Edit
git clone https://github.com/yourusername/warehouse-management-system.git
Move the project to your local server directory

Example for XAMPP: C:/xampp/htdocs/warehouse-management-system

Create the database

Open phpMyAdmin

Create a database (warehouse-management-system)

Import the database.sql file from the project folder

Configure database connection

Open includes/config.php

Update the database credentials if needed

Run the project

Start Apache & MySQL in XAMPP

Visit: http://localhost/warehouse-management-system

📂 Project Structure
pgsql
Copy
Edit
warehouse-management-system/
│-- index.php
│-- login.php
│-- home.php
│-- products.php
│-- suppliers.php
│-- sales.php
│-- users.php
│-- database.sql
│
├─ assets/
│   ├─ css/ (style.css)
│   ├─ js/ (script.js)
│   └─ images/ (logo.png)
│
├─ includes/
│   ├─ config.php
│   ├─ db_connect.php
│   ├─ header.php / footer.php
│   └─ functions.php
│
├─ _actions/
│   ├─ add_product.php / edit_product.php / delete_product.php
│   ├─ add_supplier.php / edit_supplier.php / delete_supplier.php
│   ├─ add_sale.php / edit_sale.php / delete_sale.php
│   └─ add_user.php / edit_user.php / delete_user.php
│
└─ uploads/
    ├─ products/
    └─ users/
👨‍💻 Author
Anmol Som
