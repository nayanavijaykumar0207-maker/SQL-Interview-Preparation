# JOINS

## What is a JOIN?

A JOIN is used to combine data from two or more tables using a common column.

## Why Use JOIN?

Data is often stored in multiple tables.

JOIN helps us connect them and get meaningful information.

## Example Tables

Customers

| CustomerID | Name |
|------------|------|
| 1 | Nayana |
| 2 | Rahul |

Orders

| OrderID | CustomerID | Product |
|----------|------------|---------|
| 101 | 1 | Laptop |
| 102 | 2 | Mobile |

## INNER JOIN

Returns only matching records from both tables.

Example

SELECT Customers.Name, Orders.Product
FROM Customers
INNER JOIN Orders
ON Customers.CustomerID = Orders.CustomerID;

## Result

| Name | Product |
|------|---------|
| Nayana | Laptop |
| Rahul | Mobile |

## Types of JOINS

1. INNER JOIN
   - Only matching records

2. LEFT JOIN
   - All records from left table
   - Matching records from right table

3. RIGHT JOIN
   - All records from right table
   - Matching records from left table

## Interview Question

Q: What is a JOIN?

A: A JOIN combines data from multiple tables using a common column.

## Memory Trick

JOIN = Connect Tables
