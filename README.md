# 🎓 Student Records Management System

## 📌 Description
The **Student Records Management System** is a MySQL-based database designed to efficiently manage student enrollments, courses, instructors, attendance, grades, and payments. This project ensures **data integrity, proper relationships**, and optimized **querying** through a well-structured **normalization approach**.

## 🚀 Features
- **Students** table stores student details.
- **Courses** table maintains course records.
- **Enrollments** table manages student registrations (Many-to-Many Relationship).
- **Instructors** table holds faculty information.
- **CourseAssignments** table tracks instructors teaching multiple courses.
- **Attendance** table logs student attendance.
- **Grades** table records students' grades per course.
- **Payments** table tracks student tuition payments.

## 🛠️ How to Setup & Run
### **1️⃣ Importing SQL**
1. Install **MySQL** on your system.
2. Open **MySQL Workbench** or **Command Line**.
3. Create a new database:
   ```sql
   CREATE DATABASE StudentRecords;