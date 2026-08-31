# ECE 2112: Advanced Computer Programming and Algorithms
**Experiment 1: Introduction to Python Programming** ||
**Programmed by:** Buño, James Patrick T.

This repository contains the Jupyter Notebook solution for **Experiment 1**, demonstrating the use of basic Python functions, operators, string operations, and sequence unpacking. As per the laboratory instructions, no external Python libraries were used.

---

## A. Word Rotation Problem
A function `rotate_word(text)` that accepts a non-empty string and moves its first character to the end while keeping the remaining characters in their original order.
*   **Technique Used:** String slicing and concatenation to preserve original capitalization.

## B. Username Builder Problem
A function `make_username(first_name, last_name)` that formats a user's name into a standardized username.
*   **Technique Used:** Basic string methods (`.lower()`, `.replace()`) to convert all letters to lowercase, remove spaces, and join the processed names using a single period (`.`).

## C. Bookend Swap Problem
A function `swap_bookends(items)` that accepts a list and returns a new list where the first and last elements have exchanged positions. 
*   **Technique Used:** Extended sequence unpacking (`first, *middle, last = items`) to keep the middle elements in their original order without modifying the input list.

---

## 📥 Access the Notebook
To view the full code and executed test cells showing the expected outputs[cite: 2], open the Jupyter Notebook file in this repository:
*   [**EXPERIMENT 1 INTRODUCTION TO PYTHON PROGRAMMING.ipynb**](./EXPERIMENT%201%20INTRODUCTION%20TO%20PYTHON%20PROGRAMMING.ipynb)
