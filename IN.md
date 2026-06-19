# IN Operator

## What is IN?

IN is used to check multiple values in a single condition.

## Example

SELECT *
FROM Customers
WHERE City IN ('Bangalore', 'Mysore', 'Chennai');

## Result

Shows customers from:
- Bangalore
- Mysore
- Chennai

## Why Use IN?

Instead of writing:

SELECT *
FROM Customers
WHERE City='Bangalore'
OR City='Mysore'
OR City='Chennai';

We can write:

SELECT *
FROM Customers
WHERE City IN ('Bangalore', 'Mysore', 'Chennai');

## Interview Question

Q: What is the IN operator used for?

A: IN is used to match multiple values in a WHERE condition.

## Memory Trick

IN = Is the value in this list?
