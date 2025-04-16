Skill India Website

This is a Skill India initiative website, designed to provide an online learning platform with functionalities like registration, login, and course management. It includes both frontend and backend components for a seamless user experience.

Project Overview

This project aims to build a platform for online learning, where users can access courses, learn new skills, and track their progress. The website includes features like:

User Registration

User Login

Course Management

Database Integration

Admin Panel for managing users and courses.

Technologies Used
Frontend:

HTML

CSS

JavaScript

Bootstrap (for responsive UI)

Backend:

PHP (for server-side logic)

MySQL (for database management)

Tools:

XAMPP (for local server setup)

Features
User can register and log in to access courses.

Admin can manage users, view user statistics, and add new courses.

User can enroll in courses and track their progress.

Prerequisites
XAMPP/WAMP/MAMP: You need a local server environment to run this project.

PHP 7.4 or higher: Ensure PHP is installed and configured correctly.

MySQL Database: You will need a MySQL database with the schema and tables created.

**Setup Instructions
**1. Clone the Repository****

Clone this repository to your local machine using Git:


git clone https://github.com/your-username/Skill-India-Website.git

**2. Place Project Files in XAMPP**

Copy the entire Skill-India-Website folder to the htdocs directory in your XAMPP installation (usually located in C:\xampp\htdocs).

**3. Database Setup**

Open phpMyAdmin (usually available at http://localhost/phpmyadmin).

Create a new database named db_elearning.

Import the sql/database.sql file (located in the project folder) into the db_elearning database.

**4. Configuration**

Open the include/database.php file.

Set the database credentials as per your MySQL setup:


private $db_host = "localhost";  
private $db_user = "root";       
private $db_pass = "";           
private $db_name = "db_elearning"; 

**5. Running the Website**
Start Apache and MySQL from the XAMPP control panel.

Open a browser and go to:


http://localhost/Skill
This should load the homepage of the Skill India website.

