# CASE Statement

## What is CASE?

CASE is used to add conditions in SQL.

It works like IF-ELSE in programming.

## Example

SELECT Name,
CASE
    WHEN Salary > 50000 THEN 'High Salary'
    ELSE 'Low Salary'
END AS Salary_Category
FROM Employees;

## Result

Employees will be categorized as:
- High Salary
- Low Salary

## Why Use CASE?

- Categorize data
- Create labels
- Build reports and dashboards

## Interview Question

Q: What is CASE used for?

A: CASE is used to apply conditions and return different values based on those conditions.

## Memory Trick

CASE = IF-ELSE in SQL
