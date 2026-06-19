# DISTINCT

## What is DISTINCT?

DISTINCT is used to remove duplicate values and show only unique values.

## Example Table

| Name | City |
|-------|--------|
| Nayana | Bangalore |
| Rahul | Mysore |
| Priya | Bangalore |

## Query

SELECT DISTINCT City
FROM Customers;

## Output

Bangalore
Mysore

## What happened?

Even though Bangalore appeared twice, DISTINCT showed it only once.

## Why Use DISTINCT?

- Find unique cities
- Find unique products
- Find unique departments

## Interview Question

Q: What is DISTINCT used for?

A: DISTINCT is used to remove duplicate values from the result.

## Memory Trick

DISTINCT = Different values only
