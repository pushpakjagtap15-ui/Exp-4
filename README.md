# 🧪 Experiment 4: Study of Tuples in Python

## Author
- **Name:** Pushpak J  
- **PRN:** 25070123148  
- **Branch:** F.Y. E&TC (2025-29)  
- **Batch:** A1  
- **Subject:** Exploratory Data Analysis With Python  

---

## Aim
To study and understand the properties, syntax, and practical applications of Tuples in Python for data handling.

---

## Objectives
- Understand the creation and indexing of Tuples  
- Explore the immutability of Tuples and how it differs from Lists  
- Perform operations like slicing, reversing, and concatenation on Tuples  
- Apply Tuples in solving real-world data scenarios (Exam results and Attendance tracking)  

---

## Theory

### 1. What is a Tuple?
A **Tuple** is a built-in Python data type used to store multiple items in a single variable.  
- Unlike lists, tuples are **ordered and immutable**, meaning their elements cannot be changed or replaced once assigned.  
- **Syntax:** `my_tuple = (1, "hello", 3.5)`

### 2. Key Characteristics
- **Immutability:** Tuples do not support item assignment (`tuple[1] = "new"` → raises `TypeError`)  
- **Diverse Data Types:** Can store strings, booleans, integers, sets, lists, or other tuples  
- **Indexing & Slicing:** Supports positive and negative indexing, as well as slicing (`[start:stop:step]`)  

---

## Practical Implementation

###  Tuple Basics

t1 = (10, 20, 30, "Python")
print(len(t1))       # Length → 4
print(type(t1))      # Type → <class 'tuple'>
 Immutability Test

t2 = (1, 2, 3)
# Attempting modification
# t2[1] = 5   # ❌ TypeError: 'tuple' object does not support item assignment
 Concatenation

t3 = (1, 2, 3)
t4 = (4, 5, 6)
t5 = t3 + t4
print(t5)   # (1, 2, 3, 4, 5, 6)
 Slicing & Reversing

t6 = (10, 20, 30, 40, 50)
print(t6[1:4])    # (20, 30, 40)
print(t6[::-1])   # (50, 40, 30, 20, 10)
Real-world Applications
* Exam Results

exam_result = ("Maths", 85, "A")
subject, marks, grade = exam_result

if marks >= 75:
    print("Distinction in", subject)
* Attendance Tracking

attendance = ("P", "A", "P", "P", "A", "P", "P")
present_days = attendance.count("P")
absent_days = attendance.count("A")

print("Present:", present_days)
print("Absent:", absent_days)





Conclusion
Through this experiment, the fundamental properties of Tuples were studied.

The concept of immutability was verified through error handling.

Tuples proved useful in managing fixed datasets such as exam records and employee attendance.

Their reliability and efficiency make them an essential tool in Python data handling.
