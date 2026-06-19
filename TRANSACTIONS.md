# Transactions

## What is a Transaction?

A transaction is a group of SQL operations treated as one unit of work.

## Why Use Transactions?

To ensure data remains correct and consistent.

## Important Commands

### BEGIN TRANSACTION

Starts a transaction.

Example:

BEGIN TRANSACTION;

### COMMIT

Saves all changes permanently.

Example:

COMMIT;

### ROLLBACK

Cancels changes and returns to the previous state.

Example:

ROLLBACK;

## Example

BEGIN TRANSACTION;

UPDATE Accounts
SET Balance = Balance - 1000
WHERE AccountID = 1;

UPDATE Accounts
SET Balance = Balance + 1000
WHERE AccountID = 2;

COMMIT;

## Interview Question

Q: What is a transaction?

A: A transaction is a set of SQL operations executed as a single unit of work.

## Memory Trick

COMMIT = Save

ROLLBACK = Undo
