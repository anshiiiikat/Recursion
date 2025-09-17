# 🔄 Recursion in C++

## 🎯 Aim

To understand and implement recursion concepts in C++ programming.

---

## ✅ Objectives

- Learn the concept and working of recursion in programming.
- Implement recursive functions to solve common problems.
- Understand base case and recursive case in recursive functions.
- Explore real-life inspired examples to demonstrate recursion.

---

## 📚 Theory

### What is Recursion?

Recursion is a programming technique where a function calls itself directly or indirectly to solve smaller instances of the same problem until it reaches a base case.

---

### Key Concepts

- **Base Case:** The condition under which the recursion stops to avoid infinite calls.
- **Recursive Case:** The part of the function where recursion occurs (function calls itself with a smaller problem).
- Recursive functions usually reduce the problem size with each call.

---

## 🧱 Common Examples in C++

- Factorial calculation
- Fibonacci sequence generation
- Sum of natural numbers
- Tower of Hanoi
- Binary search (recursive implementation)

---

## ✅ Advantages of Recursion

- Simplifies complex problems by breaking them into smaller sub-problems.
- Code is often shorter and easier to understand.
- Effective for problems with a recursive structure.

---

## ⚠️ Limitations

- Can lead to high memory usage due to many function calls (stack overflow).
- Recursive solutions may be less efficient than iterative ones if not optimized.
- Requires careful definition of base case to avoid infinite recursion.

---

## Algorithm
### Calculate Factorial Using Recursion

1.Start

2.Input a number n from the user.

3.Define a recursive function fact(n):

4.If n is less than or equal to 1, return 1 (base case).

5.Otherwise, return n multiplied by fact(n-1) (recursive case).

6.Call the function fact(n) with the input number.

7.Display the result as the factorial of the number.

8.End


