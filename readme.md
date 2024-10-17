# C++ Decision Making Statements and Loops - Experiment 6

This repository contains eight C++ programs that demonstrate the use of decision-making statements and loops. Each program is designed to help understand different control structures and their practical applications.

## Table of Contents

1. [Introduction](#introduction)
2. [Programs Overview](#programs-overview)
   - [Program 1: While Loop from 1 to 20](#program-1-while-loop-from-1-to-20)
   - [Program 2: Do-While Loop Example](#program-2-do-while-loop-example)
   - [Program 3: Flipped Floyd's Triangle](#program-3-flipped-floyds-triangle)
   - [Program 4: Floyd's Triangle](#program-4-floyds-triangle)
   - [Program 5: Password Check with While Loop](#program-5-password-check-with-while-loop)
   - [Program 6: Reverse Star Pattern](#program-6-reverse-star-pattern)
   - [Program 7: Star Pattern](#program-7-star-pattern)
   - [Program 8: Star Pyramid](#program-8-star-pyramid)
  
     # Algorithms

## Password Authenticator

### Algorithm

1. **Start.**  
2. **Initialize:**  
   - Set `pwd = 8761` (this is the correct password).  
   - Declare a variable `u_pwd` to store user input.  
3. **Input:**  
   - Display the message: `"Enter password: "`.  
   - Store user input in the `u_pwd` variable.  
4. **While Loop:**  
   - **Condition:** Run the loop while `pwd > 0`.
     - If `u_pwd` is **not equal** to `pwd`:
       - Display: `"Password is incorrect"`.
       - Display: `"Enter password again: "`.
       - Accept the new input and store it in `u_pwd`.
     - **Else:**
       - Display: `"Password is correct"`.
       - Break the loop.  
5. **End.**

---

## Half Pyramid

### Algorithm

1. **Start.**  
2. **Declare Variables:**  
   - `i` and `j` for loop counters.  
3. **Outer Loop:**  
   - Initialize `i = 1`.  
   - **Condition:** Run the loop while `i <= 5`.
   - Increment `i` by 1 after each iteration.
4. **Inner Loop (Nested):**  
   - Initialize `j = 1`.  
   - **Condition:** Run the loop while `j <= i`.
   - Increment `j` by 1 after each iteration.
5. **Inside Inner Loop:**  
   - Display `"* "` (a star followed by a space) on the same line.
6. After the inner loop completes, move to the next line using `endl`.
7. Repeat until the outer loop completes.
8. **End.**

---

## Inverted Half Pyramid

### Algorithm

1. **Start.**  
2. **Initialize:**  
   - Set `k = 1`.  
   - Declare variables `i` and `j` for loop counters.  
3. **Outer Loop:**  
   - Initialize `i = 1`.  
   - **Condition:** Run the loop while `i <= 5`.  
   - Increment `i` by 1 after each iteration.  
4. **Inner Loop (Nested):**  
   - Initialize `j = 1`.  
   - **Condition:** Run the loop while `j <= 5`.  
   - Increment `j` by 1 after each iteration.  
5. **Inside Inner Loop:**  
   - If `j >= k`, print a `'*'`.  
   - Else, print a space.  
6. After the inner loop completes, move to the next line.  
7. Decrement `k` by 1 to shift the starting position of stars leftward in the next row.  
8. Repeat until the outer loop completes.  
9. **End.**

---

## Floyd Series

### Algorithm

1. **Start.**  
2. **Declare Variables:**  
   - `i`, `j`, and `k`.  
   - Initialize `k = 1`.  
3. **Outer Loop:**  
   - Initialize `i = 1`.  
   - **Condition:** Run the loop while `i <= 5`.  
   - Increment `i` by 1 after each iteration.  
4. **Inner Loop (Nested):**  
   - Initialize `j = 1`.  
   - **Condition:** Run the loop while `j <= i`.  
   - Increment `j` by 1 after each iteration.  
5. **Inside Inner Loop:**  
   - Display the value of `k` followed by a space.  
   - Increment `k` by 1.  
6. After the inner loop completes, move to the next line using `endl`.  
7. Repeat until the outer loop completes.  
8. **End.**


## Introduction

This experiment focuses on implementing various decision-making statements and loops in C++. Each program demonstrates a unique aspect of control flow, including `if-else`, `while`, `do-while`, and nested loops.

## Programs Overview

### Program 1: While Loop from 1 to 20

**Logic:**  
This program uses a `while` loop to print numbers from 1 to 20. It demonstrates the basic structure of a `while` loop, where the condition is checked before executing the loop body.

### Program 2: Do-While Loop Example

**Logic:**  
This program illustrates the use of a `do-while` loop. Unlike a `while` loop, a `do-while` loop guarantees that the loop body is executed at least once before the condition is checked.

### Program 3: Flipped Floyd's Triangle

**Logic:**  
This program generates a flipped version of Floyd's Triangle using nested loops. It uses `for` loops to print a pattern of numbers in a triangular format, starting with the maximum width and reducing it in each subsequent row.

### Program 4: Floyd's Triangle

**Logic:**  
This program constructs Floyd's Triangle using nested `for` loops. The numbers are printed in a right-angled triangular format, starting from 1 at the top and continuing sequentially.

### Program 5: Password Check with While Loop

**Logic:**  
This program prompts the user to enter a password and uses a `while` loop to keep asking for input until the correct password is entered. It demonstrates how loops can be used for validation purposes.

### Program 6: Reverse Star Pattern

**Logic:**  
This program prints a reverse star pattern, decreasing the number of stars in each row. It uses nested loops to control the number of stars printed and the number of rows.

### Program 7: Star Pattern

**Logic:**  
This program creates a basic star pattern with a fixed number of rows and columns using nested loops. It's a simple example of using loops to generate patterns.

### Program 8: Star Pyramid

**Logic:**  
This program generates a star pyramid with a center alignment. It uses nested loops where the outer loop controls the rows, and the inner loops manage spaces and star printing for each row.

---

These programs are a great way to understand the practical application of loops and decision-making statements in C++. Explore each program to get a deeper insight into how control structures work in real-world scenarios.
