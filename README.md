# Python Fundamentals Drill

A practical, business-oriented Python fundamentals revision project designed to build strong syntax fluency before moving into Data Analysis, Data Science, and Machine Learning.

This project focuses on writing Python from scratch through short, progressively challenging exercises based on realistic analytics and business scenarios.

---

## Objectives

The primary objective is to make core Python syntax feel natural and fast to write.

This drill focuses on:

* Building Python syntax fluency
* Understanding variables and data types
* Practicing arithmetic and comparison operators
* Understanding division, floor division, and modulus
* Working with strings and string methods
* Converting between data types
* Writing Boolean expressions
* Understanding truthiness
* Using user input
* Formatting output with f-strings
* Debugging basic Python errors
* Applying Python to business metrics
* Developing analytical thinking through small business problems

The goal is not simply to memorize syntax, but to understand how Python can be used to solve practical analytical problems.

---

## Topics Covered

### 1. Variables & Basic Syntax

Practice creating and working with:

* Strings
* Integers
* Floats
* Variables
* Basic output

Example business variables include:

```python
revenue = 150000
cost = 95000
orders = 125
```

---

### 2. Arithmetic Operators

The project covers:

```text
+
-
*
/
//
%
```

Special attention is given to understanding the difference between:

* Regular division `/`
* Floor division `//`
* Modulus `%`

These concepts are important for both general programming and analytical calculations.

---

### 3. Business Metrics

Python is applied to common business and web analytics metrics including:

* Profit
* Profit margin
* Conversion rate
* Average Order Value (AOV)
* Marketing cost per order
* Revenue after marketing cost

For example:

```python
conversion_rate = (orders / visitors) * 100
```

This connects programming fundamentals with real-world Data Analyst workflows.

---

### 4. Strings & Data Cleaning

The drill introduces common string-cleaning operations:

```python
.strip()
.lower()
.title()
.replace()
.split()
```

Examples include cleaning:

```text
"   SHORYA BISHT   "
```

into:

```text
"Shorya Bisht"
```

and extracting information from structured strings such as:

```text
LAP-2026-PRO-15
```

---

### 5. Type Conversion

Real-world data frequently arrives in the wrong format.

The exercises therefore cover:

```python
int()
float()
str()
```

For example:

```python
orders = int("12")
revenue = int("240000")
```

This prepares for the type-conversion challenges encountered later with CSV files, APIs, databases, and datasets.

---

### 6. Boolean Logic

The project introduces analytical conditions using:

```python
==
!=
>
<
>=
<=
and
or
```

Examples include checking whether:

* A customer belongs to a particular age range
* Revenue exceeds a threshold
* Conversion rate falls below a target
* Multiple business conditions are simultaneously satisfied

---

### 7. Truthiness

The drill explores how Python evaluates values as `True` or `False`.

Examples include:

```python
bool(0)
bool(100)
bool("")
bool("Python")
bool([])
bool(None)
```

Understanding truthiness becomes particularly useful when working with missing values, conditions, filtering, and data-processing logic.

---

### 8. Input Handling

The project also introduces interactive Python programs using:

```python
input()
```

and demonstrates why user input often needs explicit type conversion.

Example:

```python
age = int(input("Enter your age: "))
salary = float(input("Enter your salary: "))
```

---

### 9. f-Strings

Formatted output is practiced using f-strings:

```python
print(f"Revenue: ₹{revenue}")
```

This provides a clean way to communicate analytical results.

---

### 10. Debugging

The exercises intentionally include common beginner mistakes involving:

* Incorrect data types
* String-number operations
* Incorrect mathematical operators
* Incorrect Boolean logic
* Incorrect formatting

The objective is to develop the ability to identify why code fails rather than simply memorizing corrected solutions.

---

## Final Business Challenge

The final exercises combine multiple fundamentals into realistic analytical scenarios.

One example evaluates an online store using:

```text
Visitors
Orders
Revenue
Marketing Cost
```

and calculates:

* Conversion Rate
* Average Order Value
* Marketing Cost per Order
* Revenue after Marketing Cost
* Whether post-marketing revenue exceeds a business threshold

This demonstrates how even basic Python can answer meaningful business questions.

---

## Key Learning Outcomes

After completing this drill, I strengthened my understanding of:

* Python variables
* Primitive data types
* Arithmetic operators
* Comparison operators
* Boolean logic
* Truthiness
* Type conversion
* String manipulation
* User input
* f-string formatting
* Basic debugging
* Business metric calculations
* Analytical problem solving

More importantly, the exercises helped connect Python syntax with the way analysts actually think about business data.

---

##  Techniques Practiced

```text
Variable Assignment
Arithmetic Operations
Floor Division
Modulus
Type Conversion
String Cleaning
String Extraction
Boolean Expressions
Chained Comparisons
Logical Operators
Truthiness
User Input
Formatted Strings
Basic Debugging
Business Metric Calculation
```

---

## Analytics Perspective

The project intentionally uses business and analytics examples rather than isolated programming exercises.

Instead of only calculating:

```python
10 + 20
```

the exercises ask questions such as:

* What is the conversion rate?
* What is the company's profit?
* What is the AOV?
* Did marketing generate enough revenue?
* Does a customer satisfy specific business criteria?
* Is a product or transaction value formatted correctly?

This approach creates a bridge between **Python programming and analytical decision-making**.

---

##  Python → Data Science Roadmap

This repository represents the fundamentals stage of my broader Python revision journey.

The progression is designed around:

```text
Python Fundamentals
        ↓
Data Structures
        ↓
Control Flow
        ↓
Functions
        ↓
Pythonic Python
        ↓
Exceptions
        ↓
Files & Modules
        ↓
Advanced Functions
        ↓
Object-Oriented Programming
        ↓
Python → ML Bridge
        ↓
Data Science & Machine Learning
```

The goal is to build programming fluency first, then use that foundation for practical Data Science and Machine Learning work.

---

## Why This Matters for Data Science

Strong Data Science skills require more than knowing machine-learning algorithms.

Before working with:

* Pandas
* NumPy
* Scikit-learn
* APIs
* Databases
* Machine Learning pipelines

it is important to be comfortable with Python itself.

This project focuses on that foundation.

---

## About Me

**Shorya Dev Bisht**

Data Analyst | Data Scientist | Web Analyst

I am building my skills across Python, SQL, Data Analytics, Web Analytics, Machine Learning, and business-focused problem solving.

### Connect With Me

* LinkedIn: https://www.linkedin.com/in/shorya-bisht-a20144349/
* GitHub: https://github.com/datascientistshorya
* Medium: https://medium.com/@its.shoryabisht

---

##  Project Philosophy

> Learn the syntax.
> Understand the logic.
> Apply it to business problems.
> Build the foundation for Data Science.

This project is intentionally practical: every concept should eventually become a tool for solving a real analytical problem.
