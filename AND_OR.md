# AND / OR Operators

## What is AND?

AND is used when all conditions must be true.

## Example

SELECT *
FROM Customers
WHERE City = 'Bangalore'
AND Age > 25;

### Result

Shows customers who are:
- From Bangalore
- AND older than 25

## What is OR?

OR is used when any one condition can be true.

## Example

SELECT *
FROM Customers
WHERE City = 'Bangalore'
OR City = 'Mysore';

### Result

Shows customers from:
- Bangalore
- OR Mysore

## Interview Question

Q: Difference between AND and OR?

A:
- AND = All conditions must be true.
- OR = Any one condition can be true.

## Memory Trick

AND = Both
OR = Either
