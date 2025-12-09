# 🎓 Student Record Management System (SRMS)

A desktop-based Student Record Management System built using Python, Tkinter, and SQLite.  
This application provides role-based access for Admin and Students to efficiently manage academic records, attendance, and support tickets through a clean and user-friendly graphical interface.

---

## 📌 Project Overview
The Student Record Management System (SRMS) is designed to streamline the management of student information in educational institutions.  
The system enables administrators to manage student records, marks, attendance, and resolve student-raised tickets, while students can view their academic details and raise support tickets.

This project was developed as an academic mini-project to demonstrate Python GUI programming, database integration, and modular application design.

---

## ✨ Key Features

### 🔐 Role-Based Authentication
- Admin and Student login using a single portal  
- Secure role-based access control  

### 👨‍💼 Admin Features
- Add, update, delete student records  
- Automatically generate student login credentials  
- Enter and manage marks  
- Mark and view attendance  
- View, track, and resolve student tickets  

### 👨‍🎓 Student Features
- Login using roll number and default password  
- View own marks and academic results  
- View attendance percentage and history  
- Raise and track support tickets  

### 🎫 Ticket Support System
- Students can raise issues or requests  
- Admin can change ticket status (Open / In Progress / Closed)  

### 🎨 User Interface
- Clean, modern Tkinter GUI  
- Dashboard-based navigation  
- Consistent color theme and responsive layout  

---

## 📂 Program Structure

SRMS/
│
├── main.py                         # Application entry point
├── requirements.txt                # Dependencies (optional)
├── README.md                       # Project documentation
├── .gitignore                      # Git ignored files
│
├── database/                       # Database configuration
│   └── db_config.py                # SQLite setup & table creation
│
├── gui/                            # GUI modules (Tkinter)
│   ├── login.py                    # Admin / Student login screen
│   ├── dashboard.py                # Admin dashboard
│   ├── student_dashboard.py        # Student dashboard
│   │
│   ├── student_form.py             # Add / update student details
│   ├── view_students.py            # View & search students
│   │
│   ├── marks_form.py               # Enter marks (Admin)
│   ├── view_results.py             # View results (Admin)
│   │
│   ├── attendance_form.py          # Mark attendance (Admin)
│   ├── view_attendance.py          # View attendance (Admin)
│   │
│   ├── student_view_marks.py       # Student: view own marks
│   ├── student_view_attendance.py  # Student: view own attendance
│   │
│   ├── ticket_form.py              # Student: raise ticket
│   ├── view_tickets_student.py     # Student: view own tickets
│   └── view_tickets_admin.py       # Admin: manage tickets
│
├── models/                         # Business logic & DB operations
│   ├── student_model.py            # Student CRUD + auto login creation
│   ├── marks_model.py              # Marks logic
│   ├── attendance_model.py         # Attendance logic
│   ├── user_model.py               # Login authentication
│   └── ticket_model.py             # Ticket system logic
│
├── utils/                          # Utilities & helpers
│   ├── constants.py                # App theme (colors, fonts)
│   ├── helpers.py                  # Message boxes & dialogs
│   └── validators.py               # Input validation
│


---

## 🛠️ Technologies Used
- **Python 3**  
- **Tkinter** – Graphical User Interface  
- **SQLite** – Database management  
- **VS Code** – Development environment  

---

## 🔑 Default Login Credentials

### Admin  
- **Username:** admin  
- **Password:** admin123  

### Student  
- **Username:** Roll Number  
- **Password:** student123  

> Student credentials are automatically created when the admin adds a student.

---

## 🎯 Project Objectives
- To develop a real-world GUI application using Python  
- To implement CRUD operations with SQLite  
- To understand role-based access control  
- To provide an intuitive student–admin interaction system  
- To follow modular and maintainable coding practices  

---

## 🚀 Future Enhancements
- Password reset and change functionality  
- Role-based user permissions (Teacher, Staff)  
- Export reports to PDF/Excel  
- Data visualization for attendance and performance  
- Cloud-based database integration  

---

## 📜 License
This project is created for educational purposes and is free to use and modify.

---

⭐ *If you like this project, feel free to star the repository!*
