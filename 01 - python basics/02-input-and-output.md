# Input and Output in Python

## Introduction

Input and Output (I/O) are fundamental concepts in programming.

Almost every program interacts with users by:

- Taking input from users
- Processing the input
- Displaying output

In this tutorial, you will learn:

- What input and output are
- The `print()` function
- The `input()` function
- Accepting user data
- Converting input data types
- Formatting output
- Common mistakes
- Real-world examples

---

# What is Output?

Output is the information displayed to the user.

Examples:
- Displaying messages
- Showing calculation results
- Printing reports
- Displaying menus

In Python, output is usually displayed using the `print()` function.

---

# The print() Function

The `print()` function is used to display output on the screen.

Syntax:

```python
print(value)
```

Example:

```python
print("Welcome to Python")
```

Output:

```text
Welcome to Python
```

---

# Printing Text

```python
print("Hello World")
print("Python is easy")
```

Output:

```text
Hello World
Python is easy
```

---

# Printing Numbers

```python
print(100)
print(99.99)
```

Output:

```text
100
99.99
```

---

# Printing Multiple Values

```python
name = "John"
age = 25

print(name, age)
```

Output:

```text
John 25
```

---

# Using the sep Parameter

The `sep` parameter specifies the separator between values.

Example:

```python
print("Python", "SQL", "Power BI", sep=" | ")
```

Output:

```text
Python | SQL | Power BI
```

---

# Using the end Parameter

By default, `print()` moves to a new line.

Example:

```python
print("Hello", end=" ")
print("World")
```

Output:

```text
Hello World
```

---

# What is Input?

Input is information entered by a user.

Examples:
- Name
- Age
- Email
- Marks
- Password

Python uses the `input()` function to receive user input.

---

# The input() Function

Syntax:

```python
input("Message")
```

Example:

```python
name = input("Enter your name: ")
```

---

# Taking User Input

```python
name = input("Enter your name: ")

print(name)
```

Example:

```text
Enter your name: John
John
```

---

# Storing User Input

```python
city = input("Enter your city: ")

print(city)
```

Output:

```text
Mumbai
```

---

# Understanding Input Data Types

Important:

The `input()` function always returns a string.

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

# Numeric Input

Suppose the user enters:

```text
25
```

Python still stores it as a string.

```python
age = input("Enter age: ")

print(type(age))
```

Output:

```text
<class 'str'>
```

---

# Converting Input to Integer

Use `int()`.

```python
age = int(input("Enter age: "))
```

Now:

```python
print(type(age))
```

Output:

```text
<class 'int'>
```

---

# Converting Input to Float

Use `float()`.

```python
salary = float(input("Enter salary: "))
```

---

# Taking Multiple Inputs

Method 1:

```python
name = input("Enter name: ")
age = int(input("Enter age: "))
```

---

# Multiple Inputs in One Line

```python
name, city = input("Enter name and city: ").split()
```

Input:

```text
John Mumbai
```

Output:

```python
print(name)
print(city)
```

---

# Example: Addition Program

```python
num1 = int(input("Enter first number: "))
num2 = int(input("Enter second number: "))

result = num1 + num2

print(result)
```

Input:

```text
10
20
```

Output:

```text
30
```

---

# Example: Area of Rectangle

```python
length = float(input("Enter length: "))
width = float(input("Enter width: "))

area = length * width

print(area)
```

---

# Example: Student Information

```python
name = input("Enter student name: ")
course = input("Enter course: ")

print(name)
print(course)
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

# Mixing Strings and Numbers

Incorrect:

```python
age = 25

print("Age: " + age)
```

This causes an error.

---

# Correct Method

```python
age = 25

print("Age:", age)
```

Or:

```python
print("Age: " + str(age))
```

---

# f-Strings

f-Strings are the modern way to format output.

Syntax:

```python
f"text {variable}"
```

Example:

```python
name = "John"

print(f"Welcome {name}")
```

Output:

```text
Welcome John
```

---

# Multiple Variables in f-Strings

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

# Escape Characters

## New Line

```python
print("Python\nSQL\nPower BI")
```

Output:

```text
Python
SQL
Power BI
```

---

## Tab Space

```python
print("Python\tSQL\tPower BI")
```

---

# Real-World Example

Employee Information System:

```python
name = input("Enter employee name: ")
salary = float(input("Enter salary: "))

print(f"Employee: {name}")
print(f"Salary: {salary}")
```

---

# Common Beginner Mistakes

## Forgetting Type Conversion

Incorrect:

```python
num1 = input("Enter number: ")
num2 = input("Enter number: ")

print(num1 + num2)
```

Input:

```text
10
20
```

Output:

```text
1020
```

Because both values are strings.

---

## Correct Version

```python
num1 = int(input("Enter number: "))
num2 = int(input("Enter number: "))

print(num1 + num2)
```

Output:

```text
30
```

---

# Mini Project: User Profile Generator

```python
name = input("Enter your name: ")
age = int(input("Enter your age: "))
city = input("Enter your city: ")

print("\nUser Profile")
print("------------")
print(f"Name : {name}")
print(f"Age  : {age}")
print(f"City : {city}")
```

---

# Best Practices

- Use meaningful prompts
- Validate user input
- Use f-strings for formatting
- Convert numeric inputs when required
- Keep output readable

---

# Summary

In this tutorial, you learned:

- What input and output are
- How to use `print()`
- How to use `input()`
- Type conversion
- String formatting
- f-strings
- Common mistakes

Input and output form the foundation of interactive Python applications.

---

# Key Takeaways

- `print()` displays output
- `input()` receives user input
- Input values are strings by default
- Use `int()` and `float()` when needed
- f-strings provide clean formatting

---

# Practice Questions

1. What is output?
2. What is input?
3. Which function is used to take input?
4. Which function displays output?
5. Why is type conversion important?
6. What is an f-string?
7. What does the `sep` parameter do?

---

# Exercises

## Exercise 1

Take user input for:
- Name
- Age
- City

Display the information.

---

## Exercise 2

Take two numbers as input and display:
- Addition
- Subtraction
- Multiplication
- Division

---

## Exercise 3

Create a program that calculates the area of a rectangle.

---

## Exercise 4

Create a simple user profile generator using f-strings.

---

# Next Topic

➡️ Operators in Python
