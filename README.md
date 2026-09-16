# 📊 Interactive Personal Data Collector

## **Author:** Drashti Vasani
## **Course/Project:** Python Practical Assignment

A Python-based console application designed to collect user input, handle different data types (`str`, `int`, `float`), inspect object metadata using `type()` and `id()`, and perform a basic arithmetic calculation.

---

## 🎯 Project Objectives

* 👤 **User Input Handling:** Collect personal information dynamically using `input()`.
* 🔍 **Data Type Inspection:** Display the data type and memory address of variables using `type()` and `id()`.
* 🧮 **Basic Calculation:** Calculate the user's approximate birth year based on their age.

---

## ✨ Features & Functionality

### 1. 📝 Data Collection

The program collects:

* Name as a string
* Age as an integer
* Height as a floating-point number
* Favorite number as an integer

### 2. 🔬 Data Type & Memory Inspection

The program displays each entered value along with:

* Its Python data type using `type()`
* Its object identity using `id()`

### 3. 📅 Age-to-Year Calculator

The program calculates the approximate birth year using:

```python
birth_year = 2026 - age
```

---

## 💻 Technologies Used

* Python 3
* Visual Studio Code
* Git & GitHub

---

## 📚 Concepts Covered

* `input()`
* Variables
* `str`, `int`, `float`
* Type conversion
* Built-in functions
* `type()`
* `id()`
* Arithmetic operations
* Console output

---

## 📂 Project Files

```text
Project-1/
│
├── Fundamental_Booster.py
├── README.md
└── output.png
```

---

## 🖥️ Sample Output

```text
Welcome to the Interactive Personal Data Collector

Please enter your name: drashti
Please enter your age: 20
Please enter your height in meters: 1.69
Please enter your favorite number: 12

Thank you for providing your information!

Name: drashti (type: <class 'str'>, memory address: 3166906178016)
Age: 20 (type: <class 'int'>, memory address: 140726799746744)
Height: 1.69 (type: <class 'float'>, memory address: 3166903186320)
Favorite Number: 12 (type: <class 'int'>, memory address: 140726799746488)

Your birth year is approximately: 2006 (based on your age of 20)

Thank you for using the Personal Data Collector. Goodbye!
```

---



