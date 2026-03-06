**Student Management System (Java + JDBC + MySQL)**

The Student Management System is a console-based Java application developed to manage student records using JDBC and MySQL. This project demonstrates how Java applications interact with relational databases to perform CRUD (Create, Read, Update, Delete) operations.

The system allows users to add new students, view existing student records, update student details, and delete records from the database through a menu-driven console interface. It is designed as a beginner-friendly project to understand database connectivity in Java using JDBC.

Features
Add new student records to the database
View all student details stored in the database
Update existing student information (course and age)
Delete student records using student ID
Menu-driven console interface for easy interaction
Secure database queries using PreparedStatement
Error handling using Exception Handling in Java

**Technologies Used**

Java (Core Java)
JDBC (Java Database Connectivity)
MySQL Database
SQL
Scanner Class for User Input
VS Code
Database Structure


The project uses a MySQL database named:

**student_management_system**

Table Name:

student
Student Table Fields
Column	Data Type	Description
id	INT	Unique Student ID (Primary Key)
name	VARCHAR	Student Name
email	VARCHAR	Student Email
course	VARCHAR	Student Course
age	INT	Student Age
SQL Table Creation
CREATE DATABASE student_management_system;

USE student_management_system;

CREATE TABLE student (
    id INT PRIMARY KEY,
    name VARCHAR(50),
    email VARCHAR(100),
    course VARCHAR(50),
    age INT
);

**Project Functionality**
1 Add Student
Allows the user to insert a new student record into the database.

2 View Students
Displays all student records stored in the database using ResultSet.

3 Update Student
Updates the course and age of a student based on their ID.

4 Delete Student
Deletes a student record from the database using their ID.

5 Exit Program
Closes the application and database connection safely.

**JDBC Concepts Used**
This project demonstrates important JDBC concepts, including:
Loading JDBC Driver using Class.forName()
Establishing database connection using DriverManager
Executing SQL queries
Using Statement and PreparedStatement
Fetching data using ResultSet
Performing CRUD operations
Exception handling with SQLException
Learning Outcomes

Through this project, the following concepts were practiced:

Connecting Java applications with MySQL databases
Writing SQL queries inside Java programs
Performing database CRUD operations
Using PreparedStatement to prevent SQL Injection
Building menu-driven console applications

**Future Improvements**

Possible improvements for this project:
Add search functionality for students
Implement a graphical user interface (GUI)
Add login authentication system
Implement pagination for large data sets
Convert into a Spring Boot REST API


**Author**
Ansh Gupta
B.Tech Computer Science Student

This project was developed by Ansh Gupta to practice Java JDBC, MySQL database connectivity, and CRUD operations while building practical backend applications.
