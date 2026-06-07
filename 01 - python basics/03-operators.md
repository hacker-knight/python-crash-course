# Operators in Python

## Introduction

Operators are special symbols used to perform operations on variables and values.

Examples:
- Addition
- Subtraction
- Comparison
- Logical decisions
- Bit-level operations

In this tutorial, you will learn:

- Arithmetic operators
- Assignment operators
- Comparison operators
- Logical operators
- Membership operators
- Identity operators
- Bitwise operators
- Operator precedence
- Real-world examples

---

# What is an Operator?

An operator tells Python to perform a specific operation.

Example:

```python
a = 10
b = 5

print(a + b)
```

Output:

```text
15
```

Here, `+` is an operator.

---

# Types of Operators in Python

| Category | Purpose |
|----------|---------|
| Arithmetic | Mathematical calculations |
| Assignment | Assign values |
| Comparison | Compare values |
| Logical | Combine conditions |
| Membership | Check existence |
| Identity | Compare objects |
| Bitwise | Binary operations |

---

# Arithmetic Operators

Arithmetic operators perform mathematical calculations.

| Operator | Meaning | Example |
|----------|---------|---------|
| + | Addition | 10 + 5 |
| - | Subtraction | 10 - 5 |
| * | Multiplication | 10 * 5 |
| / | Division | 10 / 5 |
| // | Floor Division | 10 // 3 |
| % | Modulus | 10 % 3 |
| ** | Exponent | 2 ** 3 |

---

## Addition

```python
print(10 + 5)
```

Output:

```text
15
```

---

## Subtraction

```python
print(10 - 5)
```

Output:

```text
5
```

---

## Multiplication

```python
print(10 * 5)
```

Output:

```text
50
```

---

## Division

```python
print(10 / 5)
```

Output:

```text
2.0
```

---

## Floor Division

```python
print(10 // 3)
```

Output:

```text
3
```

---

## Modulus

Returns the remainder.

```python
print(10 % 3)
```

Output:

```text
1
```

---

## Exponent

```python
print(2 ** 3)
```

Output:

```text
8
```

---

# Assignment Operators

Used to assign values.

| Operator | Example |
|----------|---------|
| = | x = 10 |
| += | x += 5 |
| -= | x -= 5 |
| *= | x *= 5 |
| /= | x /= 5 |
| %= | x %= 5 |
| **= | x **= 2 |

---

## Example

```python
x = 10

x += 5

print(x)
```

Output:

```text
15
```

---

# Comparison Operators

Comparison operators compare values and return True or False.

| Operator | Meaning |
|----------|---------|
| == | Equal |
| != | Not Equal |
| > | Greater Than |
| < | Less Than |
| >= | Greater Than or Equal |
| <= | Less Than or Equal |

---

## Examples

```python
print(10 == 10)
print(10 != 5)
print(10 > 5)
```

Output:

```text
True
True
True
```

---

# Logical Operators

Logical operators combine conditions.

| Operator | Meaning |
|----------|---------|
| and | Both conditions must be True |
| or | At least one True |
| not | Reverse result |

---

## AND

```python
print(True and True)
```

Output:

```text
True
```

---

## OR

```python
print(True or False)
```

Output:

```text
True
```

---

## NOT

```python
print(not True)
```

Output:

```text
False
```

---

# Membership Operators

Used to check whether a value exists in a sequence.

| Operator | Meaning |
|----------|---------|
| in | Exists |
| not in | Does not exist |

---

## Example

```python
languages = ["Python", "SQL", "Java"]

print("Python" in languages)
```

Output:

```text
True
```

---

# Identity Operators

Used to compare object identity.

| Operator | Meaning |
|----------|---------|
| is | Same object |
| is not | Different object |

---

## Example

```python
a = [1, 2]
b = a

print(a is b)
```

Output:

```text
True
```

---

# Bitwise Operators

Operate on binary numbers.

| Operator | Meaning |
|----------|---------|
| & | AND |
| \| | OR |
| ^ | XOR |
| ~ | NOT |
| << | Left Shift |
| >> | Right Shift |

---

## Example

```python
print(5 & 3)
```

Output:

```text
1
```

---

# Operator Precedence

Python follows precedence rules.

Example:

```python
result = 10 + 5 * 2
print(result)
```

Output:

```text
20
```

Multiplication happens before addition.

---

## Using Parentheses

```python
result = (10 + 5) * 2
print(result)
```

Output:

```text
30
```

---

# Real-World Example

## Salary Calculation

```python
salary = 50000
bonus = 5000

total_salary = salary + bonus

print(total_salary)
```

Output:

```text
55000
```

---

# Common Beginner Mistakes

## Using = Instead of ==

Incorrect:

```python
if age = 18:
    print("Adult")
```

Correct:

```python
if age == 18:
    print("Adult")
```

---

## Division Confusion

```python
print(10 / 3)
print(10 // 3)
```

Outputs:

```text
3.3333333333
3
```

---

# Mini Project

## Simple Calculator

```python
num1 = int(input("Enter first number: "))
num2 = int(input("Enter second number: "))

print("Addition:", num1 + num2)
print("Subtraction:", num1 - num2)
print("Multiplication:", num1 * num2)
print("Division:", num1 / num2)
```

---

# Best Practices

- Use parentheses when expressions become complex
- Use meaningful variable names
- Avoid unnecessary calculations
- Test comparison conditions carefully

---

# Summary

In this tutorial, you learned:

- Arithmetic operators
- Assignment operators
- Comparison operators
- Logical operators
- Membership operators
- Identity operators
- Bitwise operators
- Operator precedence

Operators are essential building blocks for every Python program.

---

# Key Takeaways

- Operators perform actions on values
- Arithmetic operators handle calculations
- Comparison operators return Boolean values
- Logical operators combine conditions
- Membership operators search collections
- Parentheses improve readability

---

# Practice Questions

1. What is an operator?
2. What is the difference between `/` and `//`?
3. What does `%` do?
4. What is the purpose of `==`?
5. What is the difference between `and` and `or`?
6. What are membership operators?

---

# Exercises

## Exercise 1

Create a calculator that performs:
- Addition
- Subtraction
- Multiplication
- Division

---

## Exercise 2

Check whether a number is even using `%`.

---

## Exercise 3

Create a program that compares two numbers and prints the larger one.

---

## Exercise 4

Check whether a subject exists in a list using `in`.

---

# Next Topic

➡️ Type Casting in Python
