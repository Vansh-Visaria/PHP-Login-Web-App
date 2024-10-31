# PHP Login Web-App

This project is a simple, secure PHP-based login system for web applications. It includes basic authentication features, such as user login, password hashing, and session management.

## Features

- User Login
- Password Hashing for Security
- Session Management
- MySQL Database Integration

## File Structure

- `connection.php`: Handles database connection using MySQL.
- `index.php`: The main landing page displayed after successful login.
- `login.php`: The login form where users enter their credentials.

## Getting Started

### Prerequisites

- PHP 7.0 or higher
- MySQL or MariaDB
- Web Server (e.g., Apache)

### Installation

1. **Clone the Repository**  
   Clone this repository to your local machine:
   ```bash
   git clone https://github.com/Vansh-Visaria/PHP-Login-Web-App.git
Database Setup

Create a MySQL database.
Add a users table with the following fields: id, username, password.
Update database credentials in connection.php.
Configuration

Modify connection.php with your database connection settings:
php
Copy code
$servername = "your_server";
$username = "your_username";
$password = "your_password";
$dbname = "your_database";
Run the Application

Start your server and access login.php in your browser.
Usage
Access the login form at login.php.
Enter your username and password.
On successful login, you will be redirected to index.php.
