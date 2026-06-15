# python-notes


# Introduction to Python

**Python** is a high-level, interpreted, and general-purpose programming language created by Guido van Rossum and first released in 1991.

It is one of the most popular programming languages because of its **simple syntax**, **readability**, and **wide range of applications**.

### Key Features of Python

* **Easy to Learn:** Simple English-like syntax.
* **Interpreted Language:** No need to compile before execution.
* **Object-Oriented:** Supports classes and objects.
* **Platform Independent:** Runs on Windows, Linux, and macOS.
* **Open Source:** Free to use and modify.
* **Large Library Support:** Thousands of built-in and external libraries.

### Applications of Python

1. **Web Development**

   * Frameworks: Django, Flask

2. **Data Science & Analytics**

   * Libraries: NumPy, Pandas, Matplotlib

3. **Machine Learning & AI**

   * Libraries: Scikit-learn, TensorFlow, PyTorch

4. **Automation & Scripting**

   * Automating repetitive tasks

5. **Desktop Applications**

   * Tkinter, PyQt

6. **Game Development**

   * Pygame

7. **Cybersecurity**

   * Network and security tools

### Simple Python Program

```python
print("Hello, World!")
```

**Output:**

```
Hello, World!
```

### Advantages of Python

* Easy to read and write
* Large community support
* Extensive libraries
* Fast development
* Suitable for beginners and professionals

### Disadvantages of Python

* Slower than C/C++
* Higher memory usage
* Not ideal for mobile app development

### Conclusion

Python is a versatile and beginner-friendly programming language used in **Web Development, Data Science, Machine Learning, Artificial Intelligence, Automation, and Software Development**. Its simplicity and powerful libraries make it one of the best languages for learning programming and building real-world applications.





# Applications of Python

Python is used in many fields because it is easy to learn and has powerful libraries.

## 1. Web Development

Python is used to create websites and web applications.

**Frameworks:**

* Django
* Flask
* FastAPI

**Examples:**

* E-commerce websites
* Blog websites
* Social media platforms

---

## 2. Data Science & Data Analysis

Python helps analyze large amounts of data and create reports.

**Libraries:**

* NumPy
* Pandas
* Matplotlib
* Seaborn

**Examples:**

* Sales analysis
* Business reports
* Data visualization

---

## 3. Machine Learning & Artificial Intelligence

Python is the most popular language for AI and ML.

**Libraries:**

* Scikit-learn
* TensorFlow
* PyTorch

**Examples:**

* Chatbots
* Recommendation systems
* Image recognition
* Speech recognition

---

## 4. Automation & Scripting

Python can automate repetitive tasks.

**Examples:**

* File management
* Sending emails automatically
* Data entry automation
* Web scraping

---

## 5. Desktop Application Development

Python can create GUI (Graphical User Interface) applications.

**Libraries:**

* Tkinter
* PyQt
* Kivy

**Examples:**

* Calculator
* Text editor
* Management systems

---

## 6. Game Development

Python is used to develop simple and medium-sized games.

**Library:**

* Pygame

**Examples:**

* Snake Game
* Tic-Tac-Toe
* Racing Games

---

## 7. Cybersecurity & Ethical Hacking

Python is widely used for security testing and network analysis.

**Examples:**

* Network scanning
* Password testing
* Security automation

---

## 8. Internet of Things (IoT)

Python is used to program smart devices.

**Examples:**

* Smart home systems
* Sensors
* Raspberry Pi projects

---

## 9. Cloud Computing

Python is used in cloud platforms and DevOps.

**Examples:**

* Cloud automation
* Server management
* Deployment scripts

---

## 10. Scientific & Research Computing

Scientists use Python for mathematical calculations and simulations.

**Libraries:**

* SciPy
* SymPy

**Examples:**

* Physics simulations
* Research projects
* Statistical analysis

---

## Real-World Companies Using Python

* Google
* Netflix
* Instagram
* Spotify
* Dropbox

### Summary

Python is mainly used for:

1. Web Development
2. Data Science
3. Machine Learning & AI
4. Automation
5. Desktop Applications
6. Game Development
7. Cybersecurity
8. IoT
9. Cloud Computing
10. Scientific Research

For a BCA student aiming for **Data Science and AI/ML**, focus first on:
**Python Basics → Data Structures → NumPy → Pandas → Machine Learning → Deep Learning.**


# Input and Output in Python

Input and Output are basic operations in Python.

* **Input:** Taking data from the user.
* **Output:** Displaying data to the user.

---

## 1. Output Function (`print()`)

The `print()` function is used to display output on the screen.

### Example 1

```python
print("Hello World")
```

**Output:**

```
Hello World
```

### Example 2

```python
name = "Anish"
print(name)
```

**Output:**

```
Anish
```

---

## 2. Input Function (`input()`)

The `input()` function is used to take input from the user.

### Example

```python
name = input("Enter your name: ")
print("Welcome", name)
```

**Input:**

```
Anish
```

**Output:**

```
Welcome Anish
```

---

## 3. Taking Integer Input

By default, `input()` returns a string. Use `int()` to convert it into an integer.

```python
age = int(input("Enter your age: "))
print(age)
```

**Input:**

```
20
```

**Output:**

```
20
```

---

## 4. Taking Float Input

```python
price = float(input("Enter price: "))
print(price)
```

**Input:**

```
99.5
```

**Output:**

```
99.5
```

---

## 5. Multiple Inputs in One Line

```python
a, b = map(int, input().split())

print(a)
print(b)
```

**Input:**

```
10 20
```

**Output:**

```
10
20
```

---

## 6. Formatted Output (f-string)

```python
name = "Anish"
age = 20

print(f"My name is {name} and I am {age} years old.")
```

**Output:**

```
My name is Anish and I am 20 years old.
```

---

## Summary

| Function   | Purpose                          |
| ---------- | -------------------------------- |
| `print()`  | Displays output                  |
| `input()`  | Takes user input                 |
| `int()`    | Converts input to integer        |
| `float()`  | Converts input to decimal number |
| `f-string` | Prints formatted output          |

### Example Program

```python
name = input("Enter your name: ")
age = int(input("Enter your age: "))

print(f"Hello {name}")
print(f"You are {age} years old")
```

This program takes the user's name and age as input and displays them as output.


# Variables in Python

A **variable** is a name used to store data in memory. Variables allow us to store values and use them later in a program.

## Syntax

```python
variable_name = value
```

### Example

```python
name = "Anish"
age = 20
salary = 50000
```

Here:

* `name` stores a string.
* `age` stores an integer.
* `salary` stores a number.

---

## Rules for Naming Variables

✅ Valid Variable Names

```python
name = "Anish"
_age = 20
student1 = "Rahul"
total_marks = 450
```

❌ Invalid Variable Names

```python
1name = "Anish"      # Cannot start with a number
class = "Python"     # Reserved keyword
my-name = "Anish"    # Hyphen not allowed
```

---

## Types of Variables

### 1. Integer (`int`)

```python
age = 20
```

### 2. Float (`float`)

```python
price = 99.99
```

### 3. String (`str`)

```python
name = "Anish"
```

### 4. Boolean (`bool`)

```python
is_student = True
```

---

## Multiple Variable Assignment

### Assign Different Values

```python
name = "Anish"
age = 20
city = "Delhi"
```

### Assign Multiple Values in One Line

```python
name, age, city = "Anish", 20, "Delhi"
```

### Assign Same Value to Multiple Variables

```python
x = y = z = 100
```

---

## Checking Variable Type

Use `type()` to check the data type.

```python
age = 20
print(type(age))
```

**Output:**

```python
<class 'int'>
```

---

## Dynamic Typing in Python

Python allows changing the type of a variable.

```python
x = 10
print(x)

x = "Hello"
print(x)
```

**Output:**

```python
10
Hello
```

---

## Example Program

```python
name = "Anish"
age = 20
cgpa = 8.5

print("Name:", name)
print("Age:", age)
print("CGPA:", cgpa)
```

**Output:**

```python
Name: Anish
Age: 20
CGPA: 8.5
```

## Key Points

* Variables store data.
* No need to declare a type in Python.
* Use meaningful variable names.
* Variable names are case-sensitive (`age` and `Age` are different).
* Use `type()` to check the data type.

### Practice Question

Write a Python program that stores:

* Your name
* Your age
* Your city

and prints them using `print()`.



# Operators in Python

**Operators** are special symbols used to perform operations on variables and values.

Example:

```python
a = 10
b = 5

print(a + b)
```

**Output:**

```
15
```

---

# Types of Operators in Python

## 1. Arithmetic Operators

Used for mathematical calculations.

| Operator | Meaning             | Example        |
| -------- | ------------------- | -------------- |
| `+`      | Addition            | `10 + 5 = 15`  |
| `-`      | Subtraction         | `10 - 5 = 5`   |
| `*`      | Multiplication      | `10 * 5 = 50`  |
| `/`      | Division            | `10 / 5 = 2.0` |
| `//`     | Floor Division      | `10 // 3 = 3`  |
| `%`      | Modulus (Remainder) | `10 % 3 = 1`   |
| `**`     | Exponent            | `2 ** 3 = 8`   |

### Example

```python
a = 10
b = 3

print(a + b)
print(a - b)
print(a * b)
print(a / b)
print(a // b)
print(a % b)
print(a ** b)
```

---

## 2. Comparison (Relational) Operators

Used to compare values.

| Operator | Meaning                  |
| -------- | ------------------------ |
| `==`     | Equal to                 |
| `!=`     | Not equal to             |
| `>`      | Greater than             |
| `<`      | Less than                |
| `>=`     | Greater than or equal to |
| `<=`     | Less than or equal to    |

### Example

```python
a = 10
b = 5

print(a == b)
print(a != b)
print(a > b)
print(a < b)
```

**Output**

```
False
True
True
False
```

---

## 3. Assignment Operators

Used to assign values.

| Operator | Example  | Same As     |
| -------- | -------- | ----------- |
| `=`      | `x = 5`  | Assign      |
| `+=`     | `x += 3` | `x = x + 3` |
| `-=`     | `x -= 3` | `x = x - 3` |
| `*=`     | `x *= 3` | `x = x * 3` |
| `/=`     | `x /= 3` | `x = x / 3` |

### Example

```python
x = 10

x += 5
print(x)
```

**Output**

```
15
```

---

## 4. Logical Operators

Used to combine conditions.

| Operator | Meaning                      |
| -------- | ---------------------------- |
| `and`    | Both conditions must be True |
| `or`     | At least one condition True  |
| `not`    | Opposite result              |

### Example

```python
a = 10
b = 20

print(a > 5 and b > 15)
print(a > 15 or b > 15)
print(not(a > 5))
```

---

## 5. Identity Operators

Used to check whether two variables refer to the same object.

| Operator | Meaning          |
| -------- | ---------------- |
| `is`     | Same object      |
| `is not` | Different object |

### Example

```python
x = [1, 2]
y = x

print(x is y)
```

**Output**

```
True
```

---

## 6. Membership Operators

Used to check membership in a sequence.

| Operator | Meaning     |
| -------- | ----------- |
| `in`     | Present     |
| `not in` | Not Present |

### Example

```python
name = "Anish"

print("A" in name)
print("z" not in name)
```

**Output**

```
True
True
```

---

## 7. Bitwise Operators

Operate on binary numbers.

| Operator | Meaning     |    |
| -------- | ----------- | -- |
| `&`      | AND         |    |
| `        | `           | OR |
| `^`      | XOR         |    |
| `~`      | NOT         |    |
| `<<`     | Left Shift  |    |
| `>>`     | Right Shift |    |

### Example

```python
a = 5
b = 3

print(a & b)
print(a | b)
```

---

# Summary

| Operator Type | Examples          |            |
| ------------- | ----------------- | ---------- |
| Arithmetic    | `+ - * / % // **` |            |
| Comparison    | `== != > < >= <=` |            |
| Assignment    | `= += -= *= /=`   |            |
| Logical       | `and or not`      |            |
| Identity      | `is, is not`      |            |
| Membership    | `in, not in`      |            |
| Bitwise       | `&                | ^ ~ << >>` |

### Important for BCA Exams

Most frequently asked operators are:

1. Arithmetic Operators
2. Relational (Comparison) Operators
3. Logical Operators
4. Assignment Operators

Master these four first before moving to advanced Python topics like **if-else, loops, functions, lists, and dictionaries**.


# Keywords in Python

**Keywords** are reserved words in Python that have a special meaning and purpose.
They cannot be used as variable names, function names, or identifiers.

For example:

```python
if = 10
```

❌ This will give an error because `if` is a keyword.

---

# Common Python Keywords

| Keyword    | Purpose                    |
| ---------- | -------------------------- |
| `if`       | Conditional statement      |
| `else`     | Alternative condition      |
| `elif`     | Multiple conditions        |
| `for`      | Loop                       |
| `while`    | Loop                       |
| `break`    | Exit loop                  |
| `continue` | Skip current iteration     |
| `pass`     | Empty statement            |
| `def`      | Define function            |
| `return`   | Return value from function |
| `class`    | Create class               |
| `try`      | Exception handling         |
| `except`   | Handle exceptions          |
| `finally`  | Execute always             |
| `import`   | Import module              |
| `from`     | Import specific items      |
| `as`       | Alias name                 |
| `True`     | Boolean true               |
| `False`    | Boolean false              |
| `None`     | Represents no value        |
| `and`      | Logical AND                |
| `or`       | Logical OR                 |
| `not`      | Logical NOT                |
| `in`       | Membership operator        |
| `is`       | Identity operator          |
| `lambda`   | Anonymous function         |

---

# Examples

### `if` and `else`

```python
age = 18

if age >= 18:
    print("Adult")
else:
    print("Minor")
```

---

### `for` Loop

```python
for i in range(5):
    print(i)
```

**Output:**

```
0
1
2
3
4
```

---

### Function using `def`

```python
def greet():
    print("Hello Python")

greet()
```

---

# How to View All Keywords

```python
import keyword

print(keyword.kwlist)
```

This displays the complete list of Python keywords.

---

# Important Points

* Keywords are **reserved words**.
* They have predefined meanings.
* Keywords cannot be used as variable names.
* Python keywords are **case-sensitive**.

  * `True` ✅ Keyword
  * `true` ❌ Not a keyword

### Examples of Invalid Variable Names

```python
class = "Python"   # Error
if = 10            # Error
for = 5            # Error
```

### Valid Variable Names

```python
class_name = "Python"
if_condition = True
for_count = 5
```

## Conclusion

Keywords are special reserved words that define Python's syntax and structure. Examples include `if`, `else`, `for`, `while`, `def`, `class`, `True`, and `False`. Understanding keywords is essential before learning **if-else statements, loops, functions, and object-oriented programming**.



# Data Types in Python

A **Data Type** specifies what kind of value a variable can store, such as numbers, text, or collections of data.

## Why Data Types Are Important?

* They determine what operations can be performed on data.
* They help Python manage memory efficiently.

---

# Main Data Types in Python

## 1. Numeric Data Types

### Integer (`int`)

Stores whole numbers.

```python
age = 20
print(type(age))
```

**Output:**

```python
<class 'int'>
```

### Float (`float`)

Stores decimal numbers.

```python
price = 99.99
print(type(price))
```

**Output:**

```python
<class 'float'>
```

### Complex (`complex`)

Stores complex numbers.

```python
x = 3 + 4j
print(type(x))
```

**Output:**

```python
<class 'complex'>
```

---

## 2. String (`str`)

A string is a sequence of characters enclosed in quotes.

```python
name = "Anish"
print(type(name))
```

**Output:**

```python
<class 'str'>
```

---

## 3. Boolean (`bool`)

Stores only two values: `True` or `False`.

```python
is_student = True
print(type(is_student))
```

**Output:**

```python
<class 'bool'>
```

---

## 4. List (`list`)

An ordered, mutable collection of items.

```python
fruits = ["Apple", "Banana", "Mango"]
print(type(fruits))
```

**Output:**

```python
<class 'list'>
```

### Features:

* Ordered
* Changeable (Mutable)
* Allows duplicate values

---

## 5. Tuple (`tuple`)

An ordered, immutable collection of items.

```python
colors = ("Red", "Green", "Blue")
print(type(colors))
```

**Output:**

```python
<class 'tuple'>
```

### Features:

* Ordered
* Cannot be modified
* Allows duplicates

---

## 6. Set (`set`)

An unordered collection of unique items.

```python
numbers = {1, 2, 3, 4}
print(type(numbers))
```

**Output:**

```python
<class 'set'>
```

### Features:

* Unordered
* No duplicate values
* Mutable

---

## 7. Dictionary (`dict`)

Stores data in **key-value pairs**.

```python
student = {
    "name": "Anish",
    "age": 20
}

print(type(student))
```

**Output:**

```python
<class 'dict'>
```

### Features:

* Key-value pairs
* Mutable
* Fast data access

---

# Checking Data Types

Use the `type()` function.

```python
x = 100
print(type(x))
```

---

# Type Conversion

### Integer to Float

```python
x = 10
y = float(x)

print(y)
```

**Output:**

```python
10.0
```

### Float to Integer

```python
x = 10.8
y = int(x)

print(y)
```

**Output:**

```python
10
```

### Integer to String

```python
x = 100
y = str(x)

print(y)
```

**Output:**

```python
100
```

---

# Summary Table

| Data Type | Example            |
| --------- | ------------------ |
| `int`     | `10`               |
| `float`   | `10.5`             |
| `complex` | `3+4j`             |
| `str`     | `"Hello"`          |
| `bool`    | `True`, `False`    |
| `list`    | `[1,2,3]`          |
| `tuple`   | `(1,2,3)`          |
| `set`     | `{1,2,3}`          |
| `dict`    | `{"name":"Anish"}` |

## Interview/Exam Question

**Q: What are the built-in data types in Python?**

**Answer:** Python provides several built-in data types:

* Numeric (`int`, `float`, `complex`)
* String (`str`)
* Boolean (`bool`)
* List (`list`)
* Tuple (`tuple`)
* Set (`set`)
* Dictionary (`dict`)

These data types are used to store and manipulate different kinds of data in Python programs.


# Conditional Statements in Python

**Conditional statements** are used to make decisions in a program. They execute different blocks of code based on whether a condition is **True** or **False**.

---

# 1. `if` Statement

The `if` statement executes a block of code only if the condition is true.

### Syntax

```python
if condition:
    # code
```

### Example

```python
age = 20

if age >= 18:
    print("You are eligible to vote.")
```

**Output:**

```python
You are eligible to vote.
```

---

# 2. `if-else` Statement

Used when you want one block to execute if the condition is true and another if it is false.

### Syntax

```python
if condition:
    # code if true
else:
    # code if false
```

### Example

```python
age = 16

if age >= 18:
    print("Adult")
else:
    print("Minor")
```

**Output:**

```python
Minor
```

---

# 3. `if-elif-else` Statement

Used when there are multiple conditions.

### Syntax

```python
if condition1:
    # code
elif condition2:
    # code
else:
    # code
```

### Example

```python
marks = 85

if marks >= 90:
    print("Grade A+")
elif marks >= 75:
    print("Grade A")
elif marks >= 60:
    print("Grade B")
else:
    print("Grade C")
```

**Output:**

```python
Grade A
```

---

# 4. Nested `if` Statement

An `if` statement inside another `if` statement.

### Example

```python
age = 20
citizen = True

if age >= 18:
    if citizen:
        print("Eligible to vote")
```

**Output:**

```python
Eligible to vote
```

---

# 5. Short-Hand `if`

### Example

```python
age = 20

if age >= 18: print("Adult")
```

---

# 6. Short-Hand `if-else` (Ternary Operator)

### Syntax

```python
value_if_true if condition else value_if_false
```

### Example

```python
age = 20

result = "Adult" if age >= 18 else "Minor"
print(result)
```

**Output:**

```python
Adult
```

---

# Flowchart of if-else

```text
        Condition?
         /    \
      True   False
       |       |
   Statement1 Statement2
```

---

# Real-Life Example

### Even or Odd Number

```python
num = int(input("Enter a number: "))

if num % 2 == 0:
    print("Even Number")
else:
    print("Odd Number")
```

---

# Comparison Operators Used in Conditions

| Operator | Meaning                  |
| -------- | ------------------------ |
| `==`     | Equal to                 |
| `!=`     | Not equal to             |
| `>`      | Greater than             |
| `<`      | Less than                |
| `>=`     | Greater than or equal to |
| `<=`     | Less than or equal to    |

### Example

```python
x = 10

if x > 5:
    print("Greater")
```

---

# Logical Operators in Conditions

| Operator | Meaning                      |
| -------- | ---------------------------- |
| `and`    | Both conditions must be true |
| `or`     | At least one condition true  |
| `not`    | Reverses the result          |

### Example

```python
age = 20
salary = 30000

if age >= 18 and salary >= 25000:
    print("Eligible")
```

---

# Summary

| Statement          | Purpose                            |
| ------------------ | ---------------------------------- |
| `if`               | Check one condition                |
| `if-else`          | Two possible outcomes              |
| `if-elif-else`     | Multiple conditions                |
| `nested if`        | Condition inside another condition |
| `ternary operator` | Short form of if-else              |

## Practice Questions

1. Check whether a number is positive, negative, or zero.
2. Find the largest of two numbers.
3. Find the largest of three numbers.
4. Check whether a year is a leap year.
5. Check whether a student passed or failed (passing marks = 40).

These are very common **BCA exam, interview, and coding practice** questions on conditional statements.


# Loops in Python

A **loop** is used to execute a block of code repeatedly until a condition is satisfied.

### Why Use Loops?

Instead of writing the same code multiple times, we use loops.

### Without Loop

```python
print("Hello")
print("Hello")
print("Hello")
print("Hello")
print("Hello")
```

### With Loop

```python
for i in range(5):
    print("Hello")
```

---

# Types of Loops in Python

1. **for Loop**
2. **while Loop**

---

# 1. for Loop

The `for` loop is used when the number of iterations is known.

### Syntax

```python
for variable in sequence:
    # code
```

### Example

```python
for i in range(5):
    print(i)
```

**Output**

```python
0
1
2
3
4
```

---

## range() Function

The `range()` function generates a sequence of numbers.

### range(stop)

```python
for i in range(5):
    print(i)
```

Output:

```python
0 1 2 3 4
```

### range(start, stop)

```python
for i in range(1, 6):
    print(i)
```

Output:

```python
1 2 3 4 5
```

### range(start, stop, step)

```python
for i in range(1, 10, 2):
    print(i)
```

Output:

```python
1 3 5 7 9
```

---

# Looping Through a String

```python
name = "Python"

for ch in name:
    print(ch)
```

Output:

```python
P
y
t
h
o
n
```

---

# Looping Through a List

```python
fruits = ["Apple", "Banana", "Mango"]

for fruit in fruits:
    print(fruit)
```

Output:

```python
Apple
Banana
Mango
```

---

# 2. while Loop

The `while` loop runs as long as the condition is True.

### Syntax

```python
while condition:
    # code
```

### Example

```python
i = 1

while i <= 5:
    print(i)
    i += 1
```

Output:

```python
1
2
3
4
5
```

---

# Infinite Loop

```python
while True:
    print("Hello")
```

⚠️ This loop runs forever until manually stopped.

---

# break Statement

Used to exit a loop immediately.

### Example

```python
for i in range(1, 10):
    if i == 5:
        break
    print(i)
```

Output:

```python
1
2
3
4
```

---

# continue Statement

Used to skip the current iteration.

### Example

```python
for i in range(1, 6):
    if i == 3:
        continue
    print(i)
```

Output:

```python
1
2
4
5
```

---

# pass Statement

Used as a placeholder when no code is written yet.

```python
for i in range(5):
    pass
```

---

# Nested Loops

A loop inside another loop.

### Example

```python
for i in range(1, 4):
    for j in range(1, 4):
        print(i, j)
```

Output:

```python
1 1
1 2
1 3
2 1
2 2
2 3
3 1
3 2
3 3
```

---

# Pattern Example

```python
for i in range(5):
    print("*" * (i + 1))
```

Output:

```python
*
**
***
****
*****
```

---

# Difference Between for and while

| for Loop                       | while Loop                       |
| ------------------------------ | -------------------------------- |
| Used when iterations are known | Used when iterations are unknown |
| Simpler syntax                 | Requires condition update        |
| Less chance of infinite loop   | More chance of infinite loop     |

---

# Summary

| Loop        | Purpose                        |
| ----------- | ------------------------------ |
| `for`       | Iterate over a sequence        |
| `while`     | Repeat while condition is true |
| `break`     | Exit loop                      |
| `continue`  | Skip iteration                 |
| `pass`      | Placeholder                    |
| Nested Loop | Loop inside loop               |

## Practice Questions

1. Print numbers from 1 to 100.
2. Print even numbers from 1 to 50.
3. Find the sum of first N natural numbers.
4. Print a multiplication table of a number.
5. Print star patterns.
6. Find factorial of a number.
7. Reverse a number using a loop.

These are the most common **BCA exam, interview, and coding practice** questions on loops.



# Functions in Python

A **function** is a block of code that performs a specific task and can be reused whenever needed.

### Why Use Functions?

* Avoid code repetition.
* Make programs modular and organized.
* Improve readability and maintenance.

---

# Defining a Function

Use the `def` keyword to create a function.

### Syntax

```python
def function_name():
    # code
```

### Example

```python
def greet():
    print("Hello, Python!")

greet()
```

**Output:**

```python
Hello, Python!
```

---

# Function with Parameters

Parameters allow us to pass data to a function.

### Example

```python
def greet(name):
    print("Hello,", name)

greet("Anish")
```

**Output:**

```python
Hello, Anish
```

---

# Function with Multiple Parameters

```python
def add(a, b):
    print(a + b)

add(10, 20)
```

**Output:**

```python
30
```

---

# Function with Return Value

The `return` statement sends a result back to the caller.

```python
def add(a, b):
    return a + b

result = add(10, 20)
print(result)
```

**Output:**

```python
30
```

---

# Types of Functions

## 1. No Arguments, No Return Value

```python
def show():
    print("Python")

show()
```

---

## 2. Arguments, No Return Value

```python
def show(name):
    print(name)

show("Anish")
```

---

## 3. No Arguments, Return Value

```python
def get_num():
    return 100

print(get_num())
```

---

## 4. Arguments and Return Value

```python
def square(n):
    return n * n

print(square(5))
```

**Output:**

```python
25
```

---

# Default Arguments

```python
def greet(name="Guest"):
    print("Hello", name)

greet()
greet("Anish")
```

**Output:**

```python
Hello Guest
Hello Anish
```

---

# Keyword Arguments

```python
def student(name, age):
    print(name, age)

student(age=20, name="Anish")
```

---

# Variable-Length Arguments (`*args`)

Used when the number of arguments is unknown.

```python
def add(*numbers):
    print(sum(numbers))

add(1, 2, 3, 4, 5)
```

**Output:**

```python
15
```

---

# Lambda Function

A small anonymous function.

### Syntax

```python
lambda arguments: expression
```

### Example

```python
square = lambda x: x * x

print(square(5))
```

**Output:**

```python
25
```

---

# Recursive Function

A function that calls itself.

### Example: Factorial

```python
def factorial(n):
    if n == 1:
        return 1
    return n * factorial(n - 1)

print(factorial(5))
```

**Output:**

```python
120
```

---

# Local and Global Variables

### Local Variable

```python
def test():
    x = 10
    print(x)

test()
```

### Global Variable

```python
x = 100

def test():
    print(x)

test()
```

---

# Built-in Functions

Python provides many built-in functions.

Examples:

```python
print(len("Python"))
print(max(10, 20, 30))
print(min(10, 20, 30))
print(sum([1, 2, 3, 4]))
```

---

# Advantages of Functions

* Code Reusability
* Better Organization
* Easier Debugging
* Improved Readability
* Modular Programming

---

# Summary

| Term      | Description                     |
| --------- | ------------------------------- |
| `def`     | Defines a function              |
| Parameter | Variable in function definition |
| Argument  | Value passed to a function      |
| `return`  | Returns a value                 |
| `*args`   | Multiple positional arguments   |
| Lambda    | Anonymous function              |
| Recursion | Function calling itself         |

## Practice Questions

1. Write a function to find the square of a number.
2. Write a function to check whether a number is even or odd.
3. Write a function to find the factorial of a number.
4. Write a function to find the largest of three numbers.
5. Write a recursive function to calculate Fibonacci numbers.

### Exam Definition

**Function:** A function is a reusable block of code that performs a specific task. Functions are defined using the `def` keyword and can accept parameters and return values. They help reduce code duplication and improve program organization.


# `pass` in Functions (Python)

The **`pass`** statement is a **null statement** in Python. It does nothing when executed.

It is used as a **placeholder** when you want to define a function but do not want to write its code yet.

---

## Syntax

```python
def function_name():
    pass
```

---

## Example 1: Empty Function

```python
def greet():
    pass

greet()
```

**Output:**

```python
```

(No output, no error)

---

## Why Use `pass`?

Suppose you are designing a program and want to create functions first, but implement them later.

```python
def login():
    pass

def register():
    pass

def logout():
    pass
```

This code runs without errors even though the functions have no implementation yet.

---

## Without `pass`

```python
def greet():
```

❌ This will cause an **IndentationError** because Python expects some code inside the function.

---

## `pass` vs `return`

### Using `pass`

```python
def test():
    pass

print(test())
```

**Output:**

```python
None
```

### Using `return`

```python
def test():
    return 10

print(test())
```

**Output:**

```python
10
```

### Difference

| `pass`               | `return`                  |
| -------------------- | ------------------------- |
| Does nothing         | Returns a value           |
| Placeholder          | Ends function execution   |
| Used for future code | Used to send results back |

---

## Example in Class

```python
class Student:
    pass
```

This creates an empty class without errors.

---

## Example in Conditional Statements

```python
age = 20

if age > 18:
    pass
else:
    print("Minor")
```

---

## Important Points

* `pass` is a placeholder statement.
* It does not perform any action.
* Useful during development when code is not ready.
* Can be used in functions, loops, classes, and conditional statements.

### Exam Definition

**Pass Statement:** The `pass` statement is a null statement in Python that performs no operation. It is used as a placeholder where code is required syntactically but has not been written yet.


# Global and Local Variables in Python

Variables in Python are classified based on where they are declared.

There are two types:

1. **Local Variables**
2. **Global Variables**

---

# 1. Local Variable

A variable declared **inside a function** is called a **local variable**.

* It can only be accessed inside that function.
* It is created when the function is called and destroyed when the function ends.

### Example

```python
def show():
    x = 10   # Local variable
    print(x)

show()
```

**Output:**

```python
10
```

### Error Example

```python
def show():
    x = 10

show()
print(x)
```

**Output:**

```python
NameError: name 'x' is not defined
```

Because `x` is local to the function.

---

# 2. Global Variable

A variable declared **outside all functions** is called a **global variable**.

* It can be accessed from anywhere in the program.
* It exists throughout the program execution.

### Example

```python
x = 100   # Global variable

def show():
    print(x)

show()
print(x)
```

**Output:**

```python
100
100
```

---

# Accessing Global Variables Inside Functions

```python
name = "Anish"

def display():
    print(name)

display()
```

**Output:**

```python
Anish
```

---

# Modifying a Global Variable

If you try to modify a global variable inside a function, Python treats it as a local variable.

### Wrong Way

```python
x = 10

def change():
    x = x + 5
    print(x)

change()
```

❌ Error occurs.

---

# Using `global` Keyword

To modify a global variable inside a function, use the `global` keyword.

### Example

```python
x = 10

def change():
    global x
    x = x + 5

change()
print(x)
```

**Output:**

```python
15
```

---

# Local and Global Variable with Same Name

```python
x = 100

def test():
    x = 50
    print("Local:", x)

test()
print("Global:", x)
```

**Output:**

```python
Local: 50
Global: 100
```

The local variable has higher priority inside the function.

---

# Example Program

```python
count = 0

def increment():
    global count
    count += 1

increment()
increment()

print(count)
```

**Output:**

```python
2
```

---

# Difference Between Local and Global Variables

| Local Variable                       | Global Variable                   |
| ------------------------------------ | --------------------------------- |
| Declared inside a function           | Declared outside functions        |
| Accessible only inside that function | Accessible throughout the program |
| Created when function starts         | Exists for entire program         |
| Cannot be used outside function      | Can be used anywhere              |

---

# Scope of Variables

```text
Global Scope
│
├── Function
│   └── Local Scope
│
└── Function
    └── Local Scope
```

* **Global Scope:** Visible everywhere.
* **Local Scope:** Visible only inside the function.

---

# Interview / Exam Question

### What is the difference between local and global variables?

**Answer:**

A **local variable** is declared inside a function and can only be accessed within that function. A **global variable** is declared outside all functions and can be accessed throughout the program. To modify a global variable inside a function, the `global` keyword is used.

### Quick Example

```python
x = 100      # Global

def demo():
    y = 50   # Local
    print(x)
    print(y)

demo()
```

Here:

* `x` is a **global variable**.
* `y` is a **local variable**.


# Recursion in Python

**Recursion** is a technique where a function calls itself to solve a problem.

A recursive function keeps calling itself until it reaches a **base case** (stopping condition).

---

# Structure of Recursion

```python
def function_name():
    if base_condition:
        return

    function_name()  # Recursive call
```

A recursive function has two parts:

1. **Base Case** → Stops recursion.
2. **Recursive Case** → Function calls itself.

---

# Example 1: Print Numbers 1 to 5

```python
def print_numbers(n):
    if n == 6:      # Base Case
        return

    print(n)
    print_numbers(n + 1)  # Recursive Call

print_numbers(1)
```

**Output:**

```python
1
2
3
4
5
```

---

# Example 2: Factorial Using Recursion

### Formula

n! = n \times (n-1)!

```python
def factorial(n):
    if n == 0 or n == 1:
        return 1

    return n * factorial(n - 1)

print(factorial(5))
```

**Output:**

```python
120
```

### Working

```text
factorial(5)
= 5 * factorial(4)
= 5 * 4 * factorial(3)
= 5 * 4 * 3 * factorial(2)
= 5 * 4 * 3 * 2 * factorial(1)
= 5 * 4 * 3 * 2 * 1
= 120
```

---

# Example 3: Sum of First N Natural Numbers

```python
def sum_n(n):
    if n == 1:
        return 1

    return n + sum_n(n - 1)

print(sum_n(5))
```

**Output:**

```python
15
```

---

# Example 4: Fibonacci Series

```python
def fibonacci(n):
    if n <= 1:
        return n

    return fibonacci(n - 1) + fibonacci(n - 2)

print(fibonacci(6))
```

**Output:**

```python
8
```

---

# Recursion Tree (Factorial of 4)

```text
factorial(4)
    |
    4 * factorial(3)
            |
            3 * factorial(2)
                    |
                    2 * factorial(1)
                            |
                            1
```

Then the function returns back:

```text
1
2 × 1 = 2
3 × 2 = 6
4 × 6 = 24
```

---

# Advantages of Recursion

✅ Makes code shorter and cleaner.

✅ Useful for:

* Tree Traversal
* Graph Algorithms (DFS)
* Divide and Conquer
* Backtracking

---

# Disadvantages of Recursion

❌ Uses more memory (function call stack).

❌ Can be slower than loops.

❌ Too many recursive calls may cause:

```python
RecursionError: maximum recursion depth exceeded
```

---

# Recursion vs Loop

| Recursion                   | Loop                           |
| --------------------------- | ------------------------------ |
| Function calls itself       | Repeats using `for` or `while` |
| Easier for complex problems | Usually faster                 |
| Uses stack memory           | Uses less memory               |
| Good for trees and graphs   | Good for simple repetitions    |

---

# Important Terms

### Base Case

Condition that stops recursion.

```python
if n == 1:
    return 1
```

### Recursive Call

Function calling itself.

```python
return n * factorial(n - 1)
```

---

# Interview / Exam Definition

**Recursion** is a programming technique in which a function calls itself repeatedly to solve a problem. Every recursive function must have a **base case** to stop the recursion and a **recursive case** that moves the problem toward the base case.

## Practice Questions

1. Find factorial of a number using recursion.
2. Find the sum of first N natural numbers.
3. Print numbers from 1 to N using recursion.
4. Reverse a string using recursion.
5. Find Fibonacci numbers using recursion.

Since you're learning **DSA and LeetCode**, recursion is extremely important because it is the foundation for **Backtracking, Trees, DFS, Dynamic Programming, and Graph algorithms**.


# `*args` and `**kwargs` in Python Functions

Sometimes we don't know how many arguments a function will receive. Python provides:

* `*args` → Variable number of **positional arguments**
* `**kwargs` → Variable number of **keyword arguments**

---

# 1. `*args`

`*args` allows a function to accept any number of positional arguments.

### Syntax

```python
def function_name(*args):
    pass
```

Here, `args` is treated as a **tuple**.

### Example

```python
def add(*args):
    print(args)

add(10, 20, 30)
```

**Output:**

```python
(10, 20, 30)
```

---

## Using `*args` to Calculate Sum

```python
def add(*args):
    total = 0

    for num in args:
        total += num

    return total

print(add(10, 20))
print(add(10, 20, 30, 40))
```

**Output:**

```python
30
100
```

---

## Accessing Individual Values

```python
def show(*args):
    print(args[0])
    print(args[1])

show("Python", "Java")
```

**Output:**

```python
Python
Java
```

---

# 2. `**kwargs`

`**kwargs` allows a function to accept any number of keyword arguments.

### Syntax

```python
def function_name(**kwargs):
    pass
```

Here, `kwargs` is treated as a **dictionary**.

### Example

```python
def student(**kwargs):
    print(kwargs)

student(name="Anish", age=20)
```

**Output:**

```python
{'name': 'Anish', 'age': 20}
```

---

## Accessing Values

```python
def student(**kwargs):
    print(kwargs["name"])
    print(kwargs["age"])

student(name="Anish", age=20)
```

**Output:**

```python
Anish
20
```

---

## Loop Through `kwargs`

```python
def student(**kwargs):
    for key, value in kwargs.items():
        print(key, ":", value)

student(name="Anish", age=20, city="Delhi")
```

**Output:**

```python
name : Anish
age : 20
city : Delhi
```

---

# Using Both `*args` and `**kwargs`

```python
def display(*args, **kwargs):
    print("Args:", args)
    print("Kwargs:", kwargs)

display(10, 20, 30, name="Anish", city="Delhi")
```

**Output:**

```python
Args: (10, 20, 30)
Kwargs: {'name': 'Anish', 'city': 'Delhi'}
```

---

# Order of Parameters

When using all types of parameters, the order should be:

```python
def func(normal, *args, **kwargs):
    pass
```

### Example

```python
def info(name, *args, **kwargs):
    print(name)
    print(args)
    print(kwargs)

info("Anish", 20, 30, city="Delhi")
```

---

# Difference Between `*args` and `**kwargs`

| `*args`                      | `**kwargs`                |
| ---------------------------- | ------------------------- |
| Accepts positional arguments | Accepts keyword arguments |
| Stored as a tuple            | Stored as a dictionary    |
| Uses single `*`              | Uses double `**`          |
| Example: `10,20,30`          | Example: `name="Anish"`   |

---

# Real-World Example

```python
def employee(name, *skills, **details):
    print("Name:", name)

    print("Skills:")
    for skill in skills:
        print(skill)

    print("Details:")
    for key, value in details.items():
        print(key, value)

employee(
    "Anish",
    "Python",
    "Java",
    age=20,
    city="Delhi"
)
```

**Output:**

```python
Name: Anish

Skills:
Python
Java

Details:
age 20
city Delhi
```

---

# Interview / Exam Definition

### `*args`

`*args` allows a function to accept a variable number of positional arguments. The arguments are stored as a tuple.

### `**kwargs`

`**kwargs` allows a function to accept a variable number of keyword arguments. The arguments are stored as a dictionary.

### Key Point

* `*args` → Tuple → Positional arguments
* `**kwargs` → Dictionary → Keyword arguments

These are widely used in frameworks like Django and APIs where the number of arguments may vary.



# First-Class Functions in Python

A **First-Class Function** means that functions are treated like any other object (such as integers, strings, or lists).

In Python, functions can:

1. Be assigned to a variable.
2. Be passed as an argument to another function.
3. Be returned from another function.
4. Be stored in data structures like lists or dictionaries.

---

# 1. Function Assigned to a Variable

```python
def greet():
    print("Hello Python")

msg = greet

msg()
```

**Output:**

```python
Hello Python
```

Here, `msg` refers to the same function as `greet`.

---

# 2. Function Passed as an Argument

```python
def greet(name):
    return f"Hello {name}"

def display(func):
    print(func("Anish"))

display(greet)
```

**Output:**

```python
Hello Anish
```

Here, `greet` is passed as an argument to `display`.

---

# 3. Function Returned from Another Function

```python
def outer():
    def inner():
        print("Inside Inner Function")

    return inner

result = outer()
result()
```

**Output:**

```python
Inside Inner Function
```

The `outer()` function returns another function.

---

# 4. Function Stored in a List

```python
def add():
    print("Add")

def delete():
    print("Delete")

operations = [add, delete]

operations[0]()
operations[1]()
```

**Output:**

```python
Add
Delete
```

---

# Real-Life Example

```python
def square(x):
    return x * x

def cube(x):
    return x * x * x

def calculate(func, num):
    return func(num)

print(calculate(square, 5))
print(calculate(cube, 5))
```

**Output:**

```python
25
125
```

---

# Why First-Class Functions Are Important?

They are the foundation of:

* Lambda Functions
* Decorators
* Closures
* Callbacks
* Functional Programming

For example:

```python
numbers = [1, 2, 3, 4]

result = list(map(lambda x: x * 2, numbers))

print(result)
```

**Output:**

```python
[2, 4, 6, 8]
```

---

# First-Class Function vs Function Call

### Function Reference

```python
greet
```

Refers to the function itself.

### Function Call

```python
greet()
```

Executes the function.

Example:

```python
def greet():
    print("Hello")

x = greet      # Reference
x()            # Call
```

---

# Interview / Exam Definition

**First-Class Function:**
A function is called a first-class function if it can be treated like any other object. In Python, functions can be assigned to variables, passed as arguments, returned from other functions, and stored in data structures.

### Key Points

✅ Functions are objects in Python.

✅ Functions can be:

* Assigned to variables
* Passed as arguments
* Returned from functions
* Stored in lists, tuples, and dictionaries

This feature makes Python very powerful and enables advanced concepts such as **decorators, closures, callbacks, and functional programming**.


# Lambda Function in Python

A **Lambda Function** is a small anonymous (nameless) function in Python.

It is used when you need a simple function for a short period of time.

---

# Syntax

```python
lambda arguments: expression
```

* `lambda` → Keyword used to create a lambda function.
* Arguments → Input values.
* Expression → Single expression whose result is returned.

---

# Normal Function vs Lambda Function

### Normal Function

```python
def square(x):
    return x * x

print(square(5))
```

**Output:**

```python
25
```

### Lambda Function

```python
square = lambda x: x * x

print(square(5))
```

**Output:**

```python
25
```

---

# Example 1: Addition of Two Numbers

```python
add = lambda a, b: a + b

print(add(10, 20))
```

**Output:**

```python
30
```

---

# Example 2: Find Larger Number

```python
maximum = lambda a, b: a if a > b else b

print(maximum(10, 20))
```

**Output:**

```python
20
```

---

# Example 3: Multiple Arguments

```python
multiply = lambda a, b, c: a * b * c

print(multiply(2, 3, 4))
```

**Output:**

```python
24
```

---

# Using Lambda with `map()`

`map()` applies a function to every element of a sequence.

```python
numbers = [1, 2, 3, 4]

result = list(map(lambda x: x * 2, numbers))

print(result)
```

**Output:**

```python
[2, 4, 6, 8]
```

---

# Using Lambda with `filter()`

`filter()` selects elements based on a condition.

```python
numbers = [1, 2, 3, 4, 5, 6]

result = list(filter(lambda x: x % 2 == 0, numbers))

print(result)
```

**Output:**

```python
[2, 4, 6]
```

---

# Using Lambda with `sorted()`

```python
students = [
    ("Anish", 80),
    ("Rahul", 95),
    ("Aman", 70)
]

result = sorted(students, key=lambda x: x[1])

print(result)
```

**Output:**

```python
[('Aman', 70), ('Anish', 80), ('Rahul', 95)]
```

---

# Characteristics of Lambda Functions

✅ Anonymous (No Name)

✅ Can have multiple arguments

✅ Contains only one expression

✅ Automatically returns the result

❌ Cannot contain multiple statements

❌ Not suitable for complex logic

---

# Difference Between `def` and `lambda`

| `def` Function              | `lambda` Function           |
| --------------------------- | --------------------------- |
| Has a name                  | Anonymous                   |
| Multiple statements allowed | Only one expression         |
| Uses `return` keyword       | Returns automatically       |
| Better for complex logic    | Better for short operations |

---

# Real-World Example

```python
employees = [
    {"name": "Anish", "salary": 50000},
    {"name": "Rahul", "salary": 70000},
    {"name": "Aman", "salary": 60000}
]

employees.sort(key=lambda emp: emp["salary"])

print(employees)
```

This sorts employees by salary.

---

# Interview / Exam Definition

**Lambda Function:**
A lambda function is a small anonymous function created using the `lambda` keyword. It can take any number of arguments but contains only one expression, whose value is automatically returned.

### Key Points

* Created using `lambda`
* No function name
* Single expression only
* Commonly used with `map()`, `filter()`, and `sorted()`

### Practice Questions

1. Create a lambda function to find the square of a number.
2. Create a lambda function to find the maximum of two numbers.
3. Use `map()` with lambda to double all numbers in a list.
4. Use `filter()` with lambda to find odd numbers.
5. Sort a list of tuples using lambda.

For **DSA, Machine Learning, and Data Science**, you'll frequently see lambda functions used with `sort()`, `map()`, `filter()`, and data-processing operations.


# `map()`, `filter()`, and `reduce()` in Python

These are powerful built-in functions used in **functional programming** to process collections like lists, tuples, etc.

---

# 1. `map()` Function

`map()` applies a function to every element of an iterable (list, tuple, etc.).

### Syntax

```python
map(function, iterable)
```

### Example 1

```python
numbers = [1, 2, 3, 4, 5]

result = list(map(lambda x: x * 2, numbers))

print(result)
```

**Output:**

```python
[2, 4, 6, 8, 10]
```

### Example 2

```python
def square(x):
    return x * x

numbers = [1, 2, 3, 4]

result = list(map(square, numbers))

print(result)
```

**Output:**

```python
[1, 4, 9, 16]
```

---

# 2. `filter()` Function

`filter()` selects elements that satisfy a condition.

### Syntax

```python
filter(function, iterable)
```

The function must return `True` or `False`.

### Example 1: Even Numbers

```python
numbers = [1, 2, 3, 4, 5, 6]

result = list(filter(lambda x: x % 2 == 0, numbers))

print(result)
```

**Output:**

```python
[2, 4, 6]
```

### Example 2: Numbers Greater Than 10

```python
numbers = [5, 12, 8, 15, 3]

result = list(filter(lambda x: x > 10, numbers))

print(result)
```

**Output:**

```python
[12, 15]
```

---

# 3. `reduce()` Function

`reduce()` repeatedly applies a function to the elements of a sequence and returns a single value.

### Import Required

```python
from functools import reduce
```

### Syntax

```python
reduce(function, iterable)
```

### Example 1: Sum of Numbers

```python
from functools import reduce

numbers = [1, 2, 3, 4, 5]

result = reduce(lambda x, y: x + y, numbers)

print(result)
```

**Output:**

```python
15
```

### Working

```text
1 + 2 = 3
3 + 3 = 6
6 + 4 = 10
10 + 5 = 15
```

---

### Example 2: Product of Numbers

```python
from functools import reduce

numbers = [1, 2, 3, 4]

result = reduce(lambda x, y: x * y, numbers)

print(result)
```

**Output:**

```python
24
```

---

# Comparison Example

Suppose we have:

```python
numbers = [1, 2, 3, 4, 5]
```

### `map()`

```python
list(map(lambda x: x * 2, numbers))
```

**Output:**

```python
[2, 4, 6, 8, 10]
```

### `filter()`

```python
list(filter(lambda x: x % 2 == 0, numbers))
```

**Output:**

```python
[2, 4]
```

### `reduce()`

```python
reduce(lambda x, y: x + y, numbers)
```

**Output:**

```python
15
```

---

# Difference Between map, filter, and reduce

| Function   | Purpose                             | Output                         |
| ---------- | ----------------------------------- | ------------------------------ |
| `map()`    | Transform each element              | Iterable of transformed values |
| `filter()` | Select elements based on condition  | Iterable of filtered values    |
| `reduce()` | Combine all elements into one value | Single value                   |

---

# Real-Life Example

```python
from functools import reduce

marks = [45, 80, 60, 30, 90]

# Pass marks
passed = list(filter(lambda x: x >= 40, marks))

# Add 5 grace marks
updated = list(map(lambda x: x + 5, passed))

# Total marks
total = reduce(lambda x, y: x + y, updated)

print("Passed:", passed)
print("Updated:", updated)
print("Total:", total)
```

---

# Interview / Exam Definitions

### `map()`

`map()` applies a function to every element of an iterable and returns the transformed values.

### `filter()`

`filter()` selects elements from an iterable based on a condition and returns only those that satisfy it.

### `reduce()`

`reduce()` repeatedly applies a function to the elements of an iterable and reduces them to a single value.

## Quick Memory Trick

* **map → Modify** each item
* **filter → Select** some items
* **reduce → Combine** all items into one result

These functions are heavily used in **Data Science, Machine Learning, Python interviews, and functional programming**.


# Inner Function (Nested Function) in Python

An **Inner Function** is a function defined inside another function.

The outer function is called the **enclosing function**, and the function inside it is called the **inner function** or **nested function**.

---

# Syntax

```python
def outer():
    
    def inner():
        print("Inner Function")
    
    inner()
```

---

# Example 1: Basic Inner Function

```python
def outer():
    
    def inner():
        print("Hello from Inner Function")
    
    inner()

outer()
```

**Output:**

```python
Hello from Inner Function
```

---

# Why Use Inner Functions?

* To hide helper functions from the outside world.
* To organize code better.
* To create closures and decorators.

---

# Example 2: Accessing Outer Function Variables

```python
def outer():
    message = "Hello Python"

    def inner():
        print(message)

    inner()

outer()
```

**Output:**

```python
Hello Python
```

### Explanation

The inner function can access variables of the outer function.

This is called **Lexical Scoping**.

---

# Example 3: Returning an Inner Function

```python
def outer():

    def inner():
        print("I am Inner Function")

    return inner

result = outer()
result()
```

**Output:**

```python
I am Inner Function
```

Here:

* `outer()` returns the `inner` function.
* `result` stores the returned function.
* `result()` executes it.

---

# Example 4: Passing Data to Inner Function

```python
def outer(name):

    def inner():
        print("Hello", name)

    inner()

outer("Anish")
```

**Output:**

```python
Hello Anish
```

---

# Example 5: Multiple Inner Functions

```python
def calculator():

    def add():
        print(10 + 20)

    def subtract():
        print(20 - 10)

    add()
    subtract()

calculator()
```

**Output:**

```python
30
10
```

---

# Scope of Inner Functions

```python
def outer():

    def inner():
        print("Hello")

    inner()

outer()
```

### Invalid

```python
def outer():

    def inner():
        print("Hello")

outer()

inner()     # Error
```

**Output:**

```python
NameError
```

Because `inner()` exists only inside `outer()`.

---

# Inner Function and Closure

```python
def outer(x):

    def inner(y):
        return x + y

    return inner

add5 = outer(5)

print(add5(10))
```

**Output:**

```python
15
```

Here the inner function remembers the value of `x` even after `outer()` has finished.

This is called a **Closure**.

---

# Difference Between Normal Function and Inner Function

| Normal Function                          | Inner Function                        |
| ---------------------------------------- | ------------------------------------- |
| Defined independently                    | Defined inside another function       |
| Accessible globally (if in global scope) | Accessible only inside outer function |
| No enclosing scope                       | Can access outer function variables   |

---

# Advantages of Inner Functions

✅ Better code organization

✅ Data hiding (encapsulation)

✅ Used in closures

✅ Used in decorators

✅ Improves readability

---

# Interview / Exam Definition

**Inner Function (Nested Function):**
An inner function is a function defined inside another function. It can access the variables of the outer function and is generally used for code organization, data hiding, closures, and decorators.

### Key Points

* Function inside another function.
* Can access outer function variables.
* Not directly accessible from outside.
* Forms the basis of **closures** and **decorators**.

### Example

```python
def outer():

    def inner():
        print("Inner Function")

    inner()

outer()
```

This is the simplest example of an inner function in Python.


# Decorators in Python

A **Decorator** is a function that modifies or extends the behavior of another function **without changing its original code**.

Decorators are built using **first-class functions**, **inner functions**, and **closures**.

---

# Why Use Decorators?

Suppose you want to add extra functionality (logging, timing, authentication, etc.) to many functions.

Instead of modifying every function, you can use a decorator.

---

# Basic Decorator Structure

```python
def decorator(func):

    def wrapper():
        print("Before function call")

        func()

        print("After function call")

    return wrapper
```

---

# Example 1: Simple Decorator

```python
def decorator(func):

    def wrapper():
        print("Before")

        func()

        print("After")

    return wrapper


def greet():
    print("Hello")

greet = decorator(greet)

greet()
```

**Output:**

```python
Before
Hello
After
```

---

# Using `@` Syntax

Python provides a cleaner syntax.

```python
def decorator(func):

    def wrapper():
        print("Before")

        func()

        print("After")

    return wrapper


@decorator
def greet():
    print("Hello")

greet()
```

**Output:**

```python
Before
Hello
After
```

---

# How Decorators Work

When Python sees:

```python
@decorator
def greet():
    pass
```

It automatically does:

```python
greet = decorator(greet)
```

---

# Decorator with Arguments

```python
def decorator(func):

    def wrapper(name):
        print("Welcome")

        func(name)

    return wrapper


@decorator
def greet(name):
    print("Hello", name)

greet("Anish")
```

**Output:**

```python
Welcome
Hello Anish
```

---

# Decorator with `*args` and `**kwargs`

This allows the decorator to work with any function.

```python
def decorator(func):

    def wrapper(*args, **kwargs):
        print("Function Started")

        result = func(*args, **kwargs)

        print("Function Ended")

        return result

    return wrapper


@decorator
def add(a, b):
    return a + b

print(add(10, 20))
```

**Output:**

```python
Function Started
Function Ended
30
```

---

# Real-Life Example: Execution Time

```python
import time

def timer(func):

    def wrapper(*args, **kwargs):

        start = time.time()

        result = func(*args, **kwargs)

        end = time.time()

        print("Time:", end - start)

        return result

    return wrapper


@timer
def work():
    for i in range(1000000):
        pass

work()
```

This measures how long a function takes to execute.

---

# Multiple Decorators

```python
def deco1(func):

    def wrapper():
        print("Decorator 1")

        func()

    return wrapper


def deco2(func):

    def wrapper():
        print("Decorator 2")

        func()

    return wrapper


@deco1
@deco2
def greet():
    print("Hello")

greet()
```

**Output:**

```python
Decorator 1
Decorator 2
Hello
```

---

# Common Uses of Decorators

* Logging
* Authentication
* Authorization
* Performance Measurement
* Caching
* Input Validation
* Flask/Django Routes

Example from web development:

```python
@app.route("/")
def home():
    return "Home Page"
```

Here `@app.route()` is a decorator.

---

# Decorator Flow Diagram

```text
Function
   ↓
Decorator
   ↓
Wrapper Function
   ↓
Modified Function Execution
```

---

# Advantages of Decorators

✅ Reuse code

✅ Keep code clean

✅ Add functionality without modifying original code

✅ Follow DRY (Don't Repeat Yourself)

---

# Interview / Exam Definition

**Decorator:**
A decorator is a function that takes another function as an argument, adds extra functionality to it, and returns a new modified function without changing the original function's source code.

### Key Points

* Uses `@decorator_name` syntax.
* Based on first-class functions and closures.
* Modifies behavior of functions.
* Widely used in Python frameworks and libraries.

### Simple Example

```python
def decorator(func):

    def wrapper():
        print("Before")

        func()

        print("After")

    return wrapper


@decorator
def greet():
    print("Hello")

greet()
```

For Python interviews and advanced topics, decorators are one of the most important concepts because they are used heavily in frameworks like Django and Flask.



# Strings in Python

A **String** is a sequence of characters enclosed in single quotes (`' '`), double quotes (`" "`), or triple quotes (`''' '''` or `""" """`).

Strings are used to store text data.

---

# Creating Strings

```python
name = "Anish"
city = 'Delhi'
message = """Welcome to Python"""
```

---

# Printing a String

```python
name = "Python"

print(name)
```

**Output:**

```python
Python
```

---

# String Indexing

Each character has an index position.

```text
P  Y  T  H  O  N
0  1  2  3  4  5
```

### Example

```python
name = "Python"

print(name[0])
print(name[3])
```

**Output:**

```python
P
h
```

---

# Negative Indexing

```text
P  Y  T  H  O  N
-6 -5 -4 -3 -2 -1
```

```python
name = "Python"

print(name[-1])
```

**Output:**

```python
N
```

---

# String Slicing

Syntax:

```python
string[start:end]
```

### Example

```python
name = "Python"

print(name[0:3])
```

**Output:**

```python
Pyt
```

### More Examples

```python
name = "Python"

print(name[:4])
print(name[2:])
print(name[::2])
```

**Output:**

```python
Pyth
thon
Pto
```

---

# String Length

```python
name = "Python"

print(len(name))
```

**Output:**

```python
6
```

---

# String Concatenation

Joining strings using `+`.

```python
first = "Hello"
second = "Python"

print(first + " " + second)
```

**Output:**

```python
Hello Python
```

---

# String Repetition

```python
print("Hi " * 3)
```

**Output:**

```python
Hi Hi Hi
```

---

# String Membership

```python
name = "Python"

print("P" in name)
print("z" in name)
```

**Output:**

```python
True
False
```

---

# Important String Methods

## `upper()`

```python
name = "python"

print(name.upper())
```

Output:

```python
PYTHON
```

---

## `lower()`

```python
name = "PYTHON"

print(name.lower())
```

Output:

```python
python
```

---

## `capitalize()`

```python
name = "python"

print(name.capitalize())
```

Output:

```python
Python
```

---

## `title()`

```python
text = "hello world"

print(text.title())
```

Output:

```python
Hello World
```

---

## `strip()`

Removes extra spaces.

```python
text = "  Python  "

print(text.strip())
```

Output:

```python
Python
```

---

## `replace()`

```python
text = "I like Java"

print(text.replace("Java", "Python"))
```

Output:

```python
I like Python
```

---

## `split()`

Converts string into a list.

```python
text = "Python Java C++"

print(text.split())
```

Output:

```python
['Python', 'Java', 'C++']
```

---

## `join()`

Joins list elements into a string.

```python
words = ["Python", "Java", "C++"]

print("-".join(words))
```

Output:

```python
Python-Java-C++
```

---

# String Immutability

Strings cannot be changed after creation.

```python
name = "Python"

name[0] = "J"
```

❌ Error

To modify:

```python
name = "Python"

name = "J" + name[1:]

print(name)
```

Output:

```python
Jython
```

---

# String Formatting

## Using f-string

```python
name = "Anish"
age = 20

print(f"My name is {name} and I am {age} years old.")
```

**Output:**

```python
My name is Anish and I am 20 years old.
```

---

# Escape Characters

| Escape Character | Meaning      |
| ---------------- | ------------ |
| `\n`             | New Line     |
| `\t`             | Tab          |
| `\\`             | Backslash    |
| `\"`             | Double Quote |
| `\'`             | Single Quote |

### Example

```python
print("Hello\nPython")
```

Output:

```python
Hello
Python
```

---

# Common String Operations

```python
text = "Python"

print(text.startswith("Py"))
print(text.endswith("on"))
print(text.count("o"))
print(text.find("h"))
```

**Output:**

```python
True
True
1
3
```

---

# Difference Between Indexing and Slicing

| Indexing              | Slicing                     |
| --------------------- | --------------------------- |
| Returns one character | Returns multiple characters |
| `s[0]`                | `s[0:3]`                    |
| Output: `P`           | Output: `Pyt`               |

---

# Interview / Exam Definition

**String:**
A string is a sequence of characters enclosed within single, double, or triple quotes. Strings are immutable in Python and support various operations such as indexing, slicing, concatenation, and formatting.

### Example

```python
name = "Python"

print(name[0])
print(name[0:3])
```

**Output:**

```python
P
Pyt
```

### Most Important String Methods for Exams

* `upper()`
* `lower()`
* `capitalize()`
* `replace()`
* `split()`
* `join()`
* `strip()`
* `find()`
* `count()`
* `startswith()`
* `endswith()`

These are frequently asked in **BCA exams, Python interviews, and coding problems**.


# List in Python

A **List** is an ordered, mutable (changeable) collection of items.

Lists can store:

* Integers
* Floats
* Strings
* Boolean values
* Other lists

---

# Creating a List

```python
numbers = [10, 20, 30, 40]
print(numbers)
```

**Output:**

```python
[10, 20, 30, 40]
```

---

# List Characteristics

✅ Ordered

✅ Mutable (can be modified)

✅ Allows duplicate values

✅ Can store different data types

```python
data = [10, "Anish", 3.14, True]
print(data)
```

**Output:**

```python
[10, 'Anish', 3.14, True]
```

---

# Accessing List Elements

## Positive Indexing

```python
fruits = ["Apple", "Banana", "Mango"]

print(fruits[0])
print(fruits[1])
```

**Output:**

```python
Apple
Banana
```

---

## Negative Indexing

```python
fruits = ["Apple", "Banana", "Mango"]

print(fruits[-1])
```

**Output:**

```python
Mango
```

---

# List Slicing

```python
numbers = [10, 20, 30, 40, 50]

print(numbers[1:4])
```

**Output:**

```python
[20, 30, 40]
```

---

# Modifying List Elements

```python
fruits = ["Apple", "Banana", "Mango"]

fruits[1] = "Orange"

print(fruits)
```

**Output:**

```python
['Apple', 'Orange', 'Mango']
```

---

# Adding Elements

## append()

Adds one element at the end.

```python
numbers = [1, 2, 3]

numbers.append(4)

print(numbers)
```

**Output:**

```python
[1, 2, 3, 4]
```

---

## insert()

Adds an element at a specific position.

```python
numbers = [1, 2, 4]

numbers.insert(2, 3)

print(numbers)
```

**Output:**

```python
[1, 2, 3, 4]
```

---

## extend()

Adds multiple elements.

```python
numbers = [1, 2]

numbers.extend([3, 4, 5])

print(numbers)
```

**Output:**

```python
[1, 2, 3, 4, 5]
```

---

# Removing Elements

## remove()

Removes the first occurrence of a value.

```python
numbers = [10, 20, 30]

numbers.remove(20)

print(numbers)
```

**Output:**

```python
[10, 30]
```

---

## pop()

Removes an element by index.

```python
numbers = [10, 20, 30]

numbers.pop(1)

print(numbers)
```

**Output:**

```python
[10, 30]
```

---

## del

```python
numbers = [10, 20, 30]

del numbers[0]

print(numbers)
```

**Output:**

```python
[20, 30]
```

---

## clear()

Removes all elements.

```python
numbers = [1, 2, 3]

numbers.clear()

print(numbers)
```

**Output:**

```python
[]
```

---

# List Operations

## Concatenation

```python
a = [1, 2]
b = [3, 4]

print(a + b)
```

**Output:**

```python
[1, 2, 3, 4]
```

---

## Repetition

```python
print([1, 2] * 3)
```

**Output:**

```python
[1, 2, 1, 2, 1, 2]
```

---

# Membership Operators

```python
fruits = ["Apple", "Banana"]

print("Apple" in fruits)
print("Mango" in fruits)
```

**Output:**

```python
True
False
```

---

# Important List Methods

## len()

```python
numbers = [1, 2, 3]

print(len(numbers))
```

Output:

```python
3
```

---

## sort()

```python
numbers = [4, 1, 3, 2]

numbers.sort()

print(numbers)
```

Output:

```python
[1, 2, 3, 4]
```

---

## reverse()

```python
numbers = [1, 2, 3]

numbers.reverse()

print(numbers)
```

Output:

```python
[3, 2, 1]
```

---

## count()

```python
numbers = [1, 2, 2, 3]

print(numbers.count(2))
```

Output:

```python
2
```

---

## index()

```python
numbers = [10, 20, 30]

print(numbers.index(20))
```

Output:

```python
1
```

---

# Traversing a List

## Using for Loop

```python
fruits = ["Apple", "Banana", "Mango"]

for fruit in fruits:
    print(fruit)
```

---

## Using Index

```python
fruits = ["Apple", "Banana", "Mango"]

for i in range(len(fruits)):
    print(fruits[i])
```

---

# Nested List

A list inside another list.

```python
matrix = [
    [1, 2],
    [3, 4]
]

print(matrix[0][1])
```

**Output:**

```python
2
```

---

# List Comprehension

A shorter way to create lists.

### Normal Way

```python
squares = []

for i in range(1, 6):
    squares.append(i * i)

print(squares)
```

### List Comprehension

```python
squares = [i * i for i in range(1, 6)]

print(squares)
```

**Output:**

```python
[1, 4, 9, 16, 25]
```

---

# Difference Between List and Tuple

| List          | Tuple     |
| ------------- | --------- |
| Mutable       | Immutable |
| Uses `[]`     | Uses `()` |
| More flexible | Faster    |

---

# Interview / Exam Definition

**List:**
A list is an ordered, mutable collection in Python used to store multiple items in a single variable. Lists allow duplicate values and support indexing, slicing, and various built-in methods.

### Example

```python
fruits = ["Apple", "Banana", "Mango"]

print(fruits[0])
```

**Output:**

```python
Apple
```

## Most Important List Methods

* `append()`
* `insert()`
* `extend()`
* `remove()`
* `pop()`
* `clear()`
* `sort()`
* `reverse()`
* `count()`
* `index()`

These methods are frequently asked in **BCA exams, Python interviews, and coding questions**.


# Tuple in Python

A **Tuple** is an ordered, immutable collection of items.

* **Ordered** → Elements have a fixed position (index).
* **Immutable** → Once created, elements cannot be changed.
* **Allows Duplicates** → Same value can appear multiple times.

---

# Creating a Tuple

```python
numbers = (10, 20, 30, 40)
print(numbers)
```

**Output:**

```python
(10, 20, 30, 40)
```

---

# Tuple with Different Data Types

```python
data = (10, "Anish", 3.14, True)
print(data)
```

**Output:**

```python
(10, 'Anish', 3.14, True)
```

---

# Creating a Single-Element Tuple

⚠️ A comma is required.

```python
t = (10,)
print(type(t))
```

**Output:**

```python
<class 'tuple'>
```

Without the comma:

```python
t = (10)
print(type(t))
```

**Output:**

```python
<class 'int'>
```

---

# Accessing Tuple Elements

## Positive Indexing

```python
fruits = ("Apple", "Banana", "Mango")

print(fruits[0])
print(fruits[1])
```

**Output:**

```python
Apple
Banana
```

---

## Negative Indexing

```python
fruits = ("Apple", "Banana", "Mango")

print(fruits[-1])
```

**Output:**

```python
Mango
```

---

# Tuple Slicing

```python
numbers = (10, 20, 30, 40, 50)

print(numbers[1:4])
```

**Output:**

```python
(20, 30, 40)
```

---

# Tuple is Immutable

```python
numbers = (10, 20, 30)

numbers[1] = 100
```

❌ Error:

```python
TypeError: 'tuple' object does not support item assignment
```

---

# Tuple Length

```python
numbers = (10, 20, 30)

print(len(numbers))
```

**Output:**

```python
3
```

---

# Tuple Operations

## Concatenation

```python
a = (1, 2)
b = (3, 4)

print(a + b)
```

**Output:**

```python
(1, 2, 3, 4)
```

---

## Repetition

```python
print((1, 2) * 3)
```

**Output:**

```python
(1, 2, 1, 2, 1, 2)
```

---

# Membership Operators

```python
fruits = ("Apple", "Banana", "Mango")

print("Apple" in fruits)
print("Orange" in fruits)
```

**Output:**

```python
True
False
```

---

# Important Tuple Methods

Tuples have only two built-in methods.

## `count()`

Counts occurrences of a value.

```python
numbers = (1, 2, 2, 3, 2)

print(numbers.count(2))
```

**Output:**

```python
3
```

---

## `index()`

Returns the position of a value.

```python
numbers = (10, 20, 30)

print(numbers.index(20))
```

**Output:**

```python
1
```

---

# Traversing a Tuple

```python
fruits = ("Apple", "Banana", "Mango")

for fruit in fruits:
    print(fruit)
```

**Output:**

```python
Apple
Banana
Mango
```

---

# Tuple Packing and Unpacking

## Packing

```python
student = ("Anish", 20, "Delhi")
```

## Unpacking

```python
name, age, city = student

print(name)
print(age)
print(city)
```

**Output:**

```python
Anish
20
Delhi
```

---

# Nested Tuple

```python
data = (
    (1, 2),
    (3, 4)
)

print(data[1][0])
```

**Output:**

```python
3
```

---

# Why Use Tuples?

✅ Faster than lists

✅ Less memory usage

✅ Data cannot be modified accidentally

✅ Useful for fixed data

Examples:

* Coordinates `(x, y)`
* RGB colors `(255, 0, 0)`
* Database records

---

# Difference Between List and Tuple

| List            | Tuple         |
| --------------- | ------------- |
| Mutable         | Immutable     |
| Uses `[]`       | Uses `()`     |
| More methods    | Fewer methods |
| Slightly slower | Faster        |
| More memory     | Less memory   |

---

# Interview / Exam Definition

**Tuple:**
A tuple is an ordered and immutable collection of elements in Python. Tuples allow duplicate values and support indexing, slicing, and iteration. They are created using parentheses `()`.

### Example

```python
fruits = ("Apple", "Banana", "Mango")

print(fruits[0])
```

**Output:**

```python
Apple
```

## Important Tuple Methods

* `count()`
* `index()`

Since tuples are immutable, they have fewer methods than lists.

### Common Exam Question

**Q: Why are tuples faster than lists?**

**Answer:**
Tuples are immutable, so Python can optimize their storage and access. Because they cannot be modified, they generally use less memory and are slightly faster than lists.


# Dictionary in Python

A **Dictionary** is a collection of data stored in **key-value pairs**.

* Keys are unique.
* Values can be duplicated.
* Dictionaries are **mutable** (changeable).
* Dictionaries are written using **curly braces `{}`**.

---

# Creating a Dictionary

```python
student = {
    "name": "Anish",
    "age": 20,
    "city": "Delhi"
}

print(student)
```

**Output:**

```python
{'name': 'Anish', 'age': 20, 'city': 'Delhi'}
```

---

# Accessing Values

### Using Key

```python
student = {
    "name": "Anish",
    "age": 20
}

print(student["name"])
```

**Output:**

```python
Anish
```

---

### Using `get()`

```python
student = {
    "name": "Anish",
    "age": 20
}

print(student.get("age"))
```

**Output:**

```python
20
```

---

# Adding New Elements

```python
student = {
    "name": "Anish"
}

student["age"] = 20

print(student)
```

**Output:**

```python
{'name': 'Anish', 'age': 20}
```

---

# Updating Values

```python
student = {
    "name": "Anish",
    "age": 20
}

student["age"] = 21

print(student)
```

**Output:**

```python
{'name': 'Anish', 'age': 21}
```

---

# Removing Elements

## `pop()`

```python
student = {
    "name": "Anish",
    "age": 20
}

student.pop("age")

print(student)
```

**Output:**

```python
{'name': 'Anish'}
```

---

## `del`

```python
student = {
    "name": "Anish",
    "age": 20
}

del student["age"]

print(student)
```

---

## `clear()`

```python
student = {
    "name": "Anish",
    "age": 20
}

student.clear()

print(student)
```

**Output:**

```python
{}
```

---

# Important Dictionary Methods

## `keys()`

Returns all keys.

```python
student = {
    "name": "Anish",
    "age": 20
}

print(student.keys())
```

**Output:**

```python
dict_keys(['name', 'age'])
```

---

## `values()`

Returns all values.

```python
print(student.values())
```

**Output:**

```python
dict_values(['Anish', 20])
```

---

## `items()`

Returns key-value pairs.

```python
print(student.items())
```

**Output:**

```python
dict_items([('name', 'Anish'), ('age', 20)])
```

---

## `update()`

Updates dictionary values.

```python
student = {
    "name": "Anish"
}

student.update({"age": 20})

print(student)
```

**Output:**

```python
{'name': 'Anish', 'age': 20}
```

---

# Looping Through a Dictionary

## Keys

```python
student = {
    "name": "Anish",
    "age": 20
}

for key in student:
    print(key)
```

**Output:**

```python
name
age
```

---

## Values

```python
for value in student.values():
    print(value)
```

**Output:**

```python
Anish
20
```

---

## Key-Value Pairs

```python
for key, value in student.items():
    print(key, ":", value)
```

**Output:**

```python
name : Anish
age : 20
```

---

# Nested Dictionary

```python
students = {
    "s1": {
        "name": "Anish",
        "age": 20
    },
    "s2": {
        "name": "Rahul",
        "age": 21
    }
}

print(students["s1"]["name"])
```

**Output:**

```python
Anish
```

---

# Dictionary Comprehension

### Normal Way

```python
square = {}

for i in range(1, 6):
    square[i] = i * i

print(square)
```

### Dictionary Comprehension

```python
square = {i: i * i for i in range(1, 6)}

print(square)
```

**Output:**

```python
{1: 1, 2: 4, 3: 9, 4: 16, 5: 25}
```

---

# Characteristics of Dictionary

✅ Key-Value Pair Structure

✅ Mutable

✅ Fast Data Access

✅ Keys Must Be Unique

✅ Values Can Be Duplicated

---

# Difference Between List, Tuple, and Dictionary

| Feature         | List | Tuple | Dictionary |
| --------------- | ---- | ----- | ---------- |
| Symbol          | `[]` | `()`  | `{}`       |
| Ordered         | Yes  | Yes   | Yes        |
| Mutable         | Yes  | No    | Yes        |
| Key-Value Pairs | No   | No    | Yes        |

---

# Real-Life Example

```python
student = {
    "roll_no": 101,
    "name": "Anish",
    "course": "BCA",
    "marks": 85
}

print(student["name"])
```

---

# Interview / Exam Definition

**Dictionary:**
A dictionary is a mutable collection in Python that stores data in key-value pairs. Keys are unique and are used to access their corresponding values efficiently.

### Example

```python
student = {
    "name": "Anish",
    "age": 20
}

print(student["name"])
```

**Output:**

```python
Anish
```

## Most Important Dictionary Methods

* `get()`
* `keys()`
* `values()`
* `items()`
* `update()`
* `pop()`
* `clear()`

These methods are commonly asked in **BCA exams, Python interviews, and coding questions**.



# Sets in Python

A **Set** is an unordered collection of unique elements.

* Duplicate values are not allowed.
* Sets are mutable (can be modified).
* Sets are written using **curly braces `{}`**.
* Elements have no index position.

---

# Creating a Set

```python
numbers = {10, 20, 30, 40}

print(numbers)
```

**Output:**

```python
{10, 20, 30, 40}
```

---

# Duplicate Values are Removed

```python
numbers = {1, 2, 2, 3, 3, 4}

print(numbers)
```

**Output:**

```python
{1, 2, 3, 4}
```

---

# Creating an Empty Set

⚠️ Don't use `{}` because it creates a dictionary.

```python
s = set()

print(type(s))
```

**Output:**

```python
<class 'set'>
```

---

# Accessing Elements

Sets do not support indexing.

❌ Wrong:

```python
numbers = {10, 20, 30}

print(numbers[0])
```

**Error:**

```python
TypeError: 'set' object is not subscriptable
```

### Using Loop

```python
numbers = {10, 20, 30}

for num in numbers:
    print(num)
```

---

# Adding Elements

## `add()`

Adds a single element.

```python
numbers = {1, 2, 3}

numbers.add(4)

print(numbers)
```

**Output:**

```python
{1, 2, 3, 4}
```

---

## `update()`

Adds multiple elements.

```python
numbers = {1, 2, 3}

numbers.update([4, 5, 6])

print(numbers)
```

**Output:**

```python
{1, 2, 3, 4, 5, 6}
```

---

# Removing Elements

## `remove()`

```python
numbers = {1, 2, 3}

numbers.remove(2)

print(numbers)
```

**Output:**

```python
{1, 3}
```

⚠️ Error if element doesn't exist.

---

## `discard()`

```python
numbers = {1, 2, 3}

numbers.discard(5)

print(numbers)
```

No error occurs.

---

## `pop()`

Removes a random element.

```python
numbers = {10, 20, 30}

numbers.pop()

print(numbers)
```

---

## `clear()`

```python
numbers = {1, 2, 3}

numbers.clear()

print(numbers)
```

**Output:**

```python
set()
```

---

# Membership Operators

```python
numbers = {10, 20, 30}

print(20 in numbers)
print(50 in numbers)
```

**Output:**

```python
True
False
```

---

# Set Operations

Suppose:

```python
A = {1, 2, 3, 4}
B = {3, 4, 5, 6}
```

---

## Union (`|`)

Combines all unique elements.

```python
print(A | B)
```

**Output:**

```python
{1, 2, 3, 4, 5, 6}
```

---

## Intersection (`&`)

Common elements.

```python
print(A & B)
```

**Output:**

```python
{3, 4}
```

---

## Difference (`-`)

Elements in A but not in B.

```python
print(A - B)
```

**Output:**

```python
{1, 2}
```

---

## Symmetric Difference (`^`)

Elements present in one set but not both.

```python
print(A ^ B)
```

**Output:**

```python
{1, 2, 5, 6}
```

---

# Important Set Methods

## `union()`

```python
A = {1, 2}
B = {2, 3}

print(A.union(B))
```

---

## `intersection()`

```python
print(A.intersection(B))
```

---

## `difference()`

```python
print(A.difference(B))
```

---

## `symmetric_difference()`

```python
print(A.symmetric_difference(B))
```

---

# Frozen Set

A **frozenset** is an immutable set.

```python
fs = frozenset([1, 2, 3])

print(fs)
```

You cannot add or remove elements from a frozenset.

---

# Set Comprehension

```python
squares = {x*x for x in range(1, 6)}

print(squares)
```

**Output:**

```python
{1, 4, 9, 16, 25}
```

---

# Difference Between List, Tuple, Dictionary, and Set

| Feature            | List | Tuple | Dictionary | Set  |
| ------------------ | ---- | ----- | ---------- | ---- |
| Symbol             | `[]` | `()`  | `{}`       | `{}` |
| Ordered            | Yes  | Yes   | Yes        | No   |
| Mutable            | Yes  | No    | Yes        | Yes  |
| Duplicates Allowed | Yes  | Yes   | Keys No    | No   |
| Indexing           | Yes  | Yes   | By Key     | No   |

---

# Real-Life Example

Find unique subjects chosen by students:

```python
subjects = ["Python", "Java", "Python", "C++", "Java"]

unique_subjects = set(subjects)

print(unique_subjects)
```

**Output:**

```python
{'Python', 'Java', 'C++'}
```

---

# Interview / Exam Definition

**Set:**
A set is an unordered and mutable collection of unique elements in Python. Sets do not allow duplicate values and are mainly used for membership testing and mathematical set operations such as union, intersection, and difference.

### Example

```python
numbers = {1, 2, 3, 4}

print(numbers)
```

### Important Set Methods

* `add()`
* `update()`
* `remove()`
* `discard()`
* `pop()`
* `clear()`
* `union()`
* `intersection()`
* `difference()`
* `symmetric_difference()`

### Common Exam Question

**Q: Why are sets faster for searching than lists?**

**Answer:**
Sets use a hash table internally, which allows very fast lookup operations (average O(1) time complexity), whereas lists require sequential searching (O(n)).



# Arrays in Python

An **Array** is a data structure used to store multiple values of the **same data type** in a single variable.

In Python, arrays are provided by the built-in **array** module.

---

# Why Use Arrays?

Instead of creating many variables:

```python id="q4x6n4"
a = 10
b = 20
c = 30
d = 40
```

We can store them in one array:

```python id="h4mwwd"
from array import *

arr = array('i', [10, 20, 30, 40])
```

---

# Importing Array Module

```python id="rkk8qi"
from array import *
```

or

```python id="9qxxu3"
import array
```

---

# Creating an Array

### Integer Array

```python id="t2yv2s"
from array import *

arr = array('i', [10, 20, 30, 40])

print(arr)
```

**Output:**

```python id="mwmdfk"
array('i', [10, 20, 30, 40])
```

---

# Type Codes

| Type Code | Data Type         |
| --------- | ----------------- |
| `'i'`     | Integer           |
| `'f'`     | Float             |
| `'d'`     | Double            |
| `'u'`     | Unicode Character |

### Float Array

```python id="zuvv5h"
from array import *

arr = array('f', [1.1, 2.2, 3.3])

print(arr)
```

---

# Accessing Elements

```python id="c89yvz"
from array import *

arr = array('i', [10, 20, 30, 40])

print(arr[0])
print(arr[2])
```

**Output:**

```python id="pcdr1g"
10
30
```

---

# Traversing an Array

```python id="r0e16j"
from array import *

arr = array('i', [10, 20, 30, 40])

for x in arr:
    print(x)
```

---

# Adding Elements

## `append()`

```python id="y2ncmn"
from array import *

arr = array('i', [10, 20, 30])

arr.append(40)

print(arr)
```

**Output:**

```python id="11r8an"
array('i', [10, 20, 30, 40])
```

---

## `insert()`

```python id="t3u8fr"
from array import *

arr = array('i', [10, 20, 40])

arr.insert(2, 30)

print(arr)
```

**Output:**

```python id="3tpnhz"
array('i', [10, 20, 30, 40])
```

---

# Removing Elements

## `remove()`

```python id="pppmov"
from array import *

arr = array('i', [10, 20, 30])

arr.remove(20)

print(arr)
```

**Output:**

```python id="76h6h9"
array('i', [10, 30])
```

---

## `pop()`

```python id="q53wt2"
from array import *

arr = array('i', [10, 20, 30])

arr.pop()

print(arr)
```

**Output:**

```python id="z9w5dc"
array('i', [10, 20])
```

---

# Updating Elements

```python id="77yzp5"
from array import *

arr = array('i', [10, 20, 30])

arr[1] = 100

print(arr)
```

**Output:**

```python id="y7ubyc"
array('i', [10, 100, 30])
```

---

# Searching an Element

## `index()`

```python id="b6m2jv"
from array import *

arr = array('i', [10, 20, 30])

print(arr.index(20))
```

**Output:**

```python id="hmy84l"
1
```

---

# Array Slicing

```python id="43vs1n"
from array import *

arr = array('i', [10, 20, 30, 40, 50])

print(arr[1:4])
```

**Output:**

```python id="fd0m0y"
array('i', [20, 30, 40])
```

---

# Length of Array

```python id="ym24x5"
from array import *

arr = array('i', [10, 20, 30])

print(len(arr))
```

**Output:**

```python id="f3v0z3"
3
```

---

# Difference Between Array and List

| Array                         | List                         |
| ----------------------------- | ---------------------------- |
| Same data type only           | Different data types allowed |
| Uses less memory              | Uses more memory             |
| Faster for numeric operations | More flexible                |
| Requires `array` module       | Built-in                     |

### Example

```python id="8ktq6v"
from array import *

arr = array('i', [10, 20, 30])
```

```python id="j0n6qt"
lst = [10, "Anish", 3.14]
```

---

# NumPy Arrays

In Data Science and Machine Learning, we usually use **NumPy arrays** instead of the basic array module.

```python id="hy6td5"
import numpy as np

arr = np.array([10, 20, 30])

print(arr)
```

NumPy arrays are:

* Faster
* More powerful
* Support mathematical operations

---

# Common Array Operations

```python id="w4j4n6"
from array import *

arr = array('i', [10, 20, 30])

print(max(arr))
print(min(arr))
print(sum(arr))
```

**Output:**

```python id="z5crjk"
30
10
60
```

---

# Real-Life Example

Store marks of students:

```python id="zfx0pw"
from array import *

marks = array('i', [85, 90, 78, 92])

for mark in marks:
    print(mark)
```

---

# Interview / Exam Definition

**Array:**
An array is a collection of elements of the same data type stored in contiguous memory locations. In Python, arrays are created using the `array` module and are used for efficient storage and processing of homogeneous data.

### Example

```python id="20l7b9"
from array import *

arr = array('i', [10, 20, 30])

print(arr[0])
```

**Output:**

```python id="44l6l4"
10
```

### Important Array Methods

* `append()`
* `insert()`
* `remove()`
* `pop()`
* `index()`

### Common Exam Question

**Q: What is the difference between an Array and a List?**

**Answer:**
An array stores elements of the same data type and is more memory-efficient, whereas a list can store elements of different data types and is more flexible.


# List Comprehensions in Python

**List Comprehension** is a short and efficient way to create lists in Python.

It allows you to create a new list using a single line of code instead of using loops.

---

# Syntax

```python
new_list = [expression for item in iterable]
```

### With Condition

```python
new_list = [expression for item in iterable if condition]
```

---

# Example 1: Without List Comprehension

```python
squares = []

for i in range(1, 6):
    squares.append(i * i)

print(squares)
```

**Output:**

```python
[1, 4, 9, 16, 25]
```

---

# Example 2: Using List Comprehension

```python
squares = [i * i for i in range(1, 6)]

print(squares)
```

**Output:**

```python
[1, 4, 9, 16, 25]
```

---

# How It Works

```python
[i * i for i in range(1, 6)]
```

Breakdown:

```text
Expression → i * i
Variable   → i
Loop       → for i in range(1, 6)
```

---

# Example 3: Create a List of Numbers

```python
numbers = [x for x in range(1, 11)]

print(numbers)
```

**Output:**

```python
[1, 2, 3, 4, 5, 6, 7, 8, 9, 10]
```

---

# Example 4: Even Numbers

```python
even_numbers = [x for x in range(1, 11) if x % 2 == 0]

print(even_numbers)
```

**Output:**

```python
[2, 4, 6, 8, 10]
```

---

# Example 5: Odd Numbers

```python
odd_numbers = [x for x in range(1, 11) if x % 2 != 0]

print(odd_numbers)
```

**Output:**

```python
[1, 3, 5, 7, 9]
```

---

# Example 6: Convert Strings to Uppercase

```python
names = ["anish", "rahul", "aman"]

result = [name.upper() for name in names]

print(result)
```

**Output:**

```python
['ANISH', 'RAHUL', 'AMAN']
```

---

# Example 7: Length of Each Word

```python
words = ["Python", "Java", "C++"]

lengths = [len(word) for word in words]

print(lengths)
```

**Output:**

```python
[6, 4, 3]
```

---

# Example 8: Using If-Else

```python
result = ["Even" if x % 2 == 0 else "Odd" for x in range(1, 6)]

print(result)
```

**Output:**

```python
['Odd', 'Even', 'Odd', 'Even', 'Odd']
```

---

# Nested List Comprehension

```python
matrix = [[i * j for j in range(1, 4)] for i in range(1, 4)]

print(matrix)
```

**Output:**

```python
[[1, 2, 3], [2, 4, 6], [3, 6, 9]]
```

---

# List Comprehension vs Normal Loop

### Normal Loop

```python
numbers = []

for i in range(5):
    numbers.append(i)
```

### List Comprehension

```python
numbers = [i for i in range(5)]
```

List comprehension is shorter and more readable.

---

# Advantages

✅ Less code

✅ Faster execution

✅ Easy to read

✅ Pythonic way of creating lists

---

# Disadvantages

❌ Complex comprehensions can be difficult to read.

❌ Not suitable for very large or complicated logic.

---

# Real-Life Example

Convert marks into grades:

```python
marks = [35, 75, 90, 45, 60]

grades = ["Pass" if m >= 40 else "Fail" for m in marks]

print(grades)
```

**Output:**

```python
['Fail', 'Pass', 'Pass', 'Pass', 'Pass']
```

---

# Interview / Exam Definition

**List Comprehension:**
List comprehension is a concise way of creating lists in Python using a single line of code. It consists of an expression, a loop, and optionally a condition.

### General Form

```python
[expression for item in iterable if condition]
```

### Example

```python
squares = [x*x for x in range(1, 6)]

print(squares)
```

**Output:**

```python
[1, 4, 9, 16, 25]
```

### Practice Questions

1. Create a list of squares from 1 to 10.
2. Create a list of even numbers from 1 to 20.
3. Convert all names in a list to uppercase.
4. Create a list containing the lengths of words.
5. Create a list of "Pass" and "Fail" based on marks.

List comprehensions are very common in **Python interviews, Data Science, Machine Learning, and competitive programming** because they make code concise and efficient.


# Counter in Python

A **Counter** is a special dictionary provided by the `collections` module that is used to count the frequency of elements in a collection (list, string, tuple, etc.).

---

# Import Counter

```python
from collections import Counter
```

---

# Creating a Counter

### Example 1: Count Elements in a List

```python
from collections import Counter

numbers = [1, 2, 2, 3, 3, 3]

count = Counter(numbers)

print(count)
```

**Output:**

```python
Counter({3: 3, 2: 2, 1: 1})
```

---

# Count Characters in a String

```python
from collections import Counter

text = "python"

count = Counter(text)

print(count)
```

**Output:**

```python
Counter({'p': 1, 'y': 1, 't': 1, 'h': 1, 'o': 1, 'n': 1})
```

---

# Access Frequency of an Element

```python
from collections import Counter

numbers = [1, 2, 2, 3, 3, 3]

count = Counter(numbers)

print(count[3])
```

**Output:**

```python
3
```

---

# `most_common()` Method

Returns the most frequent elements.

```python
from collections import Counter

numbers = [1, 2, 2, 3, 3, 3]

count = Counter(numbers)

print(count.most_common())
```

**Output:**

```python
[(3, 3), (2, 2), (1, 1)]
```

---

### Top 2 Most Common Elements

```python
print(count.most_common(2))
```

**Output:**

```python
[(3, 3), (2, 2)]
```

---

# Counter from a String

```python
from collections import Counter

text = "banana"

count = Counter(text)

print(count)
```

**Output:**

```python
Counter({'a': 3, 'n': 2, 'b': 1})
```

---

# Convert Counter to Dictionary

```python
from collections import Counter

text = "banana"

count = Counter(text)

print(dict(count))
```

**Output:**

```python
{'b': 1, 'a': 3, 'n': 2}
```

---

# Updating a Counter

```python
from collections import Counter

c = Counter([1, 2, 2])

c.update([2, 3, 3])

print(c)
```

**Output:**

```python
Counter({2: 3, 3: 2, 1: 1})
```

---

# Elements Method

Returns elements according to their count.

```python
from collections import Counter

c = Counter({1: 2, 2: 3})

print(list(c.elements()))
```

**Output:**

```python
[1, 1, 2, 2, 2]
```

---

# Real-Life Example: Word Frequency

```python
from collections import Counter

sentence = "python java python c++ python java"

words = sentence.split()

count = Counter(words)

print(count)
```

**Output:**

```python
Counter({'python': 3, 'java': 2, 'c++': 1})
```

---

# Why Use Counter?

Without Counter:

```python
numbers = [1, 2, 2, 3, 3, 3]

freq = {}

for num in numbers:
    freq[num] = freq.get(num, 0) + 1

print(freq)
```

With Counter:

```python
from collections import Counter

print(Counter(numbers))
```

Much shorter and cleaner.

---

# Counter vs Dictionary

| Counter                          | Dictionary          |
| -------------------------------- | ------------------- |
| Automatically counts frequencies | Must count manually |
| Part of `collections` module     | Built-in            |
| Specialized for counting         | General-purpose     |

---

# LeetCode / DSA Usage

Counter is very useful in problems involving:

* Frequency counting
* Anagrams
* Majority Element
* Top K Frequent Elements
* Character counting
* Sliding Window problems

### Example

```python
from collections import Counter

nums = [1, 1, 2, 2, 2, 3]

print(Counter(nums).most_common(1))
```

**Output:**

```python
[(2, 3)]
```

---

# Interview / Exam Definition

**Counter:**
`Counter` is a subclass of dictionary from the `collections` module that is used to count the frequency of elements in an iterable. It stores elements as keys and their counts as values.

### Example

```python
from collections import Counter

numbers = [1, 2, 2, 3]

print(Counter(numbers))
```

**Output:**

```python
Counter({2: 2, 1: 1, 3: 1})
```

### Important Methods

* `most_common()`
* `update()`
* `elements()`

For **DSA and LeetCode**, `Counter` is one of the most useful Python libraries because it makes frequency-counting problems extremely easy.


# `heapq` Module in Python

The **`heapq`** module provides an implementation of a **Heap Queue (Priority Queue)**.

A heap is a special tree-based data structure where:

* The smallest element is always at the root.
* Python's `heapq` implements a **Min Heap** by default.

---

# Importing `heapq`

```python
import heapq
```

---

# Creating a Heap

```python
import heapq

nums = [4, 1, 7, 3, 8]

heapq.heapify(nums)

print(nums)
```

**Output:**

```python
[1, 3, 7, 4, 8]
```

`heapify()` converts a normal list into a heap.

---

# `heappush()`

Adds an element to the heap.

```python
import heapq

nums = [1, 3, 5]

heapq.heappush(nums, 2)

print(nums)
```

**Output:**

```python
[1, 2, 5, 3]
```

---

# `heappop()`

Removes and returns the smallest element.

```python
import heapq

nums = [1, 2, 5, 3]

smallest = heapq.heappop(nums)

print(smallest)
print(nums)
```

**Output:**

```python
1
[2, 3, 5]
```

---

# Peek the Smallest Element

```python
import heapq

nums = [4, 1, 7]

heapq.heapify(nums)

print(nums[0])
```

**Output:**

```python
1
```

---

# `heappushpop()`

Pushes a new item and pops the smallest item.

```python
import heapq

nums = [1, 3, 5]

result = heapq.heappushpop(nums, 2)

print(result)
print(nums)
```

**Output:**

```python
1
[2, 3, 5]
```

---

# `heapreplace()`

Pops the smallest item and then inserts a new item.

```python
import heapq

nums = [1, 3, 5]

result = heapq.heapreplace(nums, 10)

print(result)
print(nums)
```

**Output:**

```python
1
[3, 10, 5]
```

---

# Largest and Smallest Elements

## `nsmallest()`

```python
import heapq

nums = [4, 1, 8, 2, 9]

print(heapq.nsmallest(3, nums))
```

**Output:**

```python
[1, 2, 4]
```

---

## `nlargest()`

```python
import heapq

nums = [4, 1, 8, 2, 9]

print(heapq.nlargest(2, nums))
```

**Output:**

```python
[9, 8]
```

---

# Max Heap in Python

Python provides only a Min Heap.

To create a Max Heap, store negative values.

```python
import heapq

nums = [4, 1, 7, 3]

max_heap = [-x for x in nums]

heapq.heapify(max_heap)

print(-heapq.heappop(max_heap))
```

**Output:**

```python
7
```

---

# Priority Queue Example

```python
import heapq

tasks = []

heapq.heappush(tasks, (2, "Study"))
heapq.heappush(tasks, (1, "Sleep"))
heapq.heappush(tasks, (3, "Exercise"))

print(heapq.heappop(tasks))
```

**Output:**

```python
(1, 'Sleep')
```

The task with the smallest priority number comes out first.

---

# Heap Visualization

After:

```python
nums = [4, 1, 7, 3]
heapq.heapify(nums)
```

Heap structure:

```text
       1
      / \
     3   7
    /
   4
```

Root always contains the smallest element.

---

# Time Complexity

| Operation        | Complexity |
| ---------------- | ---------- |
| `heapify()`      | O(n)       |
| `heappush()`     | O(log n)   |
| `heappop()`      | O(log n)   |
| Peek (`heap[0]`) | O(1)       |
| `nsmallest()`    | O(n log k) |

---

# LeetCode / DSA Usage

`heapq` is heavily used in:

* Top K Frequent Elements
* Kth Largest Element
* Merge K Sorted Lists
* Dijkstra's Algorithm
* Priority Queue Problems
* Scheduling Problems

Example:

```python
import heapq

nums = [3, 2, 1, 5, 6, 4]

print(heapq.nlargest(2, nums))
```

**Output:**

```python
[6, 5]
```

---

# Interview / Exam Definition

**Heapq:**
`heapq` is a Python module that implements a Min Heap (Priority Queue). It provides efficient insertion, deletion, and retrieval of the smallest element.

### Important Functions

* `heapify()`
* `heappush()`
* `heappop()`
* `heappushpop()`
* `heapreplace()`
* `nsmallest()`
* `nlargest()`

### Quick Memory Trick

* **Heap = Priority Queue**
* **Root = Smallest Element**
* **Push = Insert**
* **Pop = Remove Smallest**

Since you're preparing for **DSA, LeetCode, and coding interviews**, `heapq` is one of the most important Python libraries to master because many medium and hard problems use heaps.


# `deque` in Python

**`deque`** stands for **Double Ended Queue**.

It is provided by the `collections` module and allows insertion and deletion from **both ends** efficiently.

---

# Importing deque

```python
from collections import deque
```

---

# Creating a deque

```python
from collections import deque

dq = deque([1, 2, 3])

print(dq)
```

**Output:**

```python
deque([1, 2, 3])
```

---

# Why Use deque?

In a normal list:

```python
lst = [1, 2, 3]
lst.insert(0, 10)   # Slow
lst.pop(0)          # Slow
```

In deque:

```python
dq.appendleft(10)   # Fast
dq.popleft()        # Fast
```

Both operations are **O(1)**.

---

# Adding Elements

## append()

Add element to the right end.

```python
from collections import deque

dq = deque([1, 2, 3])

dq.append(4)

print(dq)
```

**Output:**

```python
deque([1, 2, 3, 4])
```

---

## appendleft()

Add element to the left end.

```python
dq = deque([1, 2, 3])

dq.appendleft(0)

print(dq)
```

**Output:**

```python
deque([0, 1, 2, 3])
```

---

# Removing Elements

## pop()

Removes from the right side.

```python
dq = deque([1, 2, 3])

dq.pop()

print(dq)
```

**Output:**

```python
deque([1, 2])
```

---

## popleft()

Removes from the left side.

```python
dq = deque([1, 2, 3])

dq.popleft()

print(dq)
```

**Output:**

```python
deque([2, 3])
```

---

# Accessing Elements

```python
dq = deque([10, 20, 30])

print(dq[0])
print(dq[-1])
```

**Output:**

```python
10
30
```

---

# extend()

Add multiple elements at the right end.

```python
dq = deque([1, 2])

dq.extend([3, 4])

print(dq)
```

**Output:**

```python
deque([1, 2, 3, 4])
```

---

# extendleft()

Add multiple elements at the left end.

```python
dq = deque([3, 4])

dq.extendleft([2, 1])

print(dq)
```

**Output:**

```python
deque([1, 2, 3, 4])
```

⚠️ `extendleft()` inserts elements in reverse order.

---

# rotate()

Rotates the deque.

### Rotate Right

```python
dq = deque([1, 2, 3, 4])

dq.rotate(1)

print(dq)
```

**Output:**

```python
deque([4, 1, 2, 3])
```

---

### Rotate Left

```python
dq = deque([1, 2, 3, 4])

dq.rotate(-1)

print(dq)
```

**Output:**

```python
deque([2, 3, 4, 1])
```

---

# count()

```python
dq = deque([1, 2, 2, 3])

print(dq.count(2))
```

**Output:**

```python
2
```

---

# reverse()

```python
dq = deque([1, 2, 3])

dq.reverse()

print(dq)
```

**Output:**

```python
deque([3, 2, 1])
```

---

# Queue Using deque

```python
from collections import deque

queue = deque()

queue.append(10)
queue.append(20)
queue.append(30)

print(queue.popleft())
```

**Output:**

```python
10
```

FIFO (**First In First Out**)

---

# Stack Using deque

```python
from collections import deque

stack = deque()

stack.append(10)
stack.append(20)
stack.append(30)

print(stack.pop())
```

**Output:**

```python
30
```

LIFO (**Last In First Out**)

---

# Time Complexity

| Operation       | Complexity |
| --------------- | ---------- |
| append()        | O(1)       |
| appendleft()    | O(1)       |
| pop()           | O(1)       |
| popleft()       | O(1)       |
| Access by index | O(1)       |

---

# deque vs List

| Feature        | deque | List |
| -------------- | ----- | ---- |
| Append Right   | O(1)  | O(1) |
| Pop Right      | O(1)  | O(1) |
| Append Left    | O(1)  | O(n) |
| Pop Left       | O(1)  | O(n) |
| Best for Queue | ✅     | ❌    |

---

# LeetCode / DSA Usage

`deque` is heavily used in:

* BFS (Breadth-First Search)
* Sliding Window Problems
* Monotonic Queue
* Queue Implementations
* Cache Algorithms

### BFS Example

```python
from collections import deque

queue = deque([1])

while queue:
    node = queue.popleft()
    print(node)
```

---

# Interview / Exam Definition

**deque (Double Ended Queue):**
A deque is a data structure from Python's `collections` module that allows fast insertion and deletion from both ends. It is commonly used to implement queues, stacks, BFS traversals, and sliding window algorithms.

### Important Methods

* `append()`
* `appendleft()`
* `pop()`
* `popleft()`
* `extend()`
* `extendleft()`
* `rotate()`

### Quick Memory Trick

* **append()** → Right side insert
* **appendleft()** → Left side insert
* **pop()** → Right side remove
* **popleft()** → Left side remove

Since you're learning **DSA and LeetCode**, `deque` is one of the most important Python data structures because almost every **BFS** and many **sliding window** problems use it.

# OrderedDict in Python

**OrderedDict** is a dictionary subclass from the `collections` module that remembers the order in which items were inserted.

```python
from collections import OrderedDict
```

---

# Why OrderedDict?

In older Python versions (before Python 3.7), normal dictionaries did not guarantee insertion order.

`OrderedDict` was introduced to maintain the order of elements.

---

# Creating an OrderedDict

```python
from collections import OrderedDict

od = OrderedDict()

od["name"] = "Anish"
od["age"] = 20
od["city"] = "Delhi"

print(od)
```

**Output:**

```python
OrderedDict([('name', 'Anish'),
             ('age', 20),
             ('city', 'Delhi')])
```

---

# Accessing Elements

```python
from collections import OrderedDict

od = OrderedDict({
    "name": "Anish",
    "age": 20
})

print(od["name"])
```

**Output:**

```python
Anish
```

---

# Adding Elements

```python
from collections import OrderedDict

od = OrderedDict()

od["A"] = 1
od["B"] = 2
od["C"] = 3

print(od)
```

**Output:**

```python
OrderedDict([('A', 1), ('B', 2), ('C', 3)])
```

---

# Deleting Elements

```python
from collections import OrderedDict

od = OrderedDict({
    "A": 1,
    "B": 2
})

del od["A"]

print(od)
```

**Output:**

```python
OrderedDict([('B', 2)])
```

---

# move_to_end()

Moves a key to the end (or beginning).

```python
from collections import OrderedDict

od = OrderedDict([
    ("A", 1),
    ("B", 2),
    ("C", 3)
])

od.move_to_end("A")

print(od)
```

**Output:**

```python
OrderedDict([('B', 2),
             ('C', 3),
             ('A', 1)])
```

---

## Move to Beginning

```python
od.move_to_end("C", last=False)
```

---

# popitem()

Removes and returns an item.

### Remove Last Item

```python
from collections import OrderedDict

od = OrderedDict([
    ("A", 1),
    ("B", 2),
    ("C", 3)
])

print(od.popitem())
```

**Output:**

```python
('C', 3)
```

---

### Remove First Item

```python
print(od.popitem(last=False))
```

**Output:**

```python
('A', 1)
```

---

# Traversing OrderedDict

```python
from collections import OrderedDict

od = OrderedDict([
    ("name", "Anish"),
    ("age", 20)
])

for key, value in od.items():
    print(key, value)
```

**Output:**

```python
name Anish
age 20
```

---

# OrderedDict vs Dictionary

| Feature             | OrderedDict | Dictionary        |
| ------------------- | ----------- | ----------------- |
| Maintains Order     | Yes         | Yes (Python 3.7+) |
| move_to_end()       | Yes         | No                |
| popitem(last=False) | Yes         | No                |
| Extra Features      | More        | Less              |

---

# Practical Example: LRU Cache

```python
from collections import OrderedDict

cache = OrderedDict()

cache["A"] = 100
cache["B"] = 200
cache["C"] = 300

cache.move_to_end("A")

print(cache)
```

**Output:**

```python
OrderedDict([('B', 200),
             ('C', 300),
             ('A', 100)])
```

Used in **Least Recently Used (LRU) Cache** implementations.

---

# When Should You Use OrderedDict?

Use it when you need:

✅ Order-sensitive operations

✅ `move_to_end()`

✅ FIFO/LRU cache implementations

✅ Compatibility with older Python versions

For most modern Python programs (3.7+), a normal dictionary is usually sufficient.

---

# Interview / Exam Definition

**OrderedDict:**
`OrderedDict` is a dictionary subclass from the `collections` module that preserves the insertion order of keys and provides additional methods such as `move_to_end()` and `popitem()`.

### Example

```python
from collections import OrderedDict

od = OrderedDict()

od["A"] = 1
od["B"] = 2

print(od)
```

**Output:**

```python
OrderedDict([('A', 1), ('B', 2)])
```

### Important Methods

* `move_to_end()`
* `popitem()`
* `keys()`
* `values()`
* `items()`

### DSA / Interview Usage

* LRU Cache
* Order-sensitive dictionaries
* FIFO processing
* Cache systems

**Note:** In Python 3.7+, normal dictionaries also preserve insertion order, so `OrderedDict` is mainly used when its special methods are needed.


# defaultdict in Python

**`defaultdict`** is a subclass of the dictionary (`dict`) from the `collections` module.

It automatically provides a default value for a key that does not exist, avoiding a `KeyError`.

---

# Import defaultdict

```python
from collections import defaultdict
```

---

# Problem with Normal Dictionary

```python
d = {}

d["name"] += "Anish"
```

**Output:**

```python
KeyError: 'name'
```

Because the key `"name"` does not exist.

---

# Using defaultdict

```python
from collections import defaultdict

d = defaultdict(int)

print(d["age"])
```

**Output:**

```python
0
```

The missing key automatically gets the default value `0`.

---

# Default Factory

The argument passed to `defaultdict()` is called the **default factory**.

### int

```python
from collections import defaultdict

d = defaultdict(int)

print(d["x"])
```

**Output:**

```python
0
```

---

### float

```python
from collections import defaultdict

d = defaultdict(float)

print(d["x"])
```

**Output:**

```python
0.0
```

---

### str

```python
from collections import defaultdict

d = defaultdict(str)

print(d["x"])
```

**Output:**

```python
''
```

---

### list

```python
from collections import defaultdict

d = defaultdict(list)

print(d["x"])
```

**Output:**

```python
[]
```

---

### set

```python
from collections import defaultdict

d = defaultdict(set)

print(d["x"])
```

**Output:**

```python
set()
```

---

# Counting Frequencies

Without defaultdict:

```python
nums = [1, 2, 2, 3]

freq = {}

for num in nums:
    freq[num] = freq.get(num, 0) + 1

print(freq)
```

**Output:**

```python
{1: 1, 2: 2, 3: 1}
```

---

With defaultdict:

```python
from collections import defaultdict

nums = [1, 2, 2, 3]

freq = defaultdict(int)

for num in nums:
    freq[num] += 1

print(freq)
```

**Output:**

```python
defaultdict(<class 'int'>, {1: 1, 2: 2, 3: 1})
```

---

# Grouping Data

```python
from collections import defaultdict

students = [
    ("BCA", "Anish"),
    ("BCA", "Rahul"),
    ("MCA", "Amit")
]

groups = defaultdict(list)

for course, name in students:
    groups[course].append(name)

print(groups)
```

**Output:**

```python
defaultdict(<class 'list'>,
{
'BCA': ['Anish', 'Rahul'],
'MCA': ['Amit']
})
```

---

# Using Lambda Function

```python
from collections import defaultdict

d = defaultdict(lambda: "Not Found")

print(d["name"])
```

**Output:**

```python
Not Found
```

---

# Nested defaultdict

```python
from collections import defaultdict

data = defaultdict(lambda: defaultdict(int))

data["student"]["marks"] = 95

print(data)
```

**Output:**

```python
defaultdict(...,
{'student': {'marks': 95}})
```

---

# Convert to Normal Dictionary

```python
from collections import defaultdict

d = defaultdict(int)

d["a"] += 1

print(dict(d))
```

**Output:**

```python
{'a': 1}
```

---

# defaultdict vs dict

| Feature            | dict      | defaultdict   |
| ------------------ | --------- | ------------- |
| Missing Key        | KeyError  | Default Value |
| Need `get()`       | Yes       | No            |
| Frequency Counting | More Code | Less Code     |
| Grouping Data      | More Code | Easier        |

---

# Real-Life Example

Count words in a sentence:

```python
from collections import defaultdict

sentence = "python java python c++ java"

words = sentence.split()

count = defaultdict(int)

for word in words:
    count[word] += 1

print(count)
```

**Output:**

```python
defaultdict(<class 'int'>,
{
'python': 2,
'java': 2,
'c++': 1
})
```

---

# LeetCode / DSA Usage

`defaultdict` is commonly used in:

* Graph Representation
* BFS & DFS
* Frequency Counting
* Group Anagrams
* Hash Maps
* Adjacency Lists

### Graph Example

```python
from collections import defaultdict

graph = defaultdict(list)

graph[1].append(2)
graph[1].append(3)

print(graph)
```

**Output:**

```python
defaultdict(<class 'list'>,
{1: [2, 3]})
```

---

# Interview / Exam Definition

**defaultdict:**
`defaultdict` is a subclass of Python's dictionary from the `collections` module. It automatically assigns a default value to a missing key, preventing `KeyError` and simplifying tasks like counting and grouping.

### Example

```python
from collections import defaultdict

d = defaultdict(int)

d["a"] += 1

print(d)
```

**Output:**

```python
defaultdict(<class 'int'>, {'a': 1})
```

### Important Default Factories

* `int` → `0`
* `float` → `0.0`
* `str` → `""`
* `list` → `[]`
* `set` → `set()`

### Most Common DSA Uses

1. Frequency Counting
2. Graphs (Adjacency Lists)
3. Grouping Elements
4. BFS / DFS Problems
5. HashMap-Based LeetCode Questions

**Quick Memory Trick:**

* `dict` → Error on missing key ❌
* `defaultdict` → Automatic default value ✅



# Object-Oriented Programming (OOP) in Python

**OOP (Object-Oriented Programming)** is a programming paradigm that organizes code into **Classes** and **Objects**.

It helps in:

* Code reusability
* Better organization
* Easy maintenance
* Real-world modeling

---

# Class and Object

## Class

A **Class** is a blueprint or template for creating objects.

## Object

An **Object** is an instance of a class.

### Example

```python
class Student:
    pass

s1 = Student()

print(type(s1))
```

**Output:**

```python
<class '__main__.Student'>
```

---

# Constructor (`__init__`)

A constructor is automatically called when an object is created.

```python
class Student:

    def __init__(self, name, age):
        self.name = name
        self.age = age

s1 = Student("Anish", 20)

print(s1.name)
print(s1.age)
```

**Output:**

```python
Anish
20
```

---

# self Keyword

`self` refers to the current object.

```python
class Student:

    def __init__(self, name):
        self.name = name

s1 = Student("Anish")

print(s1.name)
```

---

# Instance Variables

Variables that belong to an object.

```python
class Student:

    def __init__(self, name):
        self.name = name

s1 = Student("Anish")
```

Here `name` is an instance variable.

---

# Instance Methods

```python
class Student:

    def __init__(self, name):
        self.name = name

    def display(self):
        print("Name:", self.name)

s1 = Student("Anish")
s1.display()
```

**Output:**

```python
Name: Anish
```

---

# Four Pillars of OOP

1. Encapsulation
2. Abstraction
3. Inheritance
4. Polymorphism

---

# 1. Encapsulation

Wrapping data and methods into a single unit (class).

```python
class Student:

    def __init__(self):
        self.name = "Anish"

obj = Student()

print(obj.name)
```

---

# Private Variables

```python
class Student:

    def __init__(self):
        self.__age = 20

obj = Student()

# print(obj.__age)  ❌ Error
```

Access through method:

```python
class Student:

    def __init__(self):
        self.__age = 20

    def get_age(self):
        return self.__age

obj = Student()

print(obj.get_age())
```

**Output:**

```python
20
```

---

# 2. Inheritance

Inheritance allows one class to acquire properties of another class.

## Single Inheritance

```python
class Animal:

    def sound(self):
        print("Animal Sound")

class Dog(Animal):
    pass

d = Dog()

d.sound()
```

**Output:**

```python
Animal Sound
```

---

## Multiple Inheritance

```python
class A:
    def show(self):
        print("Class A")

class B:
    def display(self):
        print("Class B")

class C(A, B):
    pass

obj = C()

obj.show()
obj.display()
```

---

## Multilevel Inheritance

```python
class A:
    pass

class B(A):
    pass

class C(B):
    pass
```

---

## Hierarchical Inheritance

```python
class Parent:
    pass

class Child1(Parent):
    pass

class Child2(Parent):
    pass
```

---

# Method Overriding

Child class redefines a parent method.

```python
class Animal:

    def sound(self):
        print("Animal Sound")

class Dog(Animal):

    def sound(self):
        print("Bark")

d = Dog()

d.sound()
```

**Output:**

```python
Bark
```

---

# super() Method

Used to call parent class methods.

```python
class Animal:

    def sound(self):
        print("Animal Sound")

class Dog(Animal):

    def sound(self):
        super().sound()
        print("Bark")

d = Dog()

d.sound()
```

**Output:**

```python
Animal Sound
Bark
```

---

# 3. Polymorphism

Same method behaves differently.

```python
class Dog:
    def sound(self):
        print("Bark")

class Cat:
    def sound(self):
        print("Meow")

for animal in [Dog(), Cat()]:
    animal.sound()
```

**Output:**

```python
Bark
Meow
```

---

# Operator Overloading

```python
print(10 + 20)
print("Hello " + "Python")
```

`+` behaves differently based on data type.

---

# 4. Abstraction

Hiding implementation details and showing only essential features.

Use `ABC` module.

```python
from abc import ABC, abstractmethod

class Shape(ABC):

    @abstractmethod
    def area(self):
        pass

class Circle(Shape):

    def area(self):
        return 3.14 * 5 * 5

obj = Circle()

print(obj.area())
```

**Output:**

```python
78.5
```

---

# Class Variables

Shared among all objects.

```python
class Student:

    college = "MDU"

    def __init__(self, name):
        self.name = name

s1 = Student("Anish")
s2 = Student("Rahul")

print(s1.college)
print(s2.college)
```

---

# Static Method

```python
class Demo:

    @staticmethod
    def greet():
        print("Hello")

Demo.greet()
```

---

# Class Method

```python
class Student:

    college = "MDU"

    @classmethod
    def show(cls):
        print(cls.college)

Student.show()
```

---

# Magic (Dunder) Methods

Special methods with double underscores.

```python
class Demo:

    def __str__(self):
        return "Object Printed"

obj = Demo()

print(obj)
```

**Output:**

```python
Object Printed
```

---

# OOP Summary

| Concept       | Description       |
| ------------- | ----------------- |
| Class         | Blueprint         |
| Object        | Instance of Class |
| Constructor   | `__init__()`      |
| Encapsulation | Data Hiding       |
| Inheritance   | Code Reuse        |
| Polymorphism  | Many Forms        |
| Abstraction   | Hide Complexity   |
| Overriding    | Redefine Method   |
| super()       | Access Parent     |
| Static Method | `@staticmethod`   |
| Class Method  | `@classmethod`    |

---

# Interview / Exam Definition

**Object-Oriented Programming (OOP):**
OOP is a programming paradigm that uses classes and objects to organize code. It is based on four principles: **Encapsulation, Inheritance, Polymorphism, and Abstraction**.

### Example

```python
class Student:

    def __init__(self, name):
        self.name = name

    def display(self):
        print(self.name)

s1 = Student("Anish")

s1.display()
```

### Output

```python
Anish
```

### Most Important OOP Topics for BCA & Interviews

1. Class and Object
2. Constructor (`__init__`)
3. self Keyword
4. Encapsulation
5. Inheritance
6. Polymorphism
7. Abstraction
8. Method Overriding
9. `super()`
10. Static & Class Methods

These are the core OOP concepts asked in **BCA exams, Python interviews, and software development interviews**.


# Classes and Objects in Python

## What is a Class?

A **Class** is a blueprint or template used to create objects.

It defines:

* Attributes (variables/data)
* Methods (functions/behavior)

### Real-Life Example

Think of a **Car**:

* Color
* Brand
* Speed

These are properties of a car.

A **Car class** defines these properties, while actual cars are objects.

---

## What is an Object?

An **Object** is an instance of a class.

When we create an object, memory is allocated and it can use the class's attributes and methods.

---

# Creating a Class

```python
class Student:
    pass
```

Here:

* `class` is a keyword.
* `Student` is the class name.
* `pass` means the class is empty.

---

# Creating an Object

```python
class Student:
    pass

s1 = Student()

print(s1)
```

**Output:**

```python
<__main__.Student object at 0x...>
```

`s1` is an object of the `Student` class.

---

# Class with Attributes

```python
class Student:

    def __init__(self, name, age):
        self.name = name
        self.age = age

s1 = Student("Anish", 20)

print(s1.name)
print(s1.age)
```

**Output:**

```python
Anish
20
```

---

# Constructor (`__init__`)

A constructor is a special method that runs automatically when an object is created.

```python
class Student:

    def __init__(self):
        print("Object Created")

s1 = Student()
```

**Output:**

```python
Object Created
```

---

# self Keyword

`self` refers to the current object.

```python
class Student:

    def __init__(self, name):
        self.name = name

s1 = Student("Anish")

print(s1.name)
```

`self.name` belongs to the object.

---

# Class with Methods

```python
class Student:

    def __init__(self, name):
        self.name = name

    def display(self):
        print("Name:", self.name)

s1 = Student("Anish")

s1.display()
```

**Output:**

```python
Name: Anish
```

---

# Multiple Objects

```python
class Student:

    def __init__(self, name):
        self.name = name

s1 = Student("Anish")
s2 = Student("Rahul")

print(s1.name)
print(s2.name)
```

**Output:**

```python
Anish
Rahul
```

Each object has its own data.

---

# Example: Car Class

```python
class Car:

    def __init__(self, brand, color):
        self.brand = brand
        self.color = color

    def show(self):
        print(self.brand, self.color)

c1 = Car("BMW", "Black")
c2 = Car("Audi", "White")

c1.show()
c2.show()
```

**Output:**

```python
BMW Black
Audi White
```

---

# Object Modifying Attributes

```python
class Student:

    def __init__(self, name):
        self.name = name

s1 = Student("Anish")

s1.name = "Rahul"

print(s1.name)
```

**Output:**

```python
Rahul
```

---

# Object Deletion

```python
class Student:
    pass

s1 = Student()

del s1
```

The object is removed from memory.

---

# Class Variables vs Instance Variables

## Instance Variable

Different for every object.

```python
class Student:

    def __init__(self, name):
        self.name = name
```

---

## Class Variable

Shared by all objects.

```python
class Student:

    college = "MDU"

    def __init__(self, name):
        self.name = name

s1 = Student("Anish")
s2 = Student("Rahul")

print(s1.college)
print(s2.college)
```

**Output:**

```python
MDU
MDU
```

---

# Memory Representation

```text
Class
  |
  v
Student
  |
  +----> Object 1 (Anish)
  |
  +----> Object 2 (Rahul)
```

---

# Advantages of Classes and Objects

✅ Code Reusability

✅ Better Organization

✅ Easy Maintenance

✅ Real-World Modeling

✅ Data Security

---

# Real-Life Example

```python
class Mobile:

    def __init__(self, brand, price):
        self.brand = brand
        self.price = price

    def details(self):
        print("Brand:", self.brand)
        print("Price:", self.price)

m1 = Mobile("Samsung", 25000)

m1.details()
```

**Output:**

```python
Brand: Samsung
Price: 25000
```

---

# Interview / Exam Definition

### Class

A **Class** is a blueprint or template used to create objects. It defines the attributes and methods that objects will have.

### Object

An **Object** is an instance of a class that contains actual data and can access the methods defined in the class.

### Example

```python
class Student:

    def __init__(self, name):
        self.name = name

s1 = Student("Anish")

print(s1.name)
```

**Output:**

```python
Anish
```

### Important Points

* Class = Blueprint
* Object = Instance of Class
* Constructor = `__init__()`
* `self` = Current Object
* Class Variables = Shared
* Instance Variables = Unique

### Common Viva Question

**Q: What is the difference between a class and an object?**

| Class                          | Object               |
| ------------------------------ | -------------------- |
| Blueprint                      | Instance             |
| Logical Entity                 | Physical Entity      |
| No Memory Until Object Created | Occupies Memory      |
| Defines Structure              | Contains Actual Data |

**Example:**

* Class = Car
* Objects = BMW, Audi, Mercedes

This is one of the most frequently asked topics in **BCA exams, Python interviews, and OOP interviews**.


# Constructors in Python

A **Constructor** is a special method that is automatically called when an object of a class is created.

In Python, the constructor is written using the **`__init__()`** method.

---

# Why Use Constructors?

Constructors are used to:

* Initialize object data.
* Assign values to object attributes.
* Perform setup tasks when an object is created.

---

# Syntax

```python
class ClassName:

    def __init__(self):
        # Constructor code
```

---

# Simple Constructor Example

```python
class Student:

    def __init__(self):
        print("Constructor Called")

s1 = Student()
```

**Output:**

```python
Constructor Called
```

The constructor is called automatically when `s1` is created.

---

# Parameterized Constructor

A constructor can accept parameters.

```python
class Student:

    def __init__(self, name, age):
        self.name = name
        self.age = age

s1 = Student("Anish", 20)

print(s1.name)
print(s1.age)
```

**Output:**

```python
Anish
20
```

---

# Multiple Objects

```python
class Student:

    def __init__(self, name):
        self.name = name

s1 = Student("Anish")
s2 = Student("Rahul")

print(s1.name)
print(s2.name)
```

**Output:**

```python
Anish
Rahul
```

---

# Constructor with Methods

```python
class Student:

    def __init__(self, name):
        self.name = name

    def display(self):
        print("Name:", self.name)

s1 = Student("Anish")
s1.display()
```

**Output:**

```python
Name: Anish
```

---

# Default Constructor

A constructor without parameters (except `self`) is called a default constructor.

```python
class Student:

    def __init__(self):
        self.name = "Anish"

s1 = Student()

print(s1.name)
```

**Output:**

```python
Anish
```

---

# Constructor with Default Values

```python
class Student:

    def __init__(self, name="Unknown"):
        self.name = name

s1 = Student()
s2 = Student("Anish")

print(s1.name)
print(s2.name)
```

**Output:**

```python
Unknown
Anish
```

---

# Constructor in Inheritance

```python
class Person:

    def __init__(self):
        print("Person Constructor")

class Student(Person):
    pass

s = Student()
```

**Output:**

```python
Person Constructor
```

The child class automatically calls the parent's constructor if it doesn't have its own constructor.

---

# Calling Parent Constructor Using `super()`

```python
class Person:

    def __init__(self):
        print("Person Constructor")

class Student(Person):

    def __init__(self):
        super().__init__()
        print("Student Constructor")

s = Student()
```

**Output:**

```python
Person Constructor
Student Constructor
```

---

# Constructor Overloading

Python does **not support constructor overloading** directly.

❌ Not Allowed:

```python
class Demo:

    def __init__(self):
        pass

    def __init__(self, x):
        pass
```

Only the last constructor is used.

---

# Alternative to Constructor Overloading

Use default arguments.

```python
class Demo:

    def __init__(self, x=0):
        self.x = x

d1 = Demo()
d2 = Demo(10)

print(d1.x)
print(d2.x)
```

**Output:**

```python
0
10
```

---

# Destructor (`__del__()`)

A destructor is called when an object is destroyed.

```python
class Student:

    def __init__(self):
        print("Constructor Called")

    def __del__(self):
        print("Destructor Called")

s1 = Student()

del s1
```

**Output:**

```python
Constructor Called
Destructor Called
```

---

# Constructor vs Method

| Constructor                      | Method                 |
| -------------------------------- | ---------------------- |
| `__init__()`                     | Any function           |
| Called automatically             | Called manually        |
| Initializes object               | Performs tasks         |
| Runs once during object creation | Can run multiple times |

---

# Real-Life Example

```python
class Mobile:

    def __init__(self, brand, price):
        self.brand = brand
        self.price = price

    def details(self):
        print("Brand:", self.brand)
        print("Price:", self.price)

m1 = Mobile("Samsung", 25000)

m1.details()
```

**Output:**

```python
Brand: Samsung
Price: 25000
```

---

# Memory Representation

```text
Class Mobile
      |
      v
Object m1
      |
      +--> brand = Samsung
      +--> price = 25000
```

The constructor initializes these values when the object is created.

---

# Interview / Exam Definition

**Constructor:**
A constructor is a special method in Python, represented by `__init__()`, that is automatically executed when an object is created. It is used to initialize the object's attributes.

### Example

```python
class Student:

    def __init__(self, name):
        self.name = name

s1 = Student("Anish")

print(s1.name)
```

**Output:**

```python
Anish
```

### Types of Constructors

1. Default Constructor
2. Parameterized Constructor

### Important Points

* Constructor name: `__init__()`
* Called automatically.
* Used for initialization.
* Python does not support constructor overloading directly.
* `super()` is used to call parent constructors.

### Common Viva Question

**Q: What is the purpose of a constructor?**

**Answer:**
A constructor is used to initialize object attributes and perform setup operations automatically when an object is created.



# `self` as Default Argument in Python

## What is `self`?

`self` is a reference to the **current object (instance)** of a class.

It is automatically passed as the first argument to instance methods.

---

## Example

```python
class Student:

    def display(self):
        print("Hello")

s1 = Student()

s1.display()
```

Python internally converts:

```python
s1.display()
```

to

```python
Student.display(s1)
```

Here, `s1` is passed automatically as `self`.

---

## Why is `self` Required?

Without `self`, methods cannot access object variables.

### Example

```python
class Student:

    def __init__(self, name):
        self.name = name

    def display(self):
        print(self.name)

s1 = Student("Anish")
s1.display()
```

**Output:**

```python
Anish
```

`self.name` refers to the `name` attribute of the current object.

---

## `self` is Not a Keyword

You can technically use any name:

```python
class Student:

    def display(obj):
        print("Hello")

s1 = Student()
s1.display()
```

But by convention, Python programmers always use **`self`**.

---

## What Does "self as Default Argument" Mean?

When defining an instance method:

```python
class Demo:

    def show(self):
        print("Hello")
```

You don't pass `self` manually:

```python
obj = Demo()
obj.show()
```

Python automatically passes the object as the first argument.

Internally:

```python
Demo.show(obj)
```

So `self` acts like an automatically supplied first argument.

---

## Example with Multiple Parameters

```python
class Student:

    def show(self, name):
        print(name)

s = Student()

s.show("Anish")
```

Internally Python does:

```python
Student.show(s, "Anish")
```

Where:

* `s` → `self`
* `"Anish"` → `name`

---

## Common Mistake

```python
class Student:

    def display():
        print("Hello")

s = Student()
s.display()
```

❌ Error:

```python
TypeError:
display() takes 0 positional arguments but 1 was given
```

Because Python automatically passes the object.

Correct:

```python
class Student:

    def display(self):
        print("Hello")
```

---

## Interview / Viva Answer

**Q: Why do we use `self` in Python?**

**Answer:**
`self` refers to the current object of a class. It is used to access instance variables and methods. Python automatically passes the object reference as the first argument to instance methods, and by convention this argument is named `self`.

### Example

```python
class Student:

    def __init__(self, name):
        self.name = name

    def display(self):
        print(self.name)

s1 = Student("Anish")
s1.display()
```

**Output:**

```python
Anish
```

### Key Points

* `self` = current object reference.
* Automatically passed by Python.
* Not a keyword, but a convention.
* Used to access instance variables and methods.
* Must be the first parameter of instance methods.



# Polymorphism in Python

## What is Polymorphism?

**Polymorphism** means **"many forms"**.

In Python, polymorphism allows the **same method, function, or operator** to behave differently depending on the object or data type.

---

# Real-Life Example

A person can have different roles:

* Teacher in school
* Father at home
* Customer in a shop

One person → Many forms

Similarly,

One method/operator → Many behaviors

---

# Types of Polymorphism in Python

1. Function Polymorphism
2. Operator Polymorphism
3. Method Overriding (Runtime Polymorphism)

---

# 1. Function Polymorphism

The same function works with different data types.

```python
print(len("Python"))
print(len([1, 2, 3, 4]))
print(len((10, 20, 30)))
```

**Output:**

```python
6
4
3
```

`len()` works with:

* String
* List
* Tuple

Same function, different behavior.

---

# 2. Operator Polymorphism

The same operator behaves differently for different data types.

```python
print(10 + 20)
```

**Output:**

```python
30
```

```python
print("Hello " + "Python")
```

**Output:**

```python
Hello Python
```

Here:

* `+` adds numbers.
* `+` concatenates strings.

This is called **Operator Overloading**.

---

# 3. Method Overriding (Runtime Polymorphism)

A child class provides its own implementation of a parent class method.

```python
class Animal:

    def sound(self):
        print("Animal Sound")

class Dog(Animal):

    def sound(self):
        print("Bark")

d = Dog()

d.sound()
```

**Output:**

```python
Bark
```

The child class method overrides the parent class method.

---

# Polymorphism Using Multiple Classes

```python
class Dog:

    def sound(self):
        print("Bark")

class Cat:

    def sound(self):
        print("Meow")

class Cow:

    def sound(self):
        print("Moo")

animals = [Dog(), Cat(), Cow()]

for animal in animals:
    animal.sound()
```

**Output:**

```python
Bark
Meow
Moo
```

All classes have the same method name `sound()`, but each behaves differently.

---

# Duck Typing

Python follows the principle:

> "If it walks like a duck and quacks like a duck, it is a duck."

Python does not care about the object's type. It only checks whether the required method exists.

```python
class Bird:

    def fly(self):
        print("Bird Flying")

class Airplane:

    def fly(self):
        print("Airplane Flying")

def start_flying(obj):
    obj.fly()

start_flying(Bird())
start_flying(Airplane())
```

**Output:**

```python
Bird Flying
Airplane Flying
```

This is called **Duck Typing Polymorphism**.

---

# Method Overloading in Python

Python does not support traditional method overloading.

❌ Not Allowed:

```python
class Demo:

    def add(self, a):
        pass

    def add(self, a, b):
        pass
```

Only the last method is kept.

---

# Alternative to Method Overloading

Use default arguments.

```python
class Demo:

    def add(self, a, b=0):
        return a + b

d = Demo()

print(d.add(10))
print(d.add(10, 20))
```

**Output:**

```python
10
30
```

---

# Advantages of Polymorphism

✅ Code Reusability

✅ Flexibility

✅ Easy Maintenance

✅ Extensibility

✅ Cleaner Code

---

# Real-Life Example

```python
class Payment:

    def pay(self):
        pass

class CreditCard(Payment):

    def pay(self):
        print("Payment by Credit Card")

class UPI(Payment):

    def pay(self):
        print("Payment by UPI")

payments = [CreditCard(), UPI()]

for p in payments:
    p.pay()
```

**Output:**

```python
Payment by Credit Card
Payment by UPI
```

---

# Polymorphism Summary

| Type                  | Example                       |
| --------------------- | ----------------------------- |
| Function Polymorphism | `len()`                       |
| Operator Polymorphism | `+`                           |
| Method Overriding     | Parent & Child Class          |
| Duck Typing           | Same Method Different Objects |

---

# Interview / Exam Definition

**Polymorphism:**
Polymorphism is an OOP concept that allows the same interface, method, or operator to perform different actions depending on the object or data type. The word polymorphism means "many forms."

### Example

```python
class Dog:

    def sound(self):
        print("Bark")

class Cat:

    def sound(self):
        print("Meow")

animals = [Dog(), Cat()]

for animal in animals:
    animal.sound()
```

**Output:**

```python
Bark
Meow
```

### Key Points

* Polymorphism = One Interface, Many Forms
* Achieved through:

  * Method Overriding
  * Operator Overloading
  * Duck Typing
* Increases code flexibility and reusability.

### Common Viva Question

**Q: What is polymorphism?**

**Answer:**
Polymorphism is the ability of the same method, function, or operator to behave differently for different objects or data types. It allows one interface to represent many forms.


# Inheritance in Python

## What is Inheritance?

**Inheritance** is an OOP concept where one class (Child Class) acquires the properties and methods of another class (Parent Class).

It helps in:

* Code Reusability
* Reducing Redundant Code
* Easy Maintenance

---

# Real-Life Example

```text
Animal (Parent)
   |
   └── Dog (Child)
```

Dog can use all properties and methods of Animal.

---

# Basic Syntax

```python
class Parent:
    pass

class Child(Parent):
    pass
```

---

# Single Inheritance

One child inherits from one parent.

```python
class Animal:

    def sound(self):
        print("Animal makes sound")

class Dog(Animal):
    pass

d = Dog()

d.sound()
```

### Output

```python
Animal makes sound
```

Dog inherits the `sound()` method from Animal.

---

# Inheritance with Constructor

```python
class Person:

    def __init__(self, name):
        self.name = name

class Student(Person):
    pass

s = Student("Anish")

print(s.name)
```

### Output

```python
Anish
```

---

# Using `super()`

`super()` is used to call the parent class constructor or methods.

```python
class Person:

    def __init__(self, name):
        self.name = name

class Student(Person):

    def __init__(self, name, roll):
        super().__init__(name)
        self.roll = roll

s = Student("Anish", 101)

print(s.name)
print(s.roll)
```

### Output

```python
Anish
101
```

---

# Method Overriding

Child class can redefine a parent method.

```python
class Animal:

    def sound(self):
        print("Animal Sound")

class Dog(Animal):

    def sound(self):
        print("Bark")

d = Dog()

d.sound()
```

### Output

```python
Bark
```

---

# Types of Inheritance

## 1. Single Inheritance

```text
Parent
   |
 Child
```

```python
class A:
    pass

class B(A):
    pass
```

---

## 2. Multiple Inheritance

One child inherits from multiple parents.

```text
A      B
 \    /
   C
```

```python
class A:

    def show(self):
        print("Class A")

class B:

    def display(self):
        print("Class B")

class C(A, B):
    pass

obj = C()

obj.show()
obj.display()
```

### Output

```python
Class A
Class B
```

---

## 3. Multilevel Inheritance

```text
A
|
B
|
C
```

```python
class A:

    def show(self):
        print("Class A")

class B(A):
    pass

class C(B):
    pass

obj = C()

obj.show()
```

### Output

```python
Class A
```

---

## 4. Hierarchical Inheritance

```text
      Parent
      /   \
 Child1  Child2
```

```python
class Parent:

    def show(self):
        print("Parent")

class Child1(Parent):
    pass

class Child2(Parent):
    pass
```

---

## 5. Hybrid Inheritance

Combination of multiple inheritance types.

```text
      A
     / \
    B   C
     \ /
      D
```

Python supports hybrid inheritance.

---

# Method Resolution Order (MRO)

When multiple inheritance is used, Python follows MRO to decide which method to call.

```python
class A:

    def show(self):
        print("A")

class B(A):
    pass

class C(A):
    pass

class D(B, C):
    pass

d = D()

d.show()
```

### Output

```python
A
```

Check MRO:

```python
print(D.mro())
```

---

# `issubclass()`

Checks whether a class is derived from another class.

```python
class A:
    pass

class B(A):
    pass

print(issubclass(B, A))
```

### Output

```python
True
```

---

# `isinstance()`

Checks whether an object belongs to a class.

```python
class A:
    pass

obj = A()

print(isinstance(obj, A))
```

### Output

```python
True
```

---

# Advantages of Inheritance

✅ Code Reusability

✅ Easy Maintenance

✅ Extensibility

✅ Supports Polymorphism

✅ Better Code Organization

---

# Real-Life Example

```python
class Vehicle:

    def start(self):
        print("Vehicle Started")

class Car(Vehicle):

    def drive(self):
        print("Car Driving")

c = Car()

c.start()
c.drive()
```

### Output

```python
Vehicle Started
Car Driving
```

---

# Parent vs Child Class

| Parent Class      | Child Class   |
| ----------------- | ------------- |
| Base Class        | Derived Class |
| Provides Features | Uses Features |
| General           | Specific      |

---

# Interview / Exam Definition

### Inheritance

Inheritance is an OOP feature that allows a class to acquire the properties and methods of another class. The class that inherits is called the **Child (Derived) Class**, and the class being inherited from is called the **Parent (Base) Class**.

### Example

```python
class Animal:

    def sound(self):
        print("Animal Sound")

class Dog(Animal):
    pass

d = Dog()

d.sound()
```

### Output

```python
Animal Sound
```

### Types of Inheritance

1. Single Inheritance
2. Multiple Inheritance
3. Multilevel Inheritance
4. Hierarchical Inheritance
5. Hybrid Inheritance

### Common Viva Question

**Q: Why do we use inheritance?**

**Answer:**
Inheritance is used to reuse existing code, reduce duplication, and create a hierarchical relationship between classes. It improves maintainability and supports polymorphism.


# Abstraction in Python

## What is Abstraction?

**Abstraction** means **hiding implementation details** and showing only the essential features to the user.

The user knows **what an object does**, but not **how it does it**.

---

# Real-Life Example

### ATM Machine

When you withdraw money:

* You enter the PIN.
* Select amount.
* Get cash.

You don't know:

* How the bank server processes the request.
* How the database is updated.
* How security checks happen.

These details are hidden.

This is **Abstraction**.

---

# Another Example

### Car

You know:

```text
start()
stop()
accelerate()
```

You don't know:

```text
Engine mechanism
Fuel injection
Gear calculations
```

The complex implementation is hidden.

---

# Why Use Abstraction?

✅ Hides complexity

✅ Improves security

✅ Makes code easier to maintain

✅ Reduces code dependency

✅ Provides a clear interface

---

# Abstraction in Python

Python provides abstraction using the **ABC (Abstract Base Class)** module.

```python
from abc import ABC, abstractmethod
```

---

# Abstract Class

An abstract class is a class that contains one or more abstract methods.

It cannot be instantiated directly.

```python
from abc import ABC

class Shape(ABC):
    pass
```

---

# Abstract Method

An abstract method is a method declared but not implemented.

```python
from abc import ABC, abstractmethod

class Shape(ABC):

    @abstractmethod
    def area(self):
        pass
```

---

# Complete Example

```python
from abc import ABC, abstractmethod

class Shape(ABC):

    @abstractmethod
    def area(self):
        pass

class Circle(Shape):

    def area(self):
        return 3.14 * 5 * 5

c = Circle()

print(c.area())
```

### Output

```python
78.5
```

---

# Cannot Create Object of Abstract Class

```python
from abc import ABC, abstractmethod

class Shape(ABC):

    @abstractmethod
    def area(self):
        pass

s = Shape()
```

### Output

```python
TypeError:
Can't instantiate abstract class Shape
```

---

# Multiple Abstract Methods

```python
from abc import ABC, abstractmethod

class Vehicle(ABC):

    @abstractmethod
    def start(self):
        pass

    @abstractmethod
    def stop(self):
        pass
```

---

# Implementing Abstract Methods

```python
from abc import ABC, abstractmethod

class Vehicle(ABC):

    @abstractmethod
    def start(self):
        pass

class Car(Vehicle):

    def start(self):
        print("Car Started")

c = Car()

c.start()
```

### Output

```python
Car Started
```

---

# What Happens if Child Doesn't Implement Abstract Method?

```python
from abc import ABC, abstractmethod

class Vehicle(ABC):

    @abstractmethod
    def start(self):
        pass

class Car(Vehicle):
    pass

c = Car()
```

### Output

```python
TypeError
```

Because the abstract method is not implemented.

---

# Abstraction vs Encapsulation

| Abstraction           | Encapsulation               |
| --------------------- | --------------------------- |
| Hides implementation  | Hides data                  |
| Focuses on "What"     | Focuses on "How"            |
| Uses Abstract Classes | Uses Private Variables      |
| Achieved using ABC    | Achieved using `__variable` |

---

# Example: Abstraction + Inheritance

```python
from abc import ABC, abstractmethod

class Animal(ABC):

    @abstractmethod
    def sound(self):
        pass

class Dog(Animal):

    def sound(self):
        print("Bark")

class Cat(Animal):

    def sound(self):
        print("Meow")

d = Dog()
c = Cat()

d.sound()
c.sound()
```

### Output

```python
Bark
Meow
```

---

# Real-Life Banking Example

```python
from abc import ABC, abstractmethod

class Bank(ABC):

    @abstractmethod
    def interest_rate(self):
        pass

class SBI(Bank):

    def interest_rate(self):
        print("7%")

class HDFC(Bank):

    def interest_rate(self):
        print("8%")

s = SBI()
h = HDFC()

s.interest_rate()
h.interest_rate()
```

### Output

```python
7%
8%
```

---

# Advantages of Abstraction

### 1. Security

Internal implementation is hidden.

### 2. Easy Maintenance

Implementation can change without affecting users.

### 3. Better Design

Provides a clean interface.

### 4. Flexibility

Different classes can implement methods differently.

---

# Diagram

```text
Abstract Class
      |
      v
    Shape
      |
  -----------
  |         |
Circle   Rectangle
```

---

# Interview / Exam Definition

### Abstraction

Abstraction is the process of hiding implementation details and exposing only the necessary functionality to the user. In Python, abstraction is achieved using abstract classes and abstract methods provided by the `abc` module.

### Example

```python
from abc import ABC, abstractmethod

class Shape(ABC):

    @abstractmethod
    def area(self):
        pass

class Circle(Shape):

    def area(self):
        return 78.5
```

### Key Points

* Use `ABC` to create abstract classes.
* Use `@abstractmethod` to declare abstract methods.
* Abstract classes cannot be instantiated.
* Child classes must implement all abstract methods.

### Common Viva Question

**Q: What is abstraction?**

**Answer:**
Abstraction is the process of hiding implementation details and showing only essential features to the user. It reduces complexity and improves security. In Python, abstraction is implemented using the `abc` module and abstract classes.



# Encapsulation in Python

## What is Encapsulation?

**Encapsulation** is the process of **wrapping data (variables) and methods (functions) into a single unit (class)** and restricting direct access to some data.

In simple words:

> **Encapsulation = Data Hiding + Data Protection**

---

# Real-Life Example

### Bank Account

You cannot directly change your bank balance.

❌ Wrong

```python
account.balance = 1000000
```

Instead, you use methods:

✅ Correct

```python
deposit()
withdraw()
check_balance()
```

The internal data is protected.

---

# Why Use Encapsulation?

✅ Data Security

✅ Data Hiding

✅ Better Control

✅ Easy Maintenance

✅ Prevents Unauthorized Access

---

# Simple Example

```python
class Student:

    def __init__(self):
        self.name = "Anish"

obj = Student()

print(obj.name)
```

### Output

```python
Anish
```

Here `name` is public and can be accessed from anywhere.

---

# Public Members

Variables and methods accessible everywhere.

```python
class Student:

    def __init__(self):
        self.name = "Anish"

obj = Student()

print(obj.name)
```

### Output

```python
Anish
```

---

# Protected Members (`_variable`)

A protected variable starts with a single underscore `_`.

```python
class Student:

    def __init__(self):
        self._name = "Anish"

obj = Student()

print(obj._name)
```

### Output

```python
Anish
```

⚠️ Protected members can still be accessed, but by convention they should not be accessed directly outside the class.

---

# Private Members (`__variable`)

A private variable starts with double underscores `__`.

```python
class Student:

    def __init__(self):
        self.__age = 20

obj = Student()

print(obj.__age)
```

### Output

```python
AttributeError
```

Python prevents direct access.

---

# Accessing Private Variables Using Methods

```python
class Student:

    def __init__(self):
        self.__age = 20

    def get_age(self):
        return self.__age

obj = Student()

print(obj.get_age())
```

### Output

```python
20
```

---

# Modifying Private Variables

```python
class Student:

    def __init__(self):
        self.__age = 20

    def set_age(self, age):
        self.__age = age

    def get_age(self):
        return self.__age

obj = Student()

obj.set_age(25)

print(obj.get_age())
```

### Output

```python
25
```

---

# Name Mangling

Python internally changes private variable names.

```python
class Student:

    def __init__(self):
        self.__age = 20
```

Internally becomes:

```python
_Student__age
```

So:

```python
obj._Student__age
```

can access it.

```python
class Student:

    def __init__(self):
        self.__age = 20

obj = Student()

print(obj._Student__age)
```

### Output

```python
20
```

⚠️ This should generally be avoided.

---

# Getter and Setter Methods

## Getter

Used to read data.

```python
def get_age(self):
    return self.__age
```

---

## Setter

Used to modify data.

```python
def set_age(self, age):
    self.__age = age
```

---

# Example Using Getters and Setters

```python
class Employee:

    def __init__(self):
        self.__salary = 50000

    def get_salary(self):
        return self.__salary

    def set_salary(self, salary):
        if salary > 0:
            self.__salary = salary

e = Employee()

e.set_salary(70000)

print(e.get_salary())
```

### Output

```python
70000
```

---

# Encapsulation Using Properties

Python provides `@property`.

```python
class Student:

    def __init__(self):
        self.__age = 20

    @property
    def age(self):
        return self.__age

obj = Student()

print(obj.age)
```

### Output

```python
20
```

---

# Example with Setter Property

```python
class Student:

    def __init__(self):
        self.__age = 20

    @property
    def age(self):
        return self.__age

    @age.setter
    def age(self, value):
        self.__age = value

obj = Student()

obj.age = 25

print(obj.age)
```

### Output

```python
25
```

---

# Encapsulation vs Abstraction

| Encapsulation                  | Abstraction               |
| ------------------------------ | ------------------------- |
| Hides Data                     | Hides Implementation      |
| Focuses on Security            | Focuses on Simplicity     |
| Uses Private Variables         | Uses Abstract Classes     |
| Achieved with Access Modifiers | Achieved using ABC Module |

---

# Real-Life Example

```python
class BankAccount:

    def __init__(self):
        self.__balance = 1000

    def deposit(self, amount):
        self.__balance += amount

    def get_balance(self):
        return self.__balance

acc = BankAccount()

acc.deposit(500)

print(acc.get_balance())
```

### Output

```python
1500
```

The balance cannot be modified directly.

---

# Interview / Exam Definition

### Encapsulation

Encapsulation is the process of binding data and methods into a single unit (class) and restricting direct access to the data. It protects data from unauthorized access and modification.

### Example

```python
class Student:

    def __init__(self):
        self.__age = 20

    def get_age(self):
        return self.__age
```

### Key Points

* Public → `variable`
* Protected → `_variable`
* Private → `__variable`
* Getter → Read data
* Setter → Modify data

### Common Viva Question

**Q: What is encapsulation?**

**Answer:**
Encapsulation is an OOP principle that bundles data and methods into a class and restricts direct access to the data using private members. It improves security and data integrity.

### Memory Trick

```text
Encapsulation = Data Hiding
Abstraction   = Implementation Hiding
Inheritance   = Code Reuse
Polymorphism  = Many Forms
```

These four are known as the **Four Pillars of OOP** and are among the most important topics for **BCA exams, Python interviews, and software development interviews**.


# Iterators in Python

## What is an Iterator?

An **Iterator** is an object that allows us to traverse (iterate through) elements of a collection one by one.

Examples of iterable objects:

* List
* Tuple
* String
* Set
* Dictionary

---

# Real-Life Example

Imagine a TV remote.

* `next` button → Move to the next channel.
* You don't get all channels at once.
* You get one channel at a time.

This is how an iterator works.

---

# Iterable vs Iterator

| Iterable                      | Iterator                   |
| ----------------------------- | -------------------------- |
| Can be looped over            | Produces values one by one |
| Examples: List, Tuple, String | Created using `iter()`     |
| Has `__iter__()`              | Has `__next__()`           |

---

# Creating an Iterator

Use `iter()`.

```python
numbers = [10, 20, 30]

it = iter(numbers)

print(it)
```

---

# Getting Values Using `next()`

```python
numbers = [10, 20, 30]

it = iter(numbers)

print(next(it))
print(next(it))
print(next(it))
```

### Output

```python
10
20
30
```

Each call to `next()` returns the next element.

---

# StopIteration Exception

After all elements are consumed:

```python
numbers = [10, 20]

it = iter(numbers)

print(next(it))
print(next(it))
print(next(it))
```

### Output

```python
10
20

StopIteration
```

---

# Iterator with String

```python
text = "Python"

it = iter(text)

print(next(it))
print(next(it))
```

### Output

```python
P
y
```

---

# Iterator with Tuple

```python
t = (1, 2, 3)

it = iter(t)

print(next(it))
```

### Output

```python
1
```

---

# How `for` Loop Uses Iterators

```python
nums = [1, 2, 3]

for x in nums:
    print(x)
```

Internally Python does:

```python
it = iter(nums)

while True:
    try:
        item = next(it)
        print(item)
    except StopIteration:
        break
```

---

# Creating a Custom Iterator

An iterator class must implement:

1. `__iter__()`
2. `__next__()`

---

## Example

```python
class Count:

    def __init__(self, max):
        self.max = max
        self.current = 1

    def __iter__(self):
        return self

    def __next__(self):

        if self.current <= self.max:
            value = self.current
            self.current += 1
            return value

        raise StopIteration

obj = Count(5)

for i in obj:
    print(i)
```

### Output

```python
1
2
3
4
5
```

---

# Understanding `__iter__()`

```python
def __iter__(self):
    return self
```

Returns the iterator object itself.

---

# Understanding `__next__()`

```python
def __next__(self):
```

Called every time `next()` is executed.

Must:

* Return next value.
* Raise `StopIteration` when finished.

---

# Using Iterator Manually

```python
obj = Count(3)

it = iter(obj)

print(next(it))
print(next(it))
print(next(it))
```

### Output

```python
1
2
3
```

---

# Infinite Iterator Example

```python
class Infinite:

    def __init__(self):
        self.num = 1

    def __iter__(self):
        return self

    def __next__(self):
        self.num += 1
        return self.num
```

⚠️ No `StopIteration`, so it runs forever.

---

# Advantages of Iterators

✅ Memory Efficient

✅ Lazy Evaluation

✅ Faster for Large Data

✅ Process Data One by One

---

# Example: Large Data Processing

```python
nums = range(1000000)

it = iter(nums)

print(next(it))
```

Only one value is loaded at a time.

---

# Iterator Protocol

To become an iterator:

```text
Object
  |
  +--> __iter__()
  |
  +--> __next__()
```

Both methods are required.

---

# Common Built-in Iterators

```python
iter(list)
iter(tuple)
iter(string)
iter(set)
iter(dict)
iter(range())
```

Example:

```python
nums = [1, 2, 3]

it = iter(nums)

print(next(it))
```

---

# Iterator vs Generator

| Iterator                                 | Generator        |
| ---------------------------------------- | ---------------- |
| Uses class                               | Uses function    |
| Implements `__iter__()` and `__next__()` | Uses `yield`     |
| More code                                | Less code        |
| Harder to create                         | Easier to create |

---

# Real-Life Example

```python
students = ["Anish", "Rahul", "Amit"]

it = iter(students)

print(next(it))
print(next(it))
```

### Output

```python
Anish
Rahul
```

---

# Interview / Exam Definition

### Iterator

An iterator is an object that allows sequential access to elements of a collection one at a time. It follows the iterator protocol by implementing the `__iter__()` and `__next__()` methods.

### Example

```python
nums = [1, 2, 3]

it = iter(nums)

print(next(it))
```

### Output

```python
1
```

### Key Points

* `iter()` → Creates iterator.
* `next()` → Gets next element.
* `StopIteration` → End of iteration.
* Custom iterator requires:

  * `__iter__()`
  * `__next__()`

### Common Viva Question

**Q: What is the difference between an iterable and an iterator?**

**Answer:**

* **Iterable:** Object that can be iterated over (List, Tuple, String).
* **Iterator:** Object that returns elements one by one using `next()`.

### Memory Trick

```text
Iterable → iter() → Iterator → next() → Value
```

This topic is very important for **Python interviews, advanced Python, generators, and data processing**.


# Exception Handling in Python

## What is an Exception?

An **Exception** is an error that occurs during the execution of a program.

Without exception handling, the program stops immediately when an error occurs.

### Example

```python
a = 10
b = 0

print(a / b)
```

### Output

```python
ZeroDivisionError: division by zero
```

The program crashes.

---

# What is Exception Handling?

Exception handling allows us to handle errors gracefully without stopping the program.

Python uses:

```python
try
except
else
finally
```

---

# try and except

```python
try:
    risky_code
except:
    handling_code
```

### Example

```python
try:
    a = 10
    b = 0

    print(a / b)

except ZeroDivisionError:
    print("Cannot divide by zero")
```

### Output

```python
Cannot divide by zero
```

---

# Multiple Exceptions

```python
try:
    num = int(input("Enter Number: "))
    result = 10 / num

except ValueError:
    print("Invalid Input")

except ZeroDivisionError:
    print("Cannot divide by zero")
```

---

# Generic Exception

```python
try:
    x = int("abc")

except Exception as e:
    print("Error:", e)
```

### Output

```python
Error: invalid literal for int()
```

`e` stores the error message.

---

# else Block

`else` runs only if no exception occurs.

```python
try:
    num = 10

    print(num)

except:
    print("Error")

else:
    print("No Error")
```

### Output

```python
10
No Error
```

---

# finally Block

`finally` always executes whether an exception occurs or not.

```python
try:
    print("Try Block")

except:
    print("Exception")

finally:
    print("Finally Block")
```

### Output

```python
Try Block
Finally Block
```

---

# Complete Example

```python
try:
    a = 10
    b = 2

    print(a / b)

except ZeroDivisionError:
    print("Division Error")

else:
    print("Success")

finally:
    print("Program Ended")
```

### Output

```python
5.0
Success
Program Ended
```

---

# Raising Exceptions

Use `raise` to generate exceptions manually.

```python
age = -5

if age < 0:
    raise ValueError("Age cannot be negative")
```

### Output

```python
ValueError: Age cannot be negative
```

---

# Custom Exception

Create your own exception class.

```python
class InvalidAgeError(Exception):
    pass

age = -1

if age < 0:
    raise InvalidAgeError("Invalid Age")
```

---

# Common Built-in Exceptions

| Exception         | Description            |
| ----------------- | ---------------------- |
| ZeroDivisionError | Division by zero       |
| ValueError        | Wrong value type       |
| TypeError         | Wrong data type        |
| IndexError        | Invalid list index     |
| KeyError          | Missing dictionary key |
| NameError         | Variable not defined   |
| FileNotFoundError | File does not exist    |

---

# Example: IndexError

```python
nums = [10, 20, 30]

try:
    print(nums[5])

except IndexError:
    print("Index Out of Range")
```

### Output

```python
Index Out of Range
```

---

# Example: File Handling Exception

```python
try:
    file = open("data.txt")

except FileNotFoundError:
    print("File Not Found")
```

---

# Nested try-except

```python
try:

    try:
        print(10 / 0)

    except ZeroDivisionError:
        print("Inner Exception")

except:
    print("Outer Exception")
```

### Output

```python
Inner Exception
```

---

# Advantages of Exception Handling

✅ Prevents program crash

✅ Improves user experience

✅ Easier debugging

✅ Makes code robust

✅ Handles unexpected situations

---

# Flow of Exception Handling

```text
Start
  |
 Try Block
  |
Exception?
 /      \
Yes      No
 |        |
Except   Else
  \      /
   Finally
      |
     End
```

---

# Real-Life Example

```python
try:
    amount = int(input("Enter Amount: "))

    if amount < 0:
        raise ValueError

except ValueError:
    print("Invalid Amount")

else:
    print("Transaction Successful")
```

---

# Interview / Exam Definition

### Exception Handling

Exception handling is a mechanism used to handle runtime errors in a program without terminating its execution. Python uses `try`, `except`, `else`, and `finally` blocks to manage exceptions.

### Example

```python
try:
    print(10 / 0)

except ZeroDivisionError:
    print("Cannot Divide by Zero")
```

### Output

```python
Cannot Divide by Zero
```

### Keywords

* `try` → Code that may cause an error.
* `except` → Handles the error.
* `else` → Runs if no error occurs.
* `finally` → Always executes.
* `raise` → Creates an exception manually.

### Common Viva Question

**Q: What is the difference between `else` and `finally`?**

| else                               | finally       |
| ---------------------------------- | ------------- |
| Runs only when no exception occurs | Runs always   |
| Optional                           | Optional      |
| Executed before finally            | Executed last |

### Memory Trick

```text
try     → Risky Code
except  → Handle Error
else    → No Error
finally → Always Run
```

This is one of the most important Python topics for **BCA exams, interviews, file handling, database programming, and real-world applications**.


# Built-in Exceptions in Python

## What are Built-in Exceptions?

**Built-in exceptions** are predefined error types provided by Python that occur during program execution when something goes wrong.

Python automatically raises these errors.

---

# Why They Are Important?

* Help identify errors quickly
* Make debugging easier
* Used in `try-except` blocks
* Improve program reliability

---

# Common Built-in Exceptions

## 1. ZeroDivisionError

Occurs when dividing by zero.

```python id="h7x9mk"
print(10 / 0)
```

### Output

```python id="z3n1pa"
ZeroDivisionError: division by zero
```

---

## 2. ValueError

Occurs when value is correct type but invalid.

```python id="0v2gsk"
num = int("abc")
```

### Output

```python id="g1r8yw"
ValueError: invalid literal for int()
```

---

## 3. TypeError

Occurs when wrong data type is used.

```python id="p8kq0n"
print("10" + 5)
```

### Output

```python id="t6v2xc"
TypeError: can only concatenate str (not "int")
```

---

## 4. IndexError

Occurs when list index is out of range.

```python id="m2lq9e"
nums = [1, 2, 3]

print(nums[5])
```

### Output

```python id="q8w4dc"
IndexError: list index out of range
```

---

## 5. KeyError

Occurs when dictionary key is not found.

```python id="y7r3xn"
data = {"name": "Anish"}

print(data["age"])
```

### Output

```python id="k1s8qp"
KeyError: 'age'
```

---

## 6. NameError

Occurs when variable is not defined.

```python id="n9x0vc"
print(x)
```

### Output

```python id="a4t7pm"
NameError: name 'x' is not defined
```

---

## 7. AttributeError

Occurs when invalid attribute is accessed.

```python id="d6k1sm"
text = "hello"

text.append("world")
```

### Output

```python id="r9w2qd"
AttributeError: 'str' object has no attribute 'append'
```

---

## 8. FileNotFoundError

Occurs when file does not exist.

```python id="b3z8qa"
open("file.txt")
```

### Output

```python id="c7p1mv"
FileNotFoundError: No such file or directory
```

---

## 9. ImportError

Occurs when module cannot be imported.

```python id="h1n6xp"
import unknown_module
```

### Output

```python id="x9v3ld"
ImportError: No module named 'unknown_module'
```

---

## 10. ModuleNotFoundError

A specific ImportError.

```python id="k8q2zm"
import fake_module
```

---

## 11. OverflowError

Occurs when a number is too large.

```python id="t5r9yc"
import math

print(math.exp(1000))
```

---

## 12. RecursionError

Occurs when recursion limit is exceeded.

```python id="u3d7va"
def func():
    func()

func()
```

---

## 13. StopIteration

Occurs in iterators when no more items are left.

```python id="j1m8ql"
it = iter([1])

print(next(it))
print(next(it))
```

---

## 14. KeyboardInterrupt

Occurs when user manually stops program (Ctrl + C).

---

## 15. MemoryError

Occurs when system runs out of memory.

---

# Handling Built-in Exceptions

```python id="q2w8ld"
try:
    num = int("abc")

except ValueError:
    print("Invalid value entered")
```

### Output

```python id="z6m1rt"
Invalid value entered
```

---

# Multiple Exceptions Handling

```python id="x7n2kp"
try:
    a = 10 / 0

except (ZeroDivisionError, ValueError) as e:
    print("Error:", e)
```

---

# Generic Exception Handling

```python id="v3p9sa"
try:
    print(x)

except Exception as e:
    print("Error:", e)
```

---

# Most Important Built-in Exceptions (Exam List)

| Exception         | Meaning              |
| ----------------- | -------------------- |
| ZeroDivisionError | Divide by zero       |
| ValueError        | Invalid value        |
| TypeError         | Wrong type           |
| IndexError        | Invalid index        |
| KeyError          | Missing key          |
| NameError         | Variable not defined |
| FileNotFoundError | File not found       |

---

# Real-Life Example

```python id="c9k3wd"
try:
    age = int(input("Enter age: "))

    if age < 0:
        raise ValueError("Invalid Age")

except ValueError as e:
    print("Error:", e)
```

---

# Interview / Exam Definition

### Built-in Exceptions

Built-in exceptions are predefined error classes in Python that are automatically raised when an error occurs during program execution. These exceptions help in identifying and handling runtime errors.

### Example

```python id="m8x2ta"
try:
    print(10 / 0)

except ZeroDivisionError:
    print("Cannot divide by zero")
```

### Output

```python id="d3k7wv"
Cannot divide by zero
```

---

# Key Points

* Python has many built-in exceptions.
* They all inherit from the base class `Exception`.
* Used with `try-except`.
* Helps in debugging and safe program execution.

---

# Memory Trick

```text id="f1q9lv"
ZeroDivisionError → / 0
ValueError        → wrong value
TypeError         → wrong type
IndexError        → list index
KeyError          → dict key
NameError         → variable missing
FileNotFoundError → file missing
```

---

If you want, I can next give you:
👉 **File Handling in Python (very important for exams + interviews)**
👉 or a **full revision sheet of all Python OOP + Exceptions in 1 page**

# User-Defined Exceptions in Python

## What are User-Defined Exceptions?

**User-defined exceptions** are custom error classes created by the programmer to handle specific situations that are not covered by built-in exceptions.

👉 In simple words:

> You create your own error type based on your program needs.

---

# Why Use User-Defined Exceptions?

✔ Handle application-specific errors
✔ Make code more readable
✔ Better debugging
✔ Improve control over program flow
✔ Used in real-world applications (banking, login systems, etc.)

---

# How to Create User-Defined Exception?

In Python, we create a custom exception by inheriting the built-in `Exception` class.

---

# Basic Syntax

```python
class MyException(Exception):
    pass
```

---

# Simple Example

```python id="u2k9mp"
class MyError(Exception):
    pass

try:
    raise MyError("Something went wrong")

except MyError as e:
    print(e)
```

### Output

```python id="x8k2lv"
Something went wrong
```

---

# Real Example: Age Validation

```python id="a9p3dq"
class InvalidAgeError(Exception):
    pass

age = int(input("Enter age: "))

try:
    if age < 18:
        raise InvalidAgeError("Age must be 18 or above")

    print("Valid Age")

except InvalidAgeError as e:
    print("Error:", e)
```

---

# Example: Bank System

```python id="b7n4rs"
class InsufficientBalanceError(Exception):
    pass

balance = 1000
withdraw = int(input("Enter amount: "))

try:
    if withdraw > balance:
        raise InsufficientBalanceError("Not enough balance")

    balance -= withdraw
    print("Remaining Balance:", balance)

except InsufficientBalanceError as e:
    print("Error:", e)
```

---

# Example: Login System

```python id="c5t8yw"
class LoginError(Exception):
    pass

username = input("Enter username: ")

try:
    if username != "admin":
        raise LoginError("Invalid Username")

    print("Login Successful")

except LoginError as e:
    print("Error:", e)
```

---

# Custom Exception with Constructor

You can also pass custom messages.

```python id="d3k9xn"
class AgeError(Exception):

    def __init__(self, message):
        super().__init__(message)

try:
    age = -5

    if age < 0:
        raise AgeError("Age cannot be negative")

except AgeError as e:
    print(e)
```

---

# Multiple Custom Exceptions

```python id="e8q2wp"
class LowBalanceError(Exception):
    pass

class InvalidAmountError(Exception):
    pass

amount = int(input("Enter amount: "))

try:
    if amount < 0:
        raise InvalidAmountError("Amount cannot be negative")

    if amount > 1000:
        raise LowBalanceError("Insufficient balance")

except (LowBalanceError, InvalidAmountError) as e:
    print("Error:", e)
```

---

# Difference: Built-in vs User-defined Exceptions

| Built-in Exceptions            | User-defined Exceptions       |
| ------------------------------ | ----------------------------- |
| Predefined by Python           | Created by programmer         |
| Example: ValueError, TypeError | Example: AgeError, LoginError |
| General errors                 | Application-specific errors   |
| Automatically raised           | Manually raised using `raise` |

---

# Flow of User-Defined Exception

```text id="f6w2zn"
Condition Check
      ↓
Raise Custom Exception
      ↓
except block handles it
      ↓
Program continues safely
```

---

# Real-World Use Cases

✔ Banking systems (insufficient balance)
✔ Login systems (invalid credentials)
✔ E-commerce (out of stock)
✔ Form validation (invalid input)
✔ Exams systems (invalid marks)

---

# Interview / Exam Definition

### User-Defined Exception

User-defined exceptions are custom exception classes created by the programmer by inheriting the built-in `Exception` class. They are used to handle application-specific error conditions.

---

### Example

```python id="g2m8rt"
class MyError(Exception):
    pass

try:
    raise MyError("Custom Error Occurred")

except MyError as e:
    print(e)
```

### Output

```python id="h7n1qp"
Custom Error Occurred
```

---

# Key Points

✔ Created using `class`
✔ Inherit from `Exception`
✔ Raised using `raise` keyword
✔ Handled using `try-except`
✔ Used for custom business logic

---

# Memory Trick

```text id="i4p9ld"
Built-in → Python gives it
User-defined → You create it
```

---

If you want next, I can teach you:

👉 File Handling (VERY IMPORTANT for exams + interviews)
👉 OR Complete Python Revision Sheet (OOP + Exceptions + Collections in 1 page)
