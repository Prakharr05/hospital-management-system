# Hospital Management System

A comprehensive management platform for healthcare facilities, featuring patient record tracking, doctor scheduling, and billing automation. This web-based application is designed to streamline hospital operations by providing distinct interfaces for administrators, doctors, and patients.

## 🚀 Features
* **Admin Dashboard:** Comprehensive control over doctor records, patient lists, and appointment oversight (`admin-panel.php`, `admin-panel1.php`).
* **Doctor Management:** Specialized tools for doctors to manage schedules and search for patients (`doctor-panel.php`, `doctorsearch.php`).
* **Patient Search & Tracking:** Efficient search functionality for both patient and doctor databases (`patientsearch.php`, `doctorsearch.php`).
* **Prescription & Reports:** Integrated system for issuing and managing medical prescriptions (`prescribe.php`).
* **Document Generation:** Automated PDF generation for reports and invoices using the **TCPDF** library.
* **Responsive Frontend:** Built with custom CSS and enhanced with **Font-Awesome** iconography (`style1.css`, `style2.css`, `font-awesome/`).

## Prerequisites
1. Install XAMPP web server
2. Any Editor (Preferably VS Code or Sublime Text)
3. Any web browser with latest version

## 🛠️ Languages and Technologies used
1. HTML5/CSS3
2. JavaScript (to create dynamically updating content)
3. Bootstrap (An HTML, CSS, and JS library)
4. XAMPP (A web server by Apache Friends)
5. Php
6. MySQL (An RDBMS that uses SQL)
7. TCPDF (to generate PDFs)

## 📂 Steps to run the project in your machine
1. Download and install XAMPP in your machine
2. Clone or download the repository
3. Extract all the files and move it to the 'htdocs' folder of your XAMPP directory.
4. Start the Apache and Mysql in your XAMPP control panel.
5. Open your web browser and type 'localhost/phpmyadmin'
6. In phpmyadmin page, create a new database from the left panel and name it as 'myhmsdb'
7. Import the file 'myhmsdb.sql' inside your newly created database and click ok.
8. Open a new tab and type 'localhost/foldername' in the url of your browser
9. Hurray! That's it!



### Starting Apache And MySQL in XAMPP:
  The XAMPP Control Panel allows you to manually start and stop Apache and MySQL. To start Apache or MySQL manually, click the ‘Start’ button under ‘Actions’.

## 📂 Project Structure
* `myhmsdb.sql`: The primary SQL file to initialize the database schema.
* `func.php`: Contains core backend logic and helper functions for database communication.
* `vendor/`: Directory containing PHP dependencies installed via Composer.
* `assets/` & `css/`: Core design and layout files.

## ⚙️ Installation Guide

1. **Clone the Repository:**
   ```bash
   git clone [https://github.com/YOUR_USERNAME/hospital-management-system.git](https://github.com/YOUR_USERNAME/hospital-management-system.git)
