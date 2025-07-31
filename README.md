# Use of C++ Control Structures and Pattern Printing

## Project Objective

This project demonstrates the use of conditional statements, loops, and basic pattern generation using C++. It includes 10 well-structured programs that enhance understanding of:

- `if`, `else`, and `switch` statements
- `for` and `while` loops
- Nested loops for pattern printing
- String and numeric logic for verification
- Input/output formatting and control flow

These concepts are essential for mastering flow control and building the foundation for more complex programs.

---

## Theory: Iteration Control Statements in C++

**Iteration control statements** allow a set of instructions to be executed repeatedly based on a condition. These statements are essential in C++ for tasks like printing patterns, traversing numbers, validating input, and generating sequences.

### Types of Iteration Statements:

1. ``** Loop**\
   Used when the number of iterations is known. It has three parts: initialization, condition, and increment/decrement.

   ```cpp
   for (int i = 0; i < 5; i++) {
       // Executes 5 times
   }
   ```

2. ``** Loop**\
   Used when the number of iterations is unknown and the loop must continue as long as a condition is true.

   ```cpp
   while (condition) {
       // Executes repeatedly until condition becomes false
   }
   ```

3. ``** Loop**\
   Similar to `while`, but ensures the loop executes at least once.

   ```cpp
   do {
       // Executes at least once
   } while (condition);
   ```

### Application in the Project:

- **Pattern Printing Programs** (Programs 2 to 7) use **nested **``** loops** to control rows and columns of spaces/stars.
- **Number Reversal and Password Validation** use ``** loops** to process input digit-by-digit or character-by-character.
- Iteration helps control how many times a task is repeated, based on a clear logical structure.

### Why It's Important:

- Teaches **loop control logic** and **debugging nested loops**.
- Strengthens the foundation for **matrix operations**, **data processing**, and **algorithm design**.
- Encourages thinking in **steps and conditions**, which is key to programming logic.

---

## List of Programs

### 1. Simple For Loops

**Description:**\
Prints even numbers from 0 to 10 and then prints “SIT” five times.

**Algorithm:**

1. Use a `for` loop with `i` starting from 0 and incrementing by 2 until 10.
2. Print each value of `i`.
3. Use another `for` loop to print "SIT" five times.

---

### 2. Right Aligned Star (\*) Triangle

**Description:**\
Displays a right-aligned triangle using stars.

**Algorithm:**

1. Loop for rows from 1 to n.
2. For each row, print (n-row) spaces.
3. Then print `row` number of stars.

---

### 3. Left Aligned Star (\*) Triangle

**Description:**\
Displays a left-aligned triangle using stars.

**Algorithm:**

1. Loop through each row from 1 to n.
2. For each row, print that number of stars.

---

### 4. Inverted Star (\*) Pyramid

**Description:**\
Displays an inverted centered pyramid of stars.

**Algorithm:**

1. Loop from n down to 1.
2. For each row, print (n-row) spaces.
3. Print (2×row−1) stars.

---

### 5. Inverted Left Aligned Star (\*) Triangle

**Description:**\
Displays a left-aligned triangle of stars in descending order.

**Algorithm:**

1. Loop from n down to 1.
2. Print that number of stars.

---

### 6. Inverted Right Aligned Star (\*) Triangle

**Description:**\
Displays a right-aligned triangle of stars in inverted form.

**Algorithm:**

1. Loop from n down to 1.
2. For each row, print (n-row) spaces followed by `row` stars.

---

### 7. Pyramid Star (\*) Pattern

**Description:**\
Prints a centered pyramid of stars.

**Algorithm:**

1. Loop through rows from 1 to n.
2. For each row, print (n-row) spaces.
3. Then print (2×row−1) stars.

---

### 8. Reversing Digits in a Number

**Description:**\
Takes a 4-digit number and prints it in reverse order.

**Algorithm:**

1. Input a number.
2. Use a `while` loop: take the remainder when dividing by 10.
3. Multiply reverse variable by 10 and add remainder.
4. Divide number by 10 and repeat until number becomes 0.

---

### 9. Floyd's Triangle

**Description:**\
Prints Floyd’s Triangle using increasing natural numbers row by row.

**Algorithm:**

1. Input number of rows.
2. Use two nested loops: outer for rows, inner for printing numbers.
3. Increment a counter for each printed number.

---

### 10. Password Verification

**Description:**\
A secure password validation program that:

- Requires at least one capital letter, one number, and one special character.
- Prompts the user to re-enter the password for verification.

**Algorithm:**

1. Input a password.
2. Loop through characters and check for one uppercase, one digit, one special character.
3. If valid, ask user to re-enter password.
4. Match and verify.

---

## Learning Outcomes

- Implemented control structures (`if`, `else`, `switch`)
- Practiced loop-based programming with real-world examples
- Learned how to use nested loops for geometric patterns
- Understood number processing using mathematical operations
- Applied string validation logic to enforce password rules
- Improved command over formatting structured output in the console

