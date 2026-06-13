# Strings in Python

## Introduction

Strings are one of the most commonly used data types in Python.

A string is a sequence of characters used to store text data.

Examples:

- Names
- Addresses
- Emails
- Messages
- File paths
- URLs

In this tutorial, you will learn:

- What strings are
- Creating strings
- String indexing
- String slicing
- String methods
- String formatting
- Escape characters
- Common mistakes
- Real-world examples

---

# What is a String?

A string is a collection of characters enclosed in quotes.

Examples:

```python
name = "John"
city = "Mumbai"
language = "Python"
```

---

# Creating Strings

Python supports:

## Double Quotes

```python
name = "Python"
```

## Single Quotes

```python
name = 'Python'
```

Both are valid.

---

# Multi-Line Strings

Use triple quotes.

```python
message = '''
Welcome to Python
Programming
Tutorial
'''
```

---

# Checking String Type

```python
name = "Python"

print(type(name))
```

Output:

```text
<class 'str'>
```

---

# String Length

Use the `len()` function.

```python
language = "Python"

print(len(language))
```

Output:

```text
6
```

---

# String Indexing

Each character has an index position.

```text
P  y  t  h  o  n
0  1  2  3  4  5
```

---

# Accessing Characters

```python
language = "Python"

print(language[0])
```

Output:

```text
P
```

---

## Access Last Character

```python
print(language[-1])
```

Output:

```text
n
```

---

# String Slicing

Slicing extracts part of a string.

Syntax:

```python
string[start:end]
```

---

## Example

```python
language = "Python"

print(language[0:3])
```

Output:

```text
Pyt
```

---

## Beginning to End

```python
print(language[:4])
```

Output:

```text
Pyth
```

---

## End Portion

```python
print(language[2:])
```

Output:

```text
thon
```

---

# Reverse a String

```python
language = "Python"

print(language[::-1])
```

Output:

```text
nohtyP
```

---

# String Concatenation

Concatenation means joining strings.

```python
first_name = "John"
last_name = "Doe"

full_name = first_name + " " + last_name

print(full_name)
```

Output:

```text
John Doe
```

---

# String Repetition

```python
print("Python " * 3)
```

Output:

```text
Python Python Python
```

---

# String Membership

Check if text exists.

```python
language = "Python"

print("Py" in language)
```

Output:

```text
True
```

---

# String Immutability

Strings cannot be modified after creation.

Incorrect:

```python
name = "Python"

name[0] = "J"
```

Output:

```text
TypeError
```

---

# Common String Methods

## upper()

Converts to uppercase.

```python
text = "python"

print(text.upper())
```

Output:

```text
PYTHON
```

---

## lower()

```python
text = "PYTHON"

print(text.lower())
```

Output:

```text
python
```

---

## title()

```python
text = "python programming"

print(text.title())
```

Output:

```text
Python Programming
```

---

## capitalize()

```python
text = "python"

print(text.capitalize())
```

Output:

```text
Python
```

---

## strip()

Removes extra spaces.

```python
text = "  Python  "

print(text.strip())
```

Output:

```text
Python
```

---

## replace()

```python
text = "I like Java"

print(text.replace("Java", "Python"))
```

Output:

```text
I like Python
```

---

## split()

Converts string into a list.

```python
text = "Python SQL PowerBI"

print(text.split())
```

Output:

```text
['Python', 'SQL', 'PowerBI']
```

---

## join()

Joins elements together.

```python
skills = ["Python", "SQL", "PowerBI"]

print(", ".join(skills))
```

Output:

```text
Python, SQL, PowerBI
```

---

# Finding Text

## find()

Returns index position.

```python
text = "Python Programming"

print(text.find("Programming"))
```

Output:

```text
7
```

---

# Counting Occurrences

```python
text = "Python Python Python"

print(text.count("Python"))
```

Output:

```text
3
```

---

# Checking String Content

## isalpha()

```python
print("Python".isalpha())
```

Output:

```text
True
```

---

## isdigit()

```python
print("123".isdigit())
```

Output:

```text
True
```

---

## isalnum()

```python
print("Python123".isalnum())
```

Output:

```text
True
```

---

# Escape Characters

## New Line

```python
print("Python\nSQL")
```

Output:

```text
Python
SQL
```

---

## Tab

```python
print("Python\tSQL")
```

---

## Quote Inside String

```python
print("Python is called \"awesome\"")
```

---

# String Formatting

## Using Commas

```python
name = "John"

print("Welcome", name)
```

---

## Using format()

```python
name = "John"

print("Welcome {}".format(name))
```

---

# f-Strings

Recommended approach.

```python
name = "John"

print(f"Welcome {name}")
```

Output:

```text
Welcome John
```

---

# Multiple Variables

```python
name = "John"
age = 25

print(f"Name: {name}, Age: {age}")
```

---

# Real-World Example

## Email Generator

```python
name = "john"

email = name + "@company.com"

print(email)
```

Output:

```text
john@company.com
```

---

# Real-World Example

## Username Generator

```python
first_name = "john"
last_name = "doe"

username = first_name + last_name

print(username)
```

---

# Common Beginner Mistakes

## Forgetting Quotes

Incorrect:

```python
name = Python
```

Correct:

```python
name = "Python"
```

---

## Invalid Index

```python
text = "Python"

print(text[10])
```

Output:

```text
IndexError
```

---

## Modifying Strings

Strings are immutable.

Use replace() or create a new string.

---

# Mini Project

## Welcome Message Generator

```python
name = input("Enter your name: ")

print(f"Welcome {name}!")
```

---

# Best Practices

- Use meaningful variable names
- Prefer f-strings
- Avoid hardcoded text
- Use string methods instead of manual operations
- Keep formatting consistent

---

# Summary

In this tutorial, you learned:

- Creating strings
- Indexing
- Slicing
- String methods
- Formatting
- Escape characters
- String immutability

Strings are one of the most important data types in Python.

---

# Key Takeaways

- Strings store text
- Strings are immutable
- Indexing accesses characters
- Slicing extracts portions
- String methods simplify text processing
- f-strings are the preferred formatting approach

---

# Practice Questions

1. What is a string?
2. What is string indexing?
3. What is slicing?
4. What does upper() do?
5. What does split() do?
6. What is string immutability?
7. Why are f-strings useful?

---

# Exercises

## Exercise 1

Create a string containing your name.

Display:
- Length
- First character
- Last character

---

## Exercise 2

Reverse a string using slicing.

---

## Exercise 3

Convert a sentence to uppercase.

---

## Exercise 4

Count occurrences of a word in a sentence.

---

## Exercise 5

Create a username generator using first and last names.

---

# Next Topic

➡️ String Methods in Python
