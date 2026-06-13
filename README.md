# Library Management System

A simple web-based Library Management System built using HTML, CSS, PHP, and MySQL. This project allows an admin to manage books, members, staff, book issuing and returning through an easy-to-use dashboard.

---

## Aim

To design and develop a Library Management System that helps manage books, members, staff, issued books and returns through a simple web-based interface.

---

## About the Project

In most libraries, records are maintained manually using registers which is time consuming and error prone. This project solves that problem by digitizing library operations. The admin can add and manage books, members and staff, issue books to members, process returns, and the system automatically calculates fines for late returns.

---

## Features

- Admin Login (secure session-based authentication)
- Add, view, and delete books
- Add, view, and delete members
- Add, view, and delete staff
- Issue books to members with due dates
- Return books with automatic fine calculation (Rs. 5/day for late returns)
- Dashboard with live statistics (total books, members, staff, issued books)

---

## Tech Stack

| Layer | Technology |
|-------|-----------|
| Frontend | HTML, CSS |
| Backend | PHP |
| Database | MySQL |
| Server | Apache (XAMPP) |
| Editor | VS Code |

---

## Database Tables

1. admin - Admin login credentials
2. staff - Library staff details
3. members - Library member details
4. books - Book inventory details
5. issued_books - Records of issued and returned books

---

## Setup Instructions

1. Install XAMPP and start Apache and MySQL
2. Copy the project folder into C:\xampp\htdocs\
3. Open http://localhost/phpmyadmin, create a database named library_db
4. Run the SQL script (library_db.sql) to create the required tables
5. Open the project in browser:
   ```
   http://localhost/library_ms/index.php
   ```
6. Login with default credentials:
   - Username: admin
   - Password: admin123

---

## System Requirements

### Hardware
- Intel Core i3 or above
- 2GB RAM minimum
- 10GB free disk space

### Software
- Windows 10/11
- XAMPP (Apache + MySQL)
- PHP
- Google Chrome / Edge
- VS Code

---

## Project Structure

```
library_ms/
│
├── db.php              # Database connection
├── index.php           # Login page
├── dashboard.php        # Admin dashboard
├── books.php            # Manage books
├── members.php          # Manage members
├── staff.php            # Manage staff
├── issue_book.php       # Issue books
├── return_book.php      # Return books & calculate fine
└── logout.php           # Logout
```

---

## Limitations

- Only admin login is available (no member login)
- Fine is fixed at Rs. 5 per day for late returns
- Designed to run on localhost only

---

## Team Project

This project was developed as a team project by students of MES College of Engineering, Kuttippuram, as part of the DBMS course.

---

## Disclaimer

This project was built for academic purposes only, as part of a college DBMS coursework/mini-project. It is not intended for production or commercial use.
