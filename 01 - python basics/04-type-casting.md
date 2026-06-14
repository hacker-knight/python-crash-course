# Type Casting in Python

## Introduction

Type casting is the process of converting one data type into another.

Examples:
- String to Integer
- Integer to Float
- Float to String
- List to Tuple

Type casting is commonly used when working with user input, files, APIs, and data processing.

---

# What is Type Casting?

Type casting means converting a value from one data type to another.

Example:

```python
age = "25"
age = int(age)
```

Now `age` is an integer instead of a string.

---

# Why is Type Casting Important?

Consider:

```python
num1 = "10"
num2 = "20"

print(num1 + num2)
```

Output:

```text
1020
```

Because both values are strings.

Correct version:

```python
print(int(num1) + int(num2))
```

Output:

```text
30
```

---

# Types of Type Casting

Python supports:

1. Implicit Type Casting
2. Explicit Type Casting

---

# Implicit Type Casting

Python automatically converts compatible data types.

Example:

```python
num1 = 10
num2 = 5.5

result = num1 + num2

print(result)
```

Output:

```text
15.5
```

Python converts the integer to a float automatically.

---

# Explicit Type Casting

Explicit type casting is done manually.

Example:

```python
age = "25"

age = int(age)
```

---

# Common Type Conversion Functions

| Function | Converts To |
|----------|-------------|
| int() | Integer |
| float() | Float |
| str() | String |
| bool() | Boolean |
| list() | List |
| tuple() | Tuple |
| set() | Set |

---

# Integer Conversion

## String to Integer

```python
age = "25"

print(int(age))
```

Output:

```text
25
```

---

## Float to Integer

```python
price = 99.99

print(int(price))
```

Output:

```text
99
```

The decimal portion is removed.

---

# Float Conversion

## String to Float

```python
marks = "95.5"

print(float(marks))
```

Output:

```text
95.5
```

---

## Integer to Float

```python
number = 100

print(float(number))
```

Output:

```text
100.0
```

---

# String Conversion

## Integer to String

```python
age = 25

print(str(age))
```

Output:

```text
25
```

---

## Why Use str()?

Useful when displaying messages.

```python
age = 25

print("Age: " + str(age))
```

---

# Boolean Conversion

The bool() function converts values into True or False.

Examples:

```python
print(bool(1))
print(bool(0))
```

Output:

```text
True
False
```

---

# Boolean Conversion Rules

| Value | Result |
|--------|--------|
| 0 | False |
| 1 | True |
| "" | False |
| "Python" | True |
| [] | False |
| [1, 2] | True |

---

# List Conversion

```python
word = "Python"

print(list(word))
```

Output:

```text
['P', 'y', 't', 'h', 'o', 'n']
```

---

# Tuple Conversion

```python
numbers = [1, 2, 3]

print(tuple(numbers))
```

Output:

```text
(1, 2, 3)
```

---

# Set Conversion

```python
numbers = [1, 2, 2, 3]

print(set(numbers))
```

Output:

```text
{1, 2, 3}
```

Duplicates are removed.

---

# Type Casting User Input

Input values are always strings.

Example:

```python
age = input("Enter age: ")

print(type(age))
```

Output:

```text
<class 'str'>
```

---

# Correct Approach

```python
age = int(input("Enter age: "))
```

Now age becomes an integer.

---

# Example: Addition Program

Without conversion:

```python
num1 = input("Enter first number: ")
num2 = input("Enter second number: ")

print(num1 + num2)
```

Output:

```text
1020
```

---

With conversion:

```python
num1 = int(input("Enter first number: "))
num2 = int(input("Enter second number: "))

print(num1 + num2)
```

Output:

```text
30
```

---

# Type Checking

Use type().

```python
value = 100

print(type(value))
```

Output:

```text
<class 'int'>
```

---

# Real-World Example

## Salary Calculator

```python
salary = float(input("Enter salary: "))
bonus = float(input("Enter bonus: "))

print(salary + bonus)
```

---

# Common Conversion Errors

## Invalid Integer Conversion

```python
int("Python")
```

Output:

```text
ValueError
```

---

## Valid Conversion

```python
int("100")
```

Output:

```text
100
```

---

# Common Beginner Mistakes

## Forgetting Conversion

```python
age = input("Enter age: ")
```

Age remains a string.

---

## Converting Invalid Values

```python
int("Hello")
```

This causes an error.

---

# Mini Project

## Age Calculator

```python
birth_year = int(input("Enter birth year: "))

current_year = 2025

age = current_year - birth_year

print(age)
```

---

# Best Practices

- Validate user input
- Convert values only when required
- Use type() for debugging
- Handle conversion errors properly

---

# Summary

In this tutorial, you learned:

- What type casting is
- Implicit conversion
- Explicit conversion
- Common conversion functions
- Type checking

Type casting is an essential skill when working with data and user input.

---

# Key Takeaways

- Type casting converts data types
- Python supports implicit and explicit conversion
- input() always returns strings
- int(), float(), and str() are commonly used
- type() helps verify data types

---

# Practice Questions

1. What is type casting?
2. What is implicit type casting?
3. What is explicit type casting?
4. Why is conversion needed for user input?
5. What does int() do?
6. What does float() do?

---

# Exercises

## Exercise 1

Convert:

```python
"100"
```

into an integer.

---

## Exercise 2

Convert:

```python
100
```

into a string.

---

## Exercise 3

Take two numbers as input and display their sum.

---

## Exercise 4

Create a salary calculator using user input.

---

# Next Topic

➡️ Strings in Python
