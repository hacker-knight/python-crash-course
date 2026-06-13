# String Methods in Python

## Introduction

String methods are built-in functions that allow us to manipulate and process text efficiently.

Python provides dozens of powerful string methods for:

- Formatting text
- Searching text
- Replacing text
- Validating text
- Splitting text
- Joining text

In this tutorial, you will learn:

- Commonly used string methods
- Text processing techniques
- Real-world examples
- Best practices
- Exercises

---

# What are String Methods?

String methods are built-in functions associated with string objects.

Example:

```python
text = "python"

print(text.upper())
```

Output:

```text
PYTHON
```

---

# Case Conversion Methods

## upper()

Converts all characters to uppercase.

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

Converts all characters to lowercase.

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

Converts the first letter of every word to uppercase.

```python
text = "python programming language"

print(text.title())
```

Output:

```text
Python Programming Language
```

---

## capitalize()

Capitalizes only the first letter.

```python
text = "python"

print(text.capitalize())
```

Output:

```text
Python
```

---

## swapcase()

Swaps uppercase and lowercase characters.

```python
text = "PyThOn"

print(text.swapcase())
```

Output:

```text
pYtHoN
```

---

# Search Methods

## find()

Returns the first index position.

```python
text = "Python Programming"

print(text.find("Programming"))
```

Output:

```text
7
```

---

## rfind()

Searches from right to left.

```python
text = "Python Python"

print(text.rfind("Python"))
```

Output:

```text
7
```

---

## index()

Similar to find() but raises an error if not found.

```python
text = "Python"

print(text.index("t"))
```

Output:

```text
2
```

---

## count()

Counts occurrences.

```python
text = "Python Python Python"

print(text.count("Python"))
```

Output:

```text
3
```

---

# Replace Methods

## replace()

Replaces text.

```python
text = "I love Java"

print(text.replace("Java", "Python"))
```

Output:

```text
I love Python
```

---

# Whitespace Methods

## strip()

Removes spaces from both sides.

```python
text = "  Python  "

print(text.strip())
```

Output:

```text
Python
```

---

## lstrip()

Removes left spaces.

```python
print("   Python".lstrip())
```

---

## rstrip()

Removes right spaces.

```python
print("Python   ".rstrip())
```

---

# Splitting and Joining

## split()

Converts a string into a list.

```python
text = "Python SQL PowerBI"

print(text.split())
```

Output:

```text
['Python', 'SQL', 'PowerBI']
```

---

## split(separator)

```python
text = "Python,SQL,PowerBI"

print(text.split(","))
```

Output:

```text
['Python', 'SQL', 'PowerBI']
```

---

## join()

Combines elements into a string.

```python
skills = ["Python", "SQL", "PowerBI"]

print(", ".join(skills))
```

Output:

```text
Python, SQL, PowerBI
```

---

# Validation Methods

Validation methods return True or False.

---

## isalpha()

Checks whether all characters are alphabetic.

```python
print("Python".isalpha())
```

Output:

```text
True
```

---

## isdigit()

Checks whether all characters are digits.

```python
print("12345".isdigit())
```

Output:

```text
True
```

---

## isalnum()

Checks letters and numbers.

```python
print("Python123".isalnum())
```

Output:

```text
True
```

---

## islower()

```python
print("python".islower())
```

Output:

```text
True
```

---

## isupper()

```python
print("PYTHON".isupper())
```

Output:

```text
True
```

---

## istitle()

```python
print("Python Programming".istitle())
```

Output:

```text
True
```

---

## isspace()

Checks whether string contains only spaces.

```python
print("   ".isspace())
```

Output:

```text
True
```

---

# Startswith and Endswith

## startswith()

```python
text = "Python Programming"

print(text.startswith("Python"))
```

Output:

```text
True
```

---

## endswith()

```python
print(text.endswith("Programming"))
```

Output:

```text
True
```

---

# String Alignment Methods

## center()

```python
text = "Python"

print(text.center(20))
```

---

## ljust()

```python
print(text.ljust(20))
```

---

## rjust()

```python
print(text.rjust(20))
```

---

# Formatting Methods

## format()

```python
name = "John"

print("Welcome {}".format(name))
```

Output:

```text
Welcome John
```

---

## Multiple Values

```python
name = "John"
age = 25

print("Name: {}, Age: {}".format(name, age))
```

---

# Modern Alternative: f-Strings

```python
name = "John"
age = 25

print(f"Name: {name}, Age: {age}")
```

Output:

```text
Name: John, Age: 25
```

---

# Real-World Example

## Email Validation

```python
email = "user@example.com"

print("@" in email)
print(email.endswith(".com"))
```

---

# Real-World Example

## Username Cleaning

```python
username = "  john_doe  "

clean_username = username.strip()

print(clean_username)
```

Output:

```text
john_doe
```

---

# Real-World Example

## Search in Product Names

```python
product = "Laptop Computer"

print(product.lower().find("computer"))
```

---

# Method Chaining

Multiple methods can be combined.

```python
text = "  python programming  "

result = text.strip().title()

print(result)
```

Output:

```text
Python Programming
```

---

# Common Beginner Mistakes

## Forgetting Parentheses

Incorrect:

```python
text.upper
```

Correct:

```python
text.upper()
```

---

## Assuming Methods Modify Original String

Incorrect assumption:

```python
text = "python"

text.upper()

print(text)
```

Output:

```text
python
```

Strings are immutable.

---

## Correct Version

```python
text = "python"

text = text.upper()

print(text)
```

Output:

```text
PYTHON
```

---

# Mini Project

## User Registration Validator

```python
username = input("Enter username: ")

if username.isalnum():
    print("Valid Username")
else:
    print("Invalid Username")
```

---

# Best Practices

- Use strip() when processing user input
- Use lower() for case-insensitive comparisons
- Prefer f-strings for formatting
- Validate data using built-in methods
- Use method chaining carefully

---

# Summary

In this tutorial, you learned:

- Case conversion methods
- Search methods
- Validation methods
- Split and join methods
- Formatting methods
- Real-world applications

String methods are essential for data cleaning and text processing.

---

# Key Takeaways

- String methods simplify text manipulation
- Strings are immutable
- Validation methods return Boolean values
- split() and join() are frequently used
- f-strings provide modern formatting

---

# Practice Questions

1. What does upper() do?
2. What is the difference between find() and index()?
3. What does split() return?
4. What is method chaining?
5. What does isdigit() check?
6. Why are strings immutable?

---

# Exercises

## Exercise 1

Convert a sentence to:
- Uppercase
- Lowercase
- Title Case

---

## Exercise 2

Count occurrences of a word.

---

## Exercise 3

Validate whether a string contains only numbers.

---

## Exercise 4

Split a comma-separated string into a list.

---

## Exercise 5

Create a username cleaning program using strip().

---

# Next Topic

➡️ Comments and Formatting in Python
