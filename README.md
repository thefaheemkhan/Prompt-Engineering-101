
## Python Mastery Topics:
1. Introduction to Python
2. Python Installation and Setup
3. Python Datatypes
4. Operators and Expressions
5. Conditional Statements
6. Loops - Control Flow
7. String and Its Methods
8. Formatted Printing
9. Regular Expressions
10. List
11. Tuple
12. Sets
13. Dictionary
14. Functions
15. More About Functions
16. Exception Handling
17. Object-Oriented Programming
18. Multithreading
19. Date and Time
20. Database Connectivity
21. Data Structure Modules
22. Math Modules
23. OS Modules
24. Tkinter
25. Numpy Arrays
---




# 3. _Python Datatypes_

### 3.1 Section Introduction
Python has several **built-in data types** that are used to store different kinds of data. Here’s a simple breakdown of the main ones:

---

### 🔢 **Basic Data Types**
| Type       | Description                         | Example           |
|------------|-------------------------------------|-------------------|
| `int`      | Integer numbers                     | `x = 5`           |
| `float`    | Decimal (floating-point) numbers    | `pi = 3.14`       |
| `complex`  | Complex numbers                     | `z = 2 + 3j`      |
| `bool`     | Boolean values                      | `is_valid = True` |
| `str`      | Strings (text)                      | `name = "Alice"`  |

---

### 📦 **Collection Data Types**
| Type       | Description                                      | Example                          |
|------------|--------------------------------------------------|----------------------------------|
| `list`     | Ordered, changeable, allows duplicates           | `nums = [1, 2, 3]`               |
| `tuple`    | Ordered, **unchangeable**, allows duplicates     | `coords = (10, 20)`             |
| `set`      | **Unordered**, no duplicates                     | `unique_vals = {1, 2, 3}`        |
| `dict`     | Key-value pairs                                  | `person = {"name": "Bob"}`       |

---

### ⏳ **Special Data Types**
| Type     | Description              | Example          |
|----------|--------------------------|------------------|
| `None`   | Represents "nothing"     | `x = None`       |
| `bytes`  | Immutable byte sequences | `b = b"hello"`   |
| `bytearray` | Mutable byte sequence | `ba = bytearray(5)` |

---

### 3.2 What is a Program?
A **program** is a set of **instructions written in a programming language** that a computer can follow to perform a specific task or solve a problem.

### 🔍 In simple words:
> A **program** tells the computer **what to do**, **how to do it**, and **in what order**.

---

### 📌 Example in Python:
```python
# This program adds two numbers
a = 5
b = 3
sum = a + b
print("The sum is:", sum)
```

🧠 Here, the program:
1. Stores two numbers (`a` and `b`)
2. Adds them
3. Prints the result

---

### 3.3 What are Variables?

### 🔧 **1. How Variables are Created in Python**
Variables are created **automatically** when you **assign a value** to a name using the `=` sign.

📌 **Syntax:**
```python
variable_name = value
```

📦 **Examples:**
```python
x = 10
name = "Alice"
is_cool = True
```

No need to declare the type — Python figures it out!

---

### 📦 **2. What Information Does a Variable Hold?**

A variable holds **two things**:
1. The **data (value)** itself
2. The **data type** of that value

🧠 For example:
```python
age = 18
```
- Variable name: `age`
- Value: `18`
- Data type: `int`

It’s like labeling a box with a name and putting something (a value) inside it.

---

### 🏷️ **3. How Names Are Given to Data (Variable Names)**

#### ✅ Rules for Naming Variables:
- Must **start with a letter** or `_` (underscore)
- Can contain **letters, numbers, and underscores**
- **Cannot** use spaces or special characters like `@`, `#`, etc.
- **Case-sensitive**: `Name` and `name` are different
- Should **not use reserved keywords** (`if`, `while`, `class`, etc.)

📌 **Good Names:**
```python
user_name = "Ali"
total_score = 99
is_admin = False
```

📌 **Bad Names (❌):**
```python
2name = "Error"      # Starts with number
user-name = "Error"  # Contains a hyphen
class = "Error"      # 'class' is a keyword
```

---



Python Dynamically Typed
Rules for Declaring Variable Names
Python Datatypes
Variables - Practice Questions 
Set up Jupyter for Practice
Numeric Datatypes (int & float)
Numeric Datatype (bool & complex)
Literals or Constants
Integer Literals
Numeric Type & Literals - Practice Questions
Base Conversion
Type Conversion
Type and Base Conversions - Practice Questions 
