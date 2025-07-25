# Student Management System (Java + Oracle DB)

This is a basic Java console-based application for managing student records. It uses Oracle Database and JDBC for performing CRUD operations.

## Features

- Add new student
- View all students
- Search student by roll number
- Update student details (name, college name)
- Delete student record

## Tech Stack

- Java (JDK 17+ recommended)
- Oracle Database (XE or standard)
- JDBC
- SQL*Plus / SQL Developer

## How to Run

1. Ensure Oracle Database is running and the `student` table exists
2. Configure DB credentials in `DBConnection.java`
3. Compile the code:
   ```bash
   javac main/Client.java
