# Python Installation and Setup

## Introduction

Before writing Python programs, we need to install Python and set up a development environment.

In this tutorial, you will learn:

- How to install Python
- How to verify the installation
- How to install VS Code
- How to configure Python in VS Code
- How to run Python programs
- How to install Python packages
- How to create virtual environments

By the end of this tutorial, you will have a complete Python development setup ready for programming.

---

# System Requirements

Python works on multiple operating systems:

- Windows
- Linux
- macOS

Recommended system specifications:

| Component | Requirement |
|---|---|
| RAM | 4 GB or higher |
| Storage | 2 GB free space |
| OS | Windows 10+, Ubuntu 20+, macOS |
| Internet | Required for installation |

---

# Step 1 — Download Python

Official Python website:

- https://www.python.org/downloads/

Always download the latest stable version of Python 3.

---

# Installing Python on Windows

## Step 1 — Download Installer

Go to:
- https://www.python.org/downloads/

Click:

```text
Download Python 3.x.x
```

---

## Step 2 — Run Installer

Open the downloaded installer.

IMPORTANT:

✅ Check the box:

```text
Add Python to PATH
```

Then click:

```text
Install Now
```

---

## Step 3 — Wait for Installation

After installation completes, you should see:

```text
Setup was successful
```

---

# Installing Python on macOS

## Method 1 — Official Installer

Download Python from:
- https://www.python.org/downloads/macos/

---

## Method 2 — Using Homebrew

```bash
brew install python
```

---

# Installing Python on Linux

Check Python version:

```bash
python3 --version
```

Install if needed:

## Ubuntu / Debian

```bash
sudo apt update
sudo apt install python3
```

## Fedora

```bash
sudo dnf install python3
```

---

# Step 2 — Verify Python Installation

Run:

```bash
python --version
```

or

```bash
python3 --version
```

Example:

```text
Python 3.13.0
```

---

# Step 3 — Open Python Interpreter

Run:

```bash
python
```

You should see:

```text
>>>
```

---

# Your First Python Program

```python
print("Hello, Python!")
```

Output:

```text
Hello, Python!
```

---

# Exit Python Interpreter

```python
exit()
```

---

# Installing Visual Studio Code (VS Code)

## What is VS Code?

VS Code is a lightweight and powerful code editor.

Features:
- Syntax highlighting
- Auto-completion
- Extensions
- Integrated terminal
- Debugging support

Official website:

- https://code.visualstudio.com/

---

# Install Python Extension in VS Code

Open VS Code.

Go to:

```text
Extensions → Search "Python"
```

Install the extension provided by Microsoft.

---

# Configure Python Interpreter

Press:

```text
Ctrl + Shift + P
```

Search:

```text
Python: Select Interpreter
```

Choose the installed Python version.

---

# Creating Your First Python File

Create a file:

```text
hello.py
```

Write:

```python
print("Welcome to Python")
```

Run:

```bash
python hello.py
```

Output:

```text
Welcome to Python
```

---

# Understanding File Extensions

Python files use:

```text
.py
```

Examples:
- app.py
- main.py
- calculator.py

---

# Installing Python Packages

Python packages are installed using:

```bash
pip
```

---

# Verify pip Installation

```bash
pip --version
```

---

# Install Your First Package

```bash
pip install numpy
```

---

# Commonly Used Libraries

| Category | Libraries |
|---|---|
| Data Analysis | pandas, numpy |
| Machine Learning | scikit-learn |
| Deep Learning | tensorflow, pytorch |
| Visualization | matplotlib, seaborn |
| Web Development | flask, django |

---

# Upgrading pip

```bash
python -m pip install --upgrade pip
```

---

# Virtual Environments

## Create Virtual Environment

```bash
python -m venv myenv
```

---

## Activate Virtual Environment

### Windows

```bash
myenv\Scripts\activate
```

### Linux/macOS

```bash
source myenv/bin/activate
```

---

## Deactivate Virtual Environment

```bash
deactivate
```

---

# Installing Jupyter Notebook

```bash
pip install notebook
```

Run:

```bash
jupyter notebook
```

---

# Common Installation Errors

## Python Not Recognized

Solution:
- Reinstall Python
- Enable:
  - Add Python to PATH

---

## pip Not Recognized

```bash
python -m ensurepip --upgrade
```

---

# Recommended Development Setup

## Beginner Setup

- Python
- VS Code
- Python Extension

---

## Data Science Setup

Install:
- Jupyter Notebook
- NumPy
- Pandas
- Matplotlib

---

## AI/ML Setup

Install:
- TensorFlow
- PyTorch
- Scikit-learn

---

# Best Practices

- Always use Python 3
- Keep Python updated
- Use virtual environments
- Organize files properly

---

# Mini Exercise

## Task 1

Install Python and verify version.

---

## Task 2

Create:

```text
test.py
```

Write:

```python
print("Python Setup Successful")
```

---

## Task 3

Install NumPy:

```bash
pip install numpy
```

---

# Summary

In this tutorial, you learned:

- How to install Python
- How to configure VS Code
- How to run Python programs
- How to install packages
- How to use pip
- How to create virtual environments

---

# Key Takeaways

- Python installation is simple
- VS Code is powerful
- pip manages packages
- Virtual environments are important

---

# Practice Questions

1. What is pip?
2. Why are virtual environments important?
3. How do you check Python version?
4. What is the extension of Python files?
5. How do you install Python packages?

---

# Next Topic

➡️ Your First Python Program
