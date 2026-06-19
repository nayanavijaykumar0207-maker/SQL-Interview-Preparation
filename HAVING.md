# HAVING

## What is HAVING?

HAVING is used to filter groups after GROUP BY.

## Difference Between WHERE and HAVING

WHERE = Filters rows before grouping

HAVING = Filters groups after grouping

## Example

SELECT City, COUNT(*)
FROM Customers
GROUP BY City
HAVING COUNT(*) > 1;

## Result

Only cities with more than 1 customer will be shown.

## Why Use HAVING?

- Find departments with more than 10 employees
- Find cities with more than 100 customers
- Find products with high sales

## Interview Question

Q: What is the difference between WHERE and HAVING?

A:
- WHERE filters rows.
- HAVING filters groups.

## Memory Trick

WHERE = Before Grouping

HAVING = After Grouping
