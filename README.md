# 🐍 Python Learning & Practice

Welcome to my **Python Learning & Practice** repository.

This repository contains my Python learning journey, practice programs, exercises, and examples covering Python fundamentals to intermediate-level concepts.

The goal is to build a strong foundation in Python through **hands-on coding and problem solving**.

---

## 📚 Topics Covered

### 1. Python Basics

* Python syntax
* Variables
* Data types
* Type conversion
* `input()` and `print()`
* Comments
* Operators
* String manipulation
* `upper()` / `lower()`
* `round()`
* `isinstance()`

### 2. Conditional Statements

* `if`
* `elif`
* `else`
* Nested conditions
* Comparison operators
* Logical operators
* Chained comparisons

Example:

```python
if a <= b <= c:
    print("Numbers are in ascending order")
```

---

### 3. Loops

* `for` loop
* `while` loop
* `range()`
* Nested loops
* `break`
* `continue`

Practice programs include:

* Multiplication tables
* Sum of even numbers
* Sum of odd numbers
* Number patterns
* Iterating through lists

---

### 4. Strings

* String indexing
* String slicing
* String methods
* Case conversion
* String formatting
* f-strings

Example:

```python
name = input("Enter your name: ")
print(f"Hello, {name.upper()}!")
```

---

### 5. Lists

* Creating lists
* Accessing elements
* Adding/removing elements
* List indexing
* List slicing
* Iterating through lists
* Converting user input into lists

Example:

```python
numbers = list(map(int, input("Enter numbers: ").split(",")))

print(numbers)
```

Input:

```text
1,2,3,4
```

Output:

```text
[1, 2, 3, 4]
```

---

### 6. Functions

* Defining functions
* Parameters and arguments
* Return values
* Default arguments
* `*args`
* `**kwargs`
* Function scope

Example:

```python
def add_numbers(a, b):
    return a + b

result = add_numbers(10, 20)
print(result)
```

---

### 7. Object-Oriented Programming

* Classes
* Objects
* Instance variables
* Class variables
* Constructors
* Methods
* Inheritance
* Encapsulation
* Polymorphism

Example:

```python
class Employee:

    def __init__(self, name, salary):
        self.name = name
        self.salary = salary

    def display(self):
        print(self.name, self.salary)
```

---

### 8. Exception Handling

* `try`
* `except`
* `else`
* `finally`
* Handling `ValueError`
* Handling invalid user input

Example:

```python
try:
    mark = float(input("Enter your mark: "))
except ValueError:
    print("Please enter a valid number.")
```

---

### 9. Practical Programs

This section contains small programs based on real-world scenarios.

Examples:

* Swiggy bill calculation
* Hotel VIP/member benefits
* Discount calculation
* Multiplication table generator
* Even/odd number calculations
* Mark validation
* Number comparison
* User input validation

