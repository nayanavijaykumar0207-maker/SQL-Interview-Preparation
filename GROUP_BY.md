# GROUP BY

## What is GROUP BY?

GROUP BY is used to group rows that have the same value.

It is usually used with aggregate functions like:
- COUNT()
- SUM()
- AVG()
- MIN()
- MAX()

## Example Table

| City      | Salary |
|-----------|---------|
| Bangalore | 20000 |
| Bangalore | 30000 |
| Mysore    | 25000 |

## Query

SELECT City, SUM(Salary)
FROM Employees
GROUP BY City;

## Result

| City      | Total Salary |
|-----------|-------------|
| Bangalore | 50000 |
| Mysore    | 25000 |

## Why Use GROUP BY?

- Group sales by region
- Group employees by department
- Group students by class

## Interview Question

Q: What is GROUP BY used for?

A: GROUP BY is used to group rows with the same value and perform calculations on each group.

## Memory Trick

GROUP BY = Make Teams
