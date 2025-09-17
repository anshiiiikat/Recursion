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
README
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

 ## Reverse a String 

1.Start

2.Declare a character array str to store the input string.

3.Input the string str from the user.

4.Initialize a pointer start to point to the first character of str.

5.Initialize a pointer end to point to the last character of str (use strlen(str) - 1 to find it).

6.Repeat while start is less than end:
Store the character at start in a temporary variable x.

Assign the character at end to the location pointed by start.

Assign the temporary variable x to the location pointed by end.

Increment start pointer to the next character.

Decrement end pointer to the previous character.

7.Once the pointers meet or cross, the string is reversed.

8.Print the reversed string.

9.End
## Sum of First n Natural Numbers Using Recursion

1.Start

2.Input a number n from the user.

3.Define a recursive function sum(n) as follows:

If n is 0, return 0 (base case).

Otherwise, return n + sum(n-1) (recursive case).

4.Call the function sum(n) with the input number n.

5.Display the result as the sum of first n natural numbers.

6.End

# Conclusion


This experiment demonstrated how recursion simplifies problem-solving by breaking tasks into smaller subproblems. It highlighted the importance of a base case to ensure proper termination of recursive calls.




