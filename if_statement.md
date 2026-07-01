# Nested If Statement in Python

## Definition

A Nested If Statement is an if statement placed inside another if statement.

It is used when a program needs to check multiple conditions in a sequence. The inner if statement is executed only if the outer if condition is True.

## Syntax

```python
if condition1:
    if condition2:
        statement
```

## Example

```python
age = 20
citizen = True

if age >= 18:
    if citizen:
        print("Eligible to Vote")
```

## Advantages

* Helps in checking multiple conditions.
* Useful for complex decision-making.
* Makes logical validation easier.

## Real-Life Example

A student can receive a scholarship only if:

1. The student passes the exam.
2. The student's marks are above 90%.

This requires checking one condition inside another condition.

## Summary

A Nested If Statement is an if statement inside another if statement and is used when multiple conditions depend on each other.
