# First Python Program

## Introduction

Now that Python is installed and configured, it is time to write your first Python program.

In this tutorial, you will learn:

- How to create a Python file
- How to write Python code
- How to run a Python program
- How the `print()` function works
- Basic syntax rules
- Common beginner mistakes

By the end of this tutorial, you will be able to create and run simple Python programs confidently.

---

# What is a Python Program?

A Python program is a set of instructions written in the Python programming language.

These instructions tell the computer what to do.

Example:

```python
print("Hello, World!")
```

This program tells Python to display text on the screen.

---

# Your First Python Program

Traditionally, the first program written in any programming language is:

```python
print("Hello, World!")
```

---

# Understanding the Program

Let's break it down:

```python
print("Hello, World!")
```

| Part | Meaning |
|---|---|
| print | A built-in Python function |
| () | Parentheses used to pass information |
| "Hello, World!" | Text to display |

---

# What is `print()`?

`print()` is a built-in Python function used to display output.

Example:

```python
print("Welcome to Python")
```

Output:

```text
Welcome to Python
```

---

# Creating Your First Python File

## Step 1 — Open VS Code

Open Visual Studio Code.

---

## Step 2 — Create a Folder

Create a folder named:

```text
python-practice
```

---

## Step 3 — Create Python File

Create a new file:

```text
hello.py
```

Python files always use the `.py` extension.

---

## Step 4 — Write Your Program

```python
print("Hello, World!")
```

---

## Step 5 — Save the File

Press:

```text
Ctrl + S
```

---

# Running the Python Program

## Method 1 — Using VS Code

Click the Run button:

```text
▶ Run
```

---

## Method 2 — Using Terminal

Open terminal inside VS Code.

Run:

```bash
python hello.py
```

---

# Program Output

Output:

```text
Hello, World!
```

---

# How Python Executes Code

Python executes code line by line.

Example:

```python
print("Line 1")
print("Line 2")
print("Line 3")
```

Output:

```text
Line 1
Line 2
Line 3
```

---

# Printing Different Types of Data

## Printing Text

```python
print("Python")
```

---

## Printing Numbers

```python
print(100)
```

---

## Printing Decimal Numbers

```python
print(10.5)
```

---

## Printing Boolean Values

```python
print(True)
print(False)
```

---

# Multiple Print Statements

Example:

```python
print("My Name is John")
print("I am learning Python")
print("Python is fun")
```

Output:

```text
My Name is John
I am learning Python
Python is fun
```

---

# Using Quotes in Python

Python supports:
- Single quotes
- Double quotes

Example:

```python
print('Hello')
print("Python")
```

Both are valid.

---

# Printing Quotes Inside Text

Example:

```python
print('I am learning "Python"')
```

Output:

```text
I am learning "Python"
```

---

# Escape Characters

Escape characters are special characters used inside strings.

Example:

```python
print("Hello\nWorld")
```

Output:

```text
Hello
World
```

---

# Common Escape Characters

| Escape Character | Meaning |
|---|---|
| \n | New line |
| \t | Tab |
| \\ | Backslash |
| \" | Double quote |

---

# Comments in Python

Comments are notes written for humans.

Python ignores comments during execution.

Example:

```python
# This is a comment

print("Hello")
```

---

# Why Use Comments?

Comments help:
- Explain code
- Improve readability
- Make debugging easier

---

# Single-Line Comments

```python
# This prints a message
print("Python")
```

---

# Multi-Line Comments

Python does not have official multi-line comments.

But triple quotes are often used:

```python
'''
This is
a multi-line comment
'''
```

---

# Basic Syntax Rules

## Rule 1 — Case Sensitivity

Python is case-sensitive.

Example:

```python
name = "Python"
Name = "Programming"
```

These are different variables.

---

## Rule 2 — Proper Indentation

Indentation is important in Python.

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

## Rule 3 — Use Proper Quotes

Correct:

```python
print("Hello")
```

Incorrect:

```python
print(Hello)
```

---

# Common Beginner Mistakes

## Missing Quotes

Incorrect:

```python
print(Hello)
```

Correct:

```python
print("Hello")
```

---

## Missing Parentheses

Incorrect:

```python
print "Hello"
```

Correct:

```python
print("Hello")
```

---

## Wrong Indentation

Incorrect indentation causes errors.

Always maintain proper spacing.

---

# Writing Multiple Outputs

Example:

```python
print("Name: John")
print("Age: 25")
print("Language: Python")
```

---

# Real-World Example

```python
print("Welcome to ABC Bank")
print("Please Insert Your Card")
```

This simulates ATM messages.

---

# Understanding Errors

Errors are called exceptions in Python.

Example:

```python
print("Hello)
```

Output:

```text
SyntaxError
```

---

# Reading Error Messages

Python error messages help identify:
- What went wrong
- Where the error occurred

Always read errors carefully.

---

# Practice Examples

## Example 1

```python
print("Python is easy")
```

---

## Example 2

```python
print(50)
print(20.5)
```

---

## Example 3

```python
print(True)
```


---

# Practice Exercises

## Exercise 1

Write a program to print:
- Your name
- Your city
- Your favorite subject

---

## Exercise 2

Write a program that prints:

```text
Welcome
to
Python
```

Hint:
Use `\n`

---

## Exercise 3

Write a program using comments.

---

# Best Practices

- Use meaningful file names
- Write clean code
- Add comments where needed
- Save files regularly
- Read error messages carefully

---

# Summary

In this tutorial, you learned:

- How to create Python files
- How to write Python code
- How to use `print()`
- How to run Python programs
- Python syntax basics
- Common beginner mistakes

You have now written your first Python program successfully.

---

# Key Takeaways

- Python programs are written in `.py` files
- `print()` displays output
- Python executes code line by line
- Indentation is important
- Python is case-sensitive
- Comments improve readability

---

# Practice Questions

1. What is the purpose of `print()`?
2. What is the extension of Python files?
3. Why are comments used?
4. What is indentation?
5. Is Python case-sensitive?
6. What happens if quotes are missing?

---

# Next Topic

➡️ Python vs Other Programming Languages
