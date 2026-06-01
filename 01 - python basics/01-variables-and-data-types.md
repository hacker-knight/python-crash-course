# Variables and Data Types in Python

## Introduction

Variables are containers used to store data in memory. Data types define what kind of data is stored.

In this tutorial you will learn:
- Variables
- Assignment
- Naming rules
- Data types
- type() function
- Type conversion
- Best practices

---

# What is a Variable?

A variable is a named location that stores data.

```python
name = 'Doe'
age = 25
```

---

# Creating Variables

```python
name = 'Doe'
city = 'Mumbai'
age = 25
```

Python creates variables automatically when values are assigned.

---

# Variable Naming Rules

## Valid

```python
student_name = 'John'
_marks = 95
student1 = 'Doe'
```

## Invalid

```python
1student = 'Doe'
first name = 'Doe'
```

Rules:
- Must start with a letter or underscore
- Cannot contain spaces
- Cannot use Python keywords

---

# Data Types

| Type | Example |
|------|---------|
| str | 'Python' |
| int | 100 |
| float | 10.5 |
| bool | True |
| list | [1,2,3] |
| tuple | (1,2,3) |
| set | {1,2,3} |
| dict | {'name':'John'} |

---

# String

```python
name = 'John'
```

Stores text data.

---

# Integer

```python
age = 25
```

Stores whole numbers.

---

# Float

```python
price = 99.99
```

Stores decimal values.

---

# Boolean

```python
is_active = True
```

Stores True or False.

---

# List

```python
skills = ['Python', 'SQL', 'Power BI']
```

Stores multiple values.

---

# Dictionary

```python
student = {
    'name': 'John',
    'age': 25
}
```

Stores key-value pairs.

---

# Checking Data Types

```python
name = 'John'
print(type(name))
```

Output:

```text
<class 'str'>
```

---

# Dynamic Typing

Python automatically determines data types.

```python
name = 'John'
age = 25
```

---

# Type Conversion

## String to Integer

```python
age = '25'
age = int(age)
```

## Integer to String

```python
age = 25
age = str(age)
```

## Integer to Float

```python
number = 100
number = float(number)
```

---

# Multiple Assignment

```python
name, age, city = 'John', 25, 'Mumbai'
```

---

# Common Mistakes

## Wrong Variable Name

```python
# Invalid
2name = 'John'
```

## Using Quotes Around Numbers

```python
age = '25'
```

This creates a string, not an integer.

---

# Mini Project

```python
student_name = 'John'
student_age = 25
student_marks = 92.5

print(student_name)
print(student_age)
print(student_marks)
```

---

# Summary

You learned:
- Variables
- Data types
- Naming rules
- type()
- Type conversion

---

# Practice Questions

1. What is a variable?
2. What is a data type?
3. What does type() do?
4. What is dynamic typing?
5. What is the difference between int and float?

---

# Exercises

1. Create variables for your name, age and city.
2. Print their values.
3. Check their data types.
4. Convert a string number into an integer.

---

# Next Topic

➡️ Input and Output in Python
