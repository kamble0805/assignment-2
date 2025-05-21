# Assignment 2 – Module 3: Control Structures in Python

This repository contains two Python scripts developed as part of Assignment 2 for the **Python Tutedude Course – Module 3**.

---

## 📘 Task 1: Check if a Number is Even or Odd

**Description**  
This Python script prompts the user to input a number and checks whether the number is **even** or **odd** using an `if-else` control structure.

**Functionality**
- Takes numeric input from the user.
- Evaluates the modulus using `num % 2`.
- Prints `"even"` if divisible by 2, else prints `"odd"`.

**Code Snippet:**
```python
num = float(input("Enter a number: "))
if num % 2 == 0:
    print("The number",num," is even")
else:
    print("The number",num," is odd") 
```
---
## 📘 Task 2: Sum of Integers from 1 to 50 Using a Loop

**Description**  
This script calculates the sum of integers from 1 to 49 (based on the current loop range).

Note: Python's range(1, 50) includes 1 to 49. If the sum should include 50, use range(1, 51).

**Functionality**
- Initializes a sum variable.

- Iterates using a for loop.

- Adds each number in the range to the sum.

- Displays the final result.

**Code Snippet:**
```python
sum = 0
for i in range(1,50):
    sum = sum + i
print("The sum of 1 to 50 is",sum)

```


