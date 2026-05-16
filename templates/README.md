# Secure Login System

## Overview
This project is a secure web-based login system developed using Flask, SQLite, and bcrypt password hashing. The application allows users to register, login securely, manage sessions, and logout safely.

The project demonstrates important cybersecurity concepts such as password hashing, session management, and SQL injection prevention.

---

## Features
- User Registration
- Secure User Login
- Password Hashing using bcrypt
- Session Management
- Logout Functionality
- SQLite Database Integration
- SQL Injection Protection
- Basic Input Validation

---

## Technologies Used
- Python
- Flask
- Flask-Bcrypt
- SQLite
- HTML/CSS

---

## Security Features

### Password Hashing
Passwords are securely hashed using bcrypt before storing them in the database.

### SQL Injection Protection
Parameterized SQL queries are used to prevent SQL injection attacks.

### Session Management
User sessions are managed securely using Flask sessions.

---

## Project Structure

```text
Secure-Login-System/
│
├── app.py
├── users.db
├── templates/
│   ├── login.html
│   ├── register.html
│   └── dashboard.html
└── README.md