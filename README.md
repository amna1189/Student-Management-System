# Student Data Management System (SDMS)

A console-based **Student Data Management System (SDMS)** developed in **C++** to simplify the storage, management, and analysis of student records. The system provides secure administrator access, student registration, grade calculation, record sorting, and persistent file storage.

---

## Project Overview

The Student Data Management System is designed to digitize and automate student record management in educational institutions. It enables administrators to manage student information, academic records, grades, and attendance efficiently while reducing manual work and errors.

---

## Features

### Secure Admin Login
- Administrator-only access
- Username and password authentication
- Prevents unauthorized access
- Input validation and error handling

---

### Student Registration
Register students with:

- Student ID
- Name
- Email Address
- Phone Number
- Address
- Additional Metadata (Optional)

The system validates:
- Unique Student IDs
- Email Format
- Duplicate Records

---

###  Academic Record Management

Store marks for multiple subjects including:

- Computer Programming (CP)
- Information & Communication Technology (ICT)
- Discrete Mathematics (DM)
- Physics
- Ethics
- Islamic Studies

The system allows:
- Marks Entry
- Marks Updates
- Academic Record Management

---

### Automatic Grade Calculation

Grades are automatically calculated based on average marks.

| Grade | Criteria |
|---------|---------|
| A | Average ≥ 90 |
| B | 80 ≤ Average < 90 |
| C | 70 ≤ Average < 80 |
| D | 60 ≤ Average < 70 |
| F | Average < 60 |

---

### Student Performance Analysis

The system automatically calculates:

- Total Marks
- Average Marks
- Grades
- Attendance Percentage

---

### Student Record Updates

Administrators can update:

- Personal Information
- Academic Records
- Contact Information
- Attendance Data
- Subject Marks

---

### Student Sorting

Students can be sorted based on:

- Total Marks
- Grades
- Attendance

Sorting functionality helps identify top-performing students quickly.

---

### Student Record Display

Displays complete student information including:

- Student ID
- Name
- Email
- Phone Number
- Subject Marks
- Total Marks
- Average Marks
- Attendance
- Grade

---

### Persistent Data Storage

Student records are saved permanently using file handling.

Features include:

- Save student data to file
- Load data automatically on startup
- Data persistence across program executions
- Automatic backup support

---

## Project Structure

```text
StudentDataManagementSystem/
│
├── main.cpp
├── students.dat
├── backup files
├── README.md
└── documentation/
```

---

## Technologies Used

- C++
- Object-Oriented Programming (OOP)
- Dynamic Arrays
- File Handling
- Structured Programming
- Input Validation
- Command Line Interface (CLI)

---

## Data Structures & Algorithms Used

### Data Structures
- Dynamic Arrays
- Structures (Structs)
- File Storage Records

### Algorithms
- Grade Calculation Algorithm
- Bubble Sort Algorithm
- Record Search Operations
- Data Validation Algorithms

---

## Functional Requirements

- Admin Login
- Student Registration
- Marks Entry
- Grade Calculation
- Student Sorting
- Student Record Display
- Data Storage and Retrieval
- Input Validation
- Error Handling

---

## Non-Functional Requirements

### Performance
- Supports up to 1000 student records efficiently

### Security
- Restricted administrator access
- Secure credential management

### Reliability
- Accurate calculations and record handling
- Robust file operations

### Scalability
- Easy expansion for additional subjects and features

### Portability
- Runs on any system with a standard C++ compiler

### Maintainability
- Modular and structured code design

---

## Objectives

- Digitize student records
- Automate grade calculations
- Improve data accuracy
- Reduce manual workload
- Ensure secure access
- Provide persistent storage
- Create a user-friendly system


---

## Example Workflow

1. Login as Administrator
2. Register New Student
3. Enter Subject Marks
4. Calculate Grades Automatically
5. Sort Students by Performance
6. View Student Records
7. Save Data to File
8. Exit Program

---

## Key Highlights

✔ Secure Admin Authentication

✔ Student Registration System

✔ Automatic Grade Calculation

✔ Attendance Management

✔ Record Sorting and Analysis

✔ Dynamic Memory Allocation

✔ Persistent File Storage

✔ Input Validation

✔ Error Handling

✔ Scalable and Maintainable Design

---

##  Future Enhancements

- Graphical User Interface (GUI)
- Database Integration (MySQL/SQLite)
- Multi-User Access Control
- Advanced Reporting System
- Cloud-Based Storage
- Web Application Version

---

##  License

This project was developed as a university **Computer Programming Course Project** for academic purposes.

---
**Student Data Management System (SDMS)**  
*Making student record management efficient, secure, and automated.*
