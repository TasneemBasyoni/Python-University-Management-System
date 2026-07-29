# 🎓 Python University Management System

A **console-based University Management System** developed in **Python** using **Object-Oriented Programming (OOP)** principles and **JSON** file storage.

The system provides an efficient way to manage university operations, including students, teachers, courses, and departments through a user-friendly command-line interface.

---

# 📌 Features

## 👨‍💼 Admin

### Student Management
- Add Student
- View All Students
- Search Student
- Update Student Information
- Delete Student

### Teacher Management
- Add Teacher
- View All Teachers
- Search Teacher
- Update Teacher Information
- Delete Teacher

### Course Management
- Add Course
- View All Courses
- Search Course
- Update Course Information
- Delete Course

### Department Management
- Add Department
- View All Departments
- Search Department
- Update Department Information
- Delete Department

---

## 👨‍🏫 Teacher Portal

Teachers can:

- View Assigned Courses
- View Enrolled Students
- Enter Student Grades
- Update Grades

---

## 👨‍🎓 Student Portal

Students can:

- View Personal Information
- View Registered Courses
- View Grades

---

# 🗂 Project Structure

```
Python-University-Management-System/
│
├── main.py
├── login.py
├── menus.py
├── students.py
├── teachers.py
├── courses.py
├── departments.py
├── file_manager.py
├── utils.py
│
├── students.json
├── teachers.json
├── courses.json
└── departments.json
```

---

# 💾 Data Storage

The project stores all information using **JSON** files.

- students.json
- teachers.json
- courses.json
- departments.json

No external database is required.

---

# 🛠 Technologies Used

- Python 3
- Object-Oriented Programming (OOP)
- JSON File Handling
- Modular Programming

---

# 🔐 User Roles

The system supports three user roles:

- 👨‍💼 Admin
- 👨‍🏫 Teacher
- 👨‍🎓 Student

Each user has access to features based on their role.

---

# ▶️ How to Run

### Clone the repository

```bash
git clone https://github.com/your-username/Python-University-Management-System.git
```

### Navigate to the project

```bash
cd Python-University-Management-System
```

### Run the application

```bash
python main.py
```

---

# 📖 Example Workflow

1. Login to the system.
2. Create departments.
3. Add teachers.
4. Add students.
5. Create courses.
6. Assign teachers and students.
7. Manage university records.
8. View reports.

---

# 🚀 Future Improvements

- GPA Calculation
- Attendance Management
- Course Registration
- Semester Management
- Advanced Search & Filtering
- SQLite/MySQL Database Integration
- Graphical User Interface (Tkinter or PyQt)
- Web Version using Flask or Django

---

# 👨‍💻 Author

Developed as a Python Object-Oriented Programming (OOP) project for educational purposes.

---

# 📄 License

This project is intended for educational purposes only.
