# Aggregate Functions

## What are Aggregate Functions?

Aggregate functions perform calculations on multiple rows and return a single result.

## COUNT()

Counts the number of rows.

Example:

SELECT COUNT(*) 
FROM Customers;

## SUM()

Adds values together.

Example:

SELECT SUM(Salary)
FROM Employees;

## AVG()

Finds the average value.

Example:

SELECT AVG(Salary)
FROM Employees;

## MIN()

Finds the smallest value.

Example:

SELECT MIN(Salary)
FROM Employees;

## MAX()

Finds the largest value.

Example:

SELECT MAX(Salary)
FROM Employees;

## Interview Question

Q: Name some aggregate functions in SQL.

A:
- COUNT()
- SUM()
- AVG()
- MIN()
- MAX()

## Memory Trick

CSAMM

C = COUNT
S = SUM
A = AVG
M = MIN
M = MAX
