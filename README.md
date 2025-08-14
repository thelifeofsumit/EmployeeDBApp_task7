
# Employee Database App (Java JDBC)

# Overview
A simple Java console-based application to manage employees using **JDBC** with MySQL.  
Features:
- Add Employee
- View Employees
- Update Employee
- Delete Employee

# Technologies
- Java
- MySQL
- JDBC

# Database Setup
Run the following SQL commands in MySQL:
```sql
CREATE DATABASE employeedb;

USE employeedb;

CREATE TABLE employees (
    id INT PRIMARY KEY AUTO_INCREMENT,
    name VARCHAR(50),
    department VARCHAR(50),
    salary DOUBLE
);
