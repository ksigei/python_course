# Course: Introduction to Python Programming

## Table of Contents
1. [Introduction to Python](#introduction-to-python)
2. [Variables and Data Types](#variables-and-data-types)
3. [Control Structures](#control-structures)
4. [Loops](#loops)
5. [Lists](#lists)
6. [Functions](#functions)
7. [Exception Handling](#exception-handling)
8. [File Handling](#file-handling)
9. [Conclusion](#conclusion)

## Introduction to Python
- What is Python?
- Why Python is popular?
- Installing Python
- Writing and running a Python script
- Python versions and differences

```python
# Hello, World! in Python
print("Hello, World!")

# Variables and assignments
name = "Alice"
age = 30
```

## Variables and Data Types
- Variables and assignments
- Numeric data types: int and float
- Text data type: str
- Boolean data type: bool
- Type conversion

```python
# Numeric data types: int and float
x = 5
y = 3.14

# Text data type: str
name = "Bob"

# Boolean data type: bool
is_student = True

# Type conversion
age = 25
age_str = str(age)
```

## Control Structures
- Conditional statements: if, elif, else
- Logical operators: and, or, not
- Comparison operators: ==, !=, <, >, <=, >=
- The `if-elif-else` construct
- Indentation and code blocks

```python
# Conditional statements: if, elif, else
if age >= 18:
    print("You are an adult.")
elif age < 18:
    print("You are a minor.")
else:
    print("You are in-between.")

# Logical operators: and, or, not
if is_student and age < 30:
    print("You are a young student.")

# Comparison operators: ==, !=, <, >, <=, >=
if x != 0:
    print("x is not zero.")
```

## Loops
- The `for` loop
- The `while` loop
- Loop control statements: `break` and `continue`
- Iterating through sequences
- Nested loops

```python
# The 'for' loop
for i in range(5):
    print(i)

# The 'while' loop
count = 0
while count < 5:
    print(count)
    count += 1
```

## Lists
- Creating and modifying lists
- Accessing list elements
- List slicing
- List methods: append, insert, remove, pop
- List comprehension

```python
# Creating and modifying lists
fruits = ["apple", "banana", "cherry"]
fruits.append("orange")
fruits[1] = "kiwi"

# Accessing list elements
print(fruits[0])  # Output: "apple"

# List slicing
subset = fruits[1:3]  # Gets elements at index 1 and 2
```

## Functions
- Defining and calling functions
- Parameters and arguments
- Return values
- Function scope
- Lambda functions

```python
# Defining a function
def greet(name):
    return f"Hello, {name}!"

message = greet("Alice")
print(message)

# Parameters and arguments
def add(a, b):
    return a + b

result = add(3, 5)
```

## Exception Handling
- Handling exceptions with `try` and `except`
- Multiple `except` clauses
- The `else` and `finally` blocks
- Raising exceptions
- Custom exception classes

```python
# Handling exceptions with 'try' and 'except'
try:
    result = 10 / 0  # Attempting to divide by zero
except ZeroDivisionError as e:
    print(f"Error: {e}")

# Raising exceptions
def divide(a, b):
    if b == 0:
        raise ValueError("Cannot divide by zero.")
    return a / b
```

## File Handling
- Opening and closing files
- Reading from and writing to files
- Working with text and binary files
- Using the `with` statement
- Handling file exceptions

```python
# Writing to a file
with open("example.txt", "w") as file:
    file.write("Hello, world!")

# Reading from a file
with open("example.txt", "r") as file:
    content = file.read()
    print(content)
```

## Conclusion
- Recap of key Python concepts
- Next steps in your Python learning journey 
```
