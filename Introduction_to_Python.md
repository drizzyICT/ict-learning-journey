# Introduction to Python

## What is Python?

Python is a high-level, interpreted programming language known for its simplicity and readability. It is widely used in web development, data science, artificial intelligence, cybersecurity, automation, and software development.

Python was created by **Guido van Rossum** and first released in **1991**.

---

## Why Learn Python?

Python is popular because:

* Easy to learn and read
* Large community support
* Free and open source
* Works on Windows, Linux, and macOS
* Used by companies such as Google, Netflix, and Instagram

---

## Installing Python

1. Visit python.org
2. Download the latest version of Python
3. Run the installer
4. Verify installation by opening a terminal and typing:

```python
python --version
```

---

## Writing Your First Python Program

```python
print("Hello, World!")
```

Output:

```text
Hello, World!
```

The `print()` function displays information on the screen.

---

## Variables

Variables store data.

Example:

```python
name = "Chazima"
age = 20

print(name)
print(age)
```

Output:

```text
Chazima
20
```

---

## Data Types

Python supports several data types:

### String

```python
name = "Python"
```

### Integer

```python
age = 20
```

### Float

```python
height = 5.8
```

### Boolean

```python
is_student = True
```

---

## User Input

Python allows users to enter data.

```python
name = input("Enter your name: ")

print("Hello", name)
```

---

## Arithmetic Operators

```python
a = 10
b = 5

print(a + b)
print(a - b)
print(a * b)
print(a / b)
```

Operators:

| Operator | Meaning        |
| -------- | -------------- |
| +        | Addition       |
| -        | Subtraction    |
| *        | Multiplication |
| /        | Division       |
| %        | Modulus        |
| **       | Power          |

---

## Conditional Statements

Used for decision making.

```python
age = 18

if age >= 18:
    print("Adult")
else:
    print("Minor")
```

---

## Loops

### For Loop

```python
for i in range(5):
    print(i)
```

Output:

```text
0
1
2
3
4
```

### While Loop

```python
count = 1

while count <= 5:
    print(count)
    count += 1
```

---

## Functions

Functions help organize code.

```python
def greet():
    print("Welcome to Python!")

greet()
```

Functions can also accept parameters:

```python
def greet(name):
    print("Hello", name)

greet("Chazima")
```

---

## Lists

Lists store multiple values.

```python
fruits = ["Apple", "Banana", "Orange"]

print(fruits[0])
```

Output:

```text
Apple
```

---

## Dictionaries

Dictionaries store data as key-value pairs.

```python
student = {
    "name": "Chazima",
    "course": "ICT"
}

print(student["name"])
```

---

## Comments

Comments explain code.

```python
# This is a comment

print("Python")
```

---

## Applications of Python

Python is used in:

* Web Development
* Data Analysis
* Artificial Intelligence
* Machine Learning
* Cybersecurity
* Automation
* Game Development

---

## Summary

Python is one of the most beginner-friendly programming languages. It is easy to learn, powerful, and widely used in the technology industry. Learning Python provides a strong foundation for careers in software development, data science, cybersecurity, and many other ICT fields.

### Learning Goals

* Understand Python syntax
* Write simple programs
* Use variables and data types
* Work with loops and functions
* Build small projects

---

*Prepared by: Chazima (@drizzyICT)*
