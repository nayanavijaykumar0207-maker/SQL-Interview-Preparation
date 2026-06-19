# LIKE Operator

## What is LIKE?

LIKE is used to search for a pattern in text.

## Wildcards

% = Any number of characters

_ = One character

## Example 1

SELECT *
FROM Customers
WHERE Name LIKE 'N%';

### Result

Shows names starting with N.

Example:
- Nayana
- Naveen

## Example 2

SELECT *
FROM Customers
WHERE Name LIKE '%a';

### Result

Shows names ending with a.

Example:
- Priya
- Anusha

## Why Use LIKE?

- Search names
- Search cities
- Search products

## Interview Question

Q: What is LIKE used for?

A: LIKE is used to search for a specific pattern in text data.

## Memory Trick

LIKE = Looks Like
