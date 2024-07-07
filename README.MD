# Blood-Bank-Management-System-DBMS (V sem Mini-Project)

## Overview

The Blood Bank Management System is a web application designed to manage blood donations and inventory for a blood bank. It allows administrators to add and manage donor information, check blood stock levels, track donation history, and handle user accounts.

## Features

- **Add Person**: Register new donors with their details.
- **Add User**: Create and manage user accounts for the system.
- **Check Stock**: View the current blood stock levels.
- **Donation History**: Track the history of blood donations.
- **User Authentication**: Secure login and logout for users.
- **Responsive Design**: User-friendly interface compatible with various devices.

## Project Structure

```
Blood-Bank-Management-System/
├── .gitattributes
├── Add Person.php
├── Add User.php
├── addPerson.php
├── addUser.php
├── Check Stock.php
├── checkStock.php
├── connection.php
├── CONTRIBUTING.MD
├── Donation History.php
├── donationHistory.php
├── favicon.ico
├── footer.php
├── header.php
├── Home.php
├── index.php
├── LICENSE
├── login.php
├── logout.php
├── css/
│   ├── index.css
│   └── main.css
├── database/
│   └── blood_bank.sql
├── docs/
│   └── Blood managemet.docx
├── res/
│   └── images/
│       ├── bg.png
│       └── logo.png
```

## Getting Started

### Prerequisites

- A web server (e.g., Apache)
- PHP installed on the server
- MySQL or MariaDB database server

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/Blood-Bank-Management-System.git
   ```

2. **Navigate to the project directory:**
   ```bash
   cd Blood-Bank-Management-System
   ```

3. **Import the database:**
   - Create a new database in your MySQL server.
   - Import the `blood_bank.sql` file located in the `database` directory into your database.
   
4. **Configure the database connection:**
   - Open `connection.php`.
   - Update the database connection details (hostname, username, password, database name) according to your setup.

5. **Deploy the application:**
   - Place the project files in your web server's root directory.
   - Access the application via your web browser.

### Usage

- **Login**: Use the `login.php` page to log in with your credentials.
- **Dashboard**: Access different functionalities from the home page after logging in.


