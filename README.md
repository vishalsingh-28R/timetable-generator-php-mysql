# Timetable Generator System

A PHP and MySQL web application for managing academic timetable information. It includes tools to manage teachers, classes, classrooms, subjects, and time slots, along with timetable generation and teacher time-slot conflict checks.

## Features

- Admin login and dashboard.
- Add and manage teachers, classes, classrooms, and subjects.
- Allocate subjects to classes and teachers.
- Configure timetable time slots.
- Generate and view timetables.
- Check teacher time-slot conflicts.
- Store application data in a MySQL database.

## Technologies Used

- PHP
- MySQL
- PDO
- HTML and CSS
- Bootstrap
- JavaScript and jQuery

## Project Structure

- `admin/` - Admin pages and management modules.
- `assets/` - CSS, fonts, images, and JavaScript assets.
- `css/` - Stylesheets.
- `js/` - JavaScript files.
- `index.php` - Main application entry page.
- `timetable_db.sql` - Database SQL file.

## How to Run

**Prerequisites:** XAMPP with Apache, MySQL, and PHP.

1. Clone or download this repository.
2. Place the project folder inside the XAMPP `htdocs` directory.
3. Start Apache and MySQL from the XAMPP Control Panel.
4. Open `http://localhost/phpmyadmin` in your browser.
5. Create a database named `timetable_db` and import `timetable_db.sql`.
6. Check the database settings in `admin/includes/dbconnection.php` and update them if needed.
7. Open `http://localhost/timetable-generator-php-mysql/` in your browser.

## Author

Vishal Singh

GitHub: https://github.com/vishalsingh-28R
