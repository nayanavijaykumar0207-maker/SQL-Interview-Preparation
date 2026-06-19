# Subqueries

## What is a Subquery?

A subquery is a query inside another query.

## Why Use Subqueries?

Subqueries help us use the result of one query inside another query.

## Example

SELECT Name
FROM Employees
WHERE Salary > (
    SELECT AVG(Salary)
    FROM Employees
);

## What Happens?

1. First, SQL calculates the average salary.
2. Then, it shows employees whose salary is greater than the average.

## Interview Question

Q: What is a subquery?

A: A subquery is a query written inside another query.

## Memory Trick

Subquery = Query inside a Query
