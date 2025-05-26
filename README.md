
# 📚 Library Management System

A full-featured, desktop-based Library Management System built in Java using the Swing framework. This project is designed for libraries to manage books, members, borrowing history, returns, and fine calculations.

## 🔧 Technologies Used

- **Java** – Core programming language
- **Swing** – GUI toolkit for building the desktop interface
- **MySQL** – Backend database
- **JDBC** – Java Database Connectivity
- **NetBeans** – IDE used for development

## 🧩 Features

- 📖 Add, update, and remove books
- 👤 Manage library members
- 🔁 Borrow and return books with due date tracking
- 💰 Fine management for overdue returns
- 🔐 Admin login and authentication
- 📊 Reporting capabilities for issued/returned books

## 📁 Project Structure

Library-Management-System/
├── src/
│ ├── library/
│ │ ├── Login.java
│ │ ├── Dashboard.java
│ │ ├── BookManager.java
│ │ ├── MemberManager.java
│ │ └── IssueReturn.java
│ └── DBConnection.java
├── sql/
│ └── library_db.sql
├── README.md

## 🛠️ Setup Instructions

### Prerequisites

- JDK 8+
- NetBeans IDE
- MySQL Server

### Steps

1. **Clone the Repo**
   ```bash
  - git clone https://github.com/Bhanuka-Malshan/Library-Management-System.git
  -  cd Library-Management-System
Import to NetBeans
- Open NetBeans → File → Open Project → Select this folder

Set up MySQL
- Create a database: library_db
- Import sql/library_db.sql

Configure DB Connection
- Update DBConnection.java with your MySQL username and password

Run the App
- Click Run Project in NetBeans

🧪 Test Users
- Username: admin
- Password: admin123

