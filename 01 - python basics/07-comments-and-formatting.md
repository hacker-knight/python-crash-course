# Comments and Formatting in Python

## Introduction

Comments and formatting help make code readable, maintainable, and professional.

In this tutorial, you will learn:

- Single-line comments
- Multi-line comments
- Docstrings
- Code formatting
- Naming conventions
- PEP 8 guidelines
- Clean code principles

---

# What are Comments?

Comments are notes written for humans.

Python ignores comments during execution.

Example:

```python
# Display welcome message
print("Welcome")
```

---

# Why Use Comments?

Comments help:

- Explain logic
- Improve readability
- Document code
- Assist team members

---

# Single-Line Comments

Single-line comments start with `#`.

```python
# Store user name
name = "John"
```

---

# Inline Comments

```python
age = 25  # User age
```

Use inline comments sparingly.

---

# Multi-Line Comments

Python does not have a dedicated multi-line comment syntax.

Developers often use:

```python
'''
This is a
multi-line comment
'''
```

or

```python
"""
This is a
multi-line comment
"""
```

---

# What are Docstrings?

Docstrings document functions, classes, and modules.

Example:

```python
def greet():
    """Display a welcome message"""
    print("Hello")
```

---

# Accessing Docstrings

```python
def greet():
    """Display a welcome message"""
    print("Hello")

print(greet.__doc__)
```

---

# Good vs Bad Comments

## Bad

```python
# Add two numbers
result = a + b
```

The code already explains itself.

---

## Better

```python
# Calculate final invoice amount after tax deduction
result = invoice_amount - tax
```

---

# Code Formatting

Formatting makes code easier to read.

Benefits:

- Better readability
- Easier debugging
- Improved collaboration

---

# Indentation

Python uses indentation to define blocks.

Correct:

```python
if True:
    print("Hello")
```

Incorrect:

```python
if True:
print("Hello")
```

---

# Recommended Indentation

PEP 8 recommends:

```text
4 spaces
```

---

# Blank Lines

Use blank lines to separate logical sections.

```python
name = "John"
age = 25

print(name)
print(age)
```

---

# Variable Naming

Use meaningful variable names.

Good:

```python
employee_name = "John"
monthly_salary = 50000
```

Bad:

```python
x = "John"
a = 50000
```

---

# Snake Case

Variables and functions should use snake_case.

```python
student_name
calculate_total_salary
employee_id
```

---

# Constants

Constants are usually uppercase.

```python
PI = 3.14159
MAX_USERS = 100
```

---

# Class Names

Classes use PascalCase.

```python
class StudentManagement:
    pass
```

---

# PEP 8

PEP 8 is Python's official style guide.

It recommends:

- 4-space indentation
- Meaningful names
- Consistent formatting
- Readable code

---

# Common PEP 8 Rules

## Spaces Around Operators

Good:

```python
total = price + tax
```

Bad:

```python
total=price+tax
```

---

## Meaningful Names

Good:

```python
student_marks
```

Bad:

```python
x
```

---

# Clean Code Principles

## Keep Functions Small

```python
def calculate_total():
    pass
```

---

## Avoid Repetition

Bad:

```python
print("Welcome")
print("Welcome")
print("Welcome")
```

Better:

```python
for _ in range(3):
    print("Welcome")
```

---

# Real-World Example

Poor:

```python
name="John"
age=25
if age>=18:
 print("Adult")
```

Better:

```python
name = "John"
age = 25

if age >= 18:
    print("Adult")
```

---

# Useful Formatting Tools

| Tool | Purpose |
|--------|---------|
| Black | Auto-format code |
| Ruff | Linting |
| Flake8 | Style checking |
| Pylint | Code quality analysis |

---

# Installing Black

```bash
pip install black
```

Format a file:

```bash
black app.py
```

---

# Common Beginner Mistakes

- Mixing tabs and spaces
- Poor variable names
- Too many comments
- Ignoring formatting standards

---

# Mini Project

## Employee Information Program

```python
"""
Employee Information System
Displays employee details.
"""

employee_name = "John"
employee_department = "Technology"

print(employee_name)
print(employee_department)
```

---

# Best Practices

- Follow PEP 8
- Use meaningful names
- Write docstrings
- Keep code readable
- Use formatting tools

---

# Summary

In this tutorial, you learned:

- Comments
- Docstrings
- Formatting
- Naming conventions
- PEP 8
- Clean code principles

---

# Key Takeaways

- Comments explain code
- Docstrings document code
- PEP 8 improves consistency
- Use snake_case for variables
- Use PascalCase for classes

---

# Practice Questions

1. What is a comment?
2. What is a docstring?
3. What is PEP 8?
4. Why is indentation important?
5. What naming style is used for variables?

---

# Exercises

## Exercise 1

Add comments to a calculator program.

## Exercise 2

Create a function with a docstring.

## Exercise 3

Rewrite poorly formatted code using PEP 8.

---

# Next Topic

➡️ If-Else Statements in Python
