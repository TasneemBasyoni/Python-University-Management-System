# 🎓 University Management System

A console-based **University Management System** developed in **Python** using **Object-Oriented Programming (OOP)** principles and **JSON** file storage.

This project provides a complete system for managing university operations, including students, teachers, courses, and departments through a simple command-line interface.

---

## 📌 Features

### 👨‍💼 Admin
- Manage Students
  - Add Student
  - View All Students
  - Search Student
  - Update Student Information
  - Delete Student

- Manage Teachers
  - Add Teacher
  - View All Teachers
  - Search Teacher
  - Update Teacher Information
  - Delete Teacher

- Manage Courses
  - Add Course
  - View All Courses
  - Search Course
  - Update Course
  - Delete Course

- Manage Departments
  - Add Department
  - View All Departments
  - Search Department
  - Update Department
  - Delete Department

---

### 👨‍🏫 Teacher Portal

Teachers can:

- View Assigned Courses
- View Enrolled Students
- Enter Student Grades
- Update Grades

---

### 👨‍🎓 Student Portal

Students can:

- View Personal Information
- View Registered Courses
- View Grades

---

## 🗂 Project Structure

```
University-Management-System/
│
├── main.py
├── login.py
├── students.py
├── teachers.py
├── courses.py
├── departments.py
├── file_manager.py
├── utils.py
├── menus.py
│
├── students.json
├── teachers.json
├── courses.json
└── departments.json
```

---

## 💾 Data Storage

The system stores all data using **JSON** files.

- students.json
- teachers.json
- courses.json
- departments.json

No external database is required.

---

## 🛠 Technologies Used

- Python 3
- Object-Oriented Programming (OOP)
- JSON File Handling
- Modular Programming

---

## 🔐 Login System

The system supports multiple user roles:

- Admin
- Teacher
- Student

Each user can access the features assigned to their role.

---

## ▶️ How to Run

1. Clone the repository

```bash
git clone https://github.com/your-username/Python-University-Management-System.git
```

2. Open the project folder

```bash
cd Python-University-Management-System
```

3. Run the application

```bash
python main.py
```

---

## 📖 Project Workflow

1. Login to the system.
2. Add departments.
3. Add teachers.
4. Add students.
5. Create courses.
6. Assign courses.
7. Manage student information.
8. View reports.

---

## 🚀 Future Improvements

- GPA Calculation
- Attendance System
- Course Registration
- Semester Management
- Search & Filter
- SQLite/MySQL Database
- GUI using Tkinter
- Web Version using Flask or Django

---

## 👨‍💻 Author

Developed as a Python Object-Oriented Programming (OOP) project for educational purposes.

---

## 📄 License

This project is intended for educational purposes only.
