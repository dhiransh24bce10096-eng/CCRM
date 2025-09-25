# 📚 Campus Course & Records Manager (CCRM)

A **Java-based console application** to manage students, courses, enrollments, grading, and file operations.  
This project demonstrates **Object-Oriented Programming (OOP) concepts**, design patterns, file I/O, and exception handling in a practical way.

---

## ✨ Features

- **Student Management**
  - Add, list, and manage students with different statuses (Active, Inactive, Deceased).
  - Built using the **Builder Pattern**.
  
- **Course Management**
  - Add, list, and manage courses with instructors, credits, semester, and department.
  - Built using the **Builder Pattern**.
  
- **Enrollment & Grading**
  - Enroll students in courses (with credit limit validation).
  - Record marks and compute **grades & GPA**.
  - Demonstrates **polymorphism** and `toString()` overrides.
  
- **File Operations**
  - Export students and courses to `.csv` files.
  - Create backups with timestamps.
  - Calculate backup directory size recursively.

- **Reports**
  - List students by active status.
  - Search courses by instructor using **lambda expressions** and **stream pipelines**.

- **Design Patterns & Concepts Used**
  - Singleton (AppConfig)
  - Builder (Student, Course)
  - Enums with constructors
  - Exception handling with custom exceptions
  - Streams & Lambdas
  - Polymorphism and abstraction

---

## 🏗️ Project Structure

