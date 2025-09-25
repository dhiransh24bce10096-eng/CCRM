# 🎓 Campus Course & Records Manager (CCRM)

This is my Java project for managing **students, courses, enrollments, grades, and backups** — all through a simple console menu.  
I built it mainly to practice **OOP concepts, design patterns, and file handling** in Java.

---

## 🔑 What it can do
- **Students** → add, list, and manage (Active, Inactive, Deceased)  
- **Courses** → create courses with instructors, credits, semester, department  
- **Enrollments** → enroll students, record marks, auto-calculate grade + GPA  
- **File ops** → export students/courses into CSV, create backups with timestamps  
- **Reports** → view active students or search courses by instructor  

---

## 🛠️ Concepts I used
- Singleton (AppConfig)  
- Builder Pattern (Student, Course)  
- Enums with custom fields (Semester, Grade)  
- Polymorphism & Abstraction (`Person`, `Student`, `Instructor`)  
- Exception handling (custom exceptions)  
- Streams, Lambdas & Predicates  
- File I/O and Recursion (backup size utility)  

---

## 📂 Project layout
Everything is inside one main file (`CCRM.java`) but organized into inner classes like config, domain, service, io, util, and exception.  
Later I can split them into separate packages if needed.

---

## ▶️ How to run

1. Compile:
   ```bash
   javac CCRM.java
