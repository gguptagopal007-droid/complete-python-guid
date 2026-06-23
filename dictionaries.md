# Dictionaries in Python

## What is a Dictionary?

A Dictionary is a collection of data stored in key-value pairs.

Dictionaries are used to store related information together.

## Creating a Dictionary

```python
student = {
    "name": "Gopal",
    "age": 25,
    "city": "Gorakhpur"
}
```

## Accessing Values

```python
print(student["name"])
```

Output:

```text
Gopal
```

## Dictionary Characteristics

* Ordered
* Mutable
* No duplicate keys
* Stores data as key-value pairs

## Adding New Data

```python
student["course"] = "Python"
```

## Updating Data

```python
student["age"] = 26
```

## Removing Data

```python
student.pop("city")
```

## Useful Methods

### keys()

Returns all keys.

```python
print(student.keys())
```

### values()

Returns all values.

```python
print(student.values())
```

### items()

Returns key-value pairs.

```python
print(student.items())
```

## Real-Life Uses

* Student Records
* Employee Data
* JSON Data
* APIs
* Database Applications

## Summary

Dictionaries are one of the most powerful data structures in Python and are heavily used in real-world projects.
