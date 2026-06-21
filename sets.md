# Sets in Python

## What is a Set?

A Set is a collection of unique and unordered items in Python.

Sets are used to store multiple values in a single variable. Unlike lists and tuples, sets do not allow duplicate values.

## Creating a Set

```python
fruits = {"Apple", "Banana", "Mango"}
```

## Characteristics of Sets

* Unordered
* Mutable (can be changed)
* No duplicate values
* Items cannot be accessed using index

## Example

```python
numbers = {10, 20, 30, 40}

print(numbers)
```

Output:

```text
{10, 20, 30, 40}
```

## Adding Elements

Use the `add()` method to add a new element.

```python
numbers.add(50)

print(numbers)
```

## Removing Elements

Use the `remove()` method to remove an element.

```python
numbers.remove(20)

print(numbers)
```

## Set Operations

### Union

Combines two sets.

```python
A = {1, 2, 3}
B = {3, 4, 5}

print(A.union(B))
```

### Intersection

Returns common elements.

```python
print(A.intersection(B))
```

### Difference

Returns elements present in first set but not in second.

```python
print(A.difference(B))
```

## Advantages of Sets

* Fast searching
* Removes duplicates automatically
* Useful in data analysis
* Useful in database and web applications

## Summary

Sets are useful when unique values are required and duplicate values should be avoided. They provide powerful mathematical operations such as union, intersection, and difference.
