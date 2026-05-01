🏥 Doctor Appointment System (Edoc)
📌 Overview

Edoc is a simple open-source web-based doctor appointment booking system developed using PHP, MySQL, HTML, and CSS. It allows patients to book appointments online, doctors to manage their schedules, and administrators to control system operations efficiently.

🎯 Objective

The main goal of this system is to digitize the traditional appointment booking process and provide an easy, fast, and organized platform for patients and doctors.

⚙️ Features
👑 Admin
Add, edit, and delete doctors
Manage doctor schedules
View patient details
View all appointment bookings
🩺 Doctor
View appointments
Manage scheduled sessions
View patient details
Edit account settings
Delete account
👤 Patient
Register and create account
Book appointments online
View appointment history
Edit account settings
Delete account
🔐 Default Login Credentials
Role	Email	Password
Admin	admin@edoc.com
	123
Doctor	doctor@edoc.com
	123
Patient	patient@edoc.com
	123
🛠️ Technologies Used
Frontend: HTML, CSS
Backend: PHP
Database: MySQL
Server: XAMPP
🚀 Installation Guide
Start Apache and MySQL in XAMPP
Extract the project folder

Copy it into:

C:\xampp\htdocs\

Open phpMyAdmin:

http://localhost/phpmyadmin
Create a database named edoc
Import the file DATABASE edoc.sql

Run the project:

http://localhost/edoc-doctor-appointment-system-main/
🗄️ System Architecture
User → Browser → Apache Server → PHP → MySQL Database → Response
✨ Key Highlights
Role-based login system
Online appointment booking
Schedule management
Simple and user-friendly interface
⚠️ Limitations
Runs only on local server
No online payment integration
Basic UI design
🚀 Future Enhancements
Online payment system
Email/SMS notifications
Improved UI/UX
AI-based doctor recommendation
