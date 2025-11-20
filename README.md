🎯 Overview

This Restaurant Website & Management System is a complete solution built using PHP 7.4, MySQL, HTML/CSS, JavaScript, and SCSS.
It includes a modern customer-facing website and a powerful Admin Panel for managing reservations, menu items, users, and content.

🚀 Features:
👨‍🍳 Customer Website (users side)

✔️ Browse food/menu items
✔️ View restaurant details
✔️ Make table bookings
✔️ Contact the restaurant
✔️ User login & registration
✔️ Profile management
✔️ Responsive, mobile-friendly UI

🛠️ Admin Panel (admin-panel/)

✔️ Manage reservations
✔️ CRUD for menu items & food images
✔️ Manage users
✔️ Upload images & update website sections
✔️ Admin authentication
✔️ Dashboard with quick stats
✔️ Organized module structure

📁 Project Structure
📦 Project Root
├── SQL_FILE/         → Database .sql file(s)
├── admin-panel/      → Admin dashboard & management modules
├── auth/             → Login / Register / Logout / Sessions
├── config/           → Database config files
├── css/              → Compiled CSS
├── scss/             → SCSS styling files
├── js/               → JavaScript files
├── img/              → Website images
├── food/             → Food/item images
├── includes/         → Reusable components (header, footer)
├── lib/ and libs/    → Library files
├── users/            → Customer-side pages
│
├── index.php         → Homepage
├── about.php         → About page
├── booking.php       → Booking form
├── booking-table.php → Table reservation page
├── contact.php       → Contact page
├── 404.php           → Custom error page

⚙️ Setup Guide (XAMPP / Localhost)

📌 Step-by-step Installation
Install XAMPP

Start Apache & MySQL

Copy the project folder into:
C:\xampp\htdocs\

Open phpMyAdmin → Create database:
restaurantdb

Import SQL file from:
SQL_FILE/

Check config/config.php and edit if needed:
$host = "localhost";
$user = "root";
$pass = "";
$dbname = "restaurantdb";


🖼️ Screenshots
![5577e8b1-6047-441d-9929-06e641863651](https://github.com/user-attachments/assets/0a029de3-973e-4640-8b57-0f6e26a09838)


