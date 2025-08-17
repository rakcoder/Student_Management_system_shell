# Student Management System Shell

This is a **Student Management System** implemented in **Bash Shell Scripting**. 
It allows administrators, teachers, and students to manage and interact with courses, students, and semesters. 
The project is designed to simulate a basic student management system with functionalities like creating users, managing courses, enrolling students, and updating marks.

## Table of Contents

- [Features](#features)
- [Project Structure](#project-structure)
- [Usage](#usage)
- [Admin Functionalities](#admin-functionalities)
- [Teacher Functionalities](#teacher-functionalities)
- [Student Functionalities](#student-functionalities)
- [Prerequisites](#prerequisites)
- [How to Run](#how-to-run)
- [File Descriptions](#file-descriptions)
- [Author](#author)

---

## Features

- **Admin Functionalities**:
  - Create and view teachers and students.
  - Create and view semesters.
  - Create and view courses.
  - Modify course teachers.
  - Enroll students into courses.
  - View and search student information.
  - Delete students.

- **Teacher Functionalities**:
  - View enrolled students in their courses.
  - Update or insert marks for students.

- **Student Functionalities**:
  - View their enrolled courses, marks, and grades.

---

## Project Structure
Student_Management_system_shell/ 
── Student_Management_system_shell/course.csv 
── Student_Management_system_shell/courseEnroll.csv 
── Student_Management_system_shell/index.sh 
── Student_Management_system_shell/semester.csv 
── Student_Management_system_shell/student.csv 
── Student_Management_system_shell/teacher.csv


---

## Usage

The system provides three user roles:
1. **Admin**
2. **Teacher**
3. **Student**

Each role has specific functionalities, as described below.

---

## Admin Functionalities

- **Create Teacher**: Add a new teacher to the system.
- **View Teachers**: Display all teachers.
- **Create Student**: Add a new student to the system.
- **View Students**: Display all students with their enrolled courses and marks.
- **Search Students**: Search for a specific student by ID.
- **Create Semester**: Add a new semester.
- **View Semesters**: Display all semesters.
- **Create Course**: Add a new course with a teacher and semester.
- **View Courses**: Display all courses with details like teacher and enrolled students.
- **Modify Course Teacher**: Change the teacher of a course.
- **Enroll Students**: Enroll a student into a course.
- **Delete Student**: Remove a student from the system.

---

## Teacher Functionalities

- **View Enrolled Students**: Display students enrolled in the teacher's courses.
- **Update Marks**: Update attendance, quiz, midterm, and final marks for students.

---

## Student Functionalities

- **View Courses and Grades**: View their enrolled courses, marks, and grades.

---

## Prerequisites

- **Bash Shell**: Ensure you have a Bash shell environment.
- **`banner` Command**: Install the `banner` command if not already available. You can install it using:
  ```bash
  sudo apt-get install sysvbanner

How to Run
  1) Clone or download the project to your local machine.
  2) Navigate to the project directory:
     -> "cd Student_Management_system_shell"
  3) Make the script executable:
     ->  "chmod +x index.sh"
  4) Run the script:
     -> "./index.sh"

---

## File Descriptions

- index.sh: The main script containing the core logic of the project.
- teacher.csv: Stores teacher information (ID, Name).
- student.csv: Stores student information (ID, Name).
- semester.csv: Stores semester information (e.g., Spring-2023).
- course.csv: Stores course information (ID, Name, Semester, Teacher ID).
- courseEnroll.csv: Stores course enrollment information (Course ID, Student ID, Semester, Attendance, Quiz, Midterm, Final).

---

## Author
Aghera Rakshit
LinkedIn : https://www.linkedin.com/in/rakshit-aghera04/

---

## Notes
- Ensure all .csv files are present in the same directory as the script.
- The system uses simple CSV files for data storage. Make sure to back up these files regularly.
- The project is designed for educational purposes and may not be suitable for production use.
