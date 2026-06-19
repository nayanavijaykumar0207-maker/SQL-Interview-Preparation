# Constraints

## What are Constraints?

Constraints are rules applied to table columns to ensure data accuracy and integrity.

## Common Constraints

### NOT NULL
A column cannot have empty values.

Example:

CREATE TABLE Employees (
    Name VARCHAR(50) NOT NULL
);

### UNIQUE
No duplicate values allowed.

Example:

Email VARCHAR(100) UNIQUE

### PRIMARY KEY
Uniquely identifies each row.

Example:

EmployeeID INT PRIMARY KEY

### FOREIGN KEY
Links one table to another.

Example:

FOREIGN KEY (DepartmentID)
REFERENCES Departments(DepartmentID)

## Interview Question

Q: What are constraints?

A: Constraints are rules that ensure valid and accurate data in a table.

## Memory Trick

Constraints = Rules for Data
