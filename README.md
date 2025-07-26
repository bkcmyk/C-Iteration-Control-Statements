
# Use of C++ Control Structures and Pattern Printing

## Project Objective

This project demonstrates the use of conditional statements, loops, and basic pattern generation using C++. It includes 10 well-structured programs that enhance understanding of:

* `if`, `else`, and `switch` statements  
* `for` and `while` loops  
* Nested loops for pattern printing  
* String and numeric logic for verification  
* Input/output formatting and control flow

These concepts are essential for mastering flow control and building the foundation for more complex programs.

---

## Theory: Iteration Control Statements in C++

**Iteration control statements** allow a set of instructions to be executed repeatedly based on a condition. These statements are essential in C++ for tasks like printing patterns, traversing numbers, validating input, and generating sequences.

### Types of Iteration Statements:

1. **`for` Loop**  
   Used when the number of iterations is known. It has three parts: initialization, condition, and increment/decrement.
   ```cpp
   for (int i = 0; i < 5; i++) {
       // Executes 5 times
   }
   ```

2. **`while` Loop**  
   Used when the number of iterations is unknown and the loop must continue as long as a condition is true.
   ```cpp
   while (condition) {
       // Executes repeatedly until condition becomes false
   }
   ```

3. **`do-while` Loop**  
   Similar to `while`, but ensures the loop executes at least once.
   ```cpp
   do {
       // Executes at least once
   } while (condition);
   ```

### Application in the Project:

- **Pattern Printing Programs** (Programs 2 to 7) use **nested `for` loops** to control rows and columns of spaces/stars.
- **Number Reversal and Password Validation** use **`while` loops** to process input digit-by-digit or character-by-character.
- Iteration helps control how many times a task is repeated, based on a clear logical structure.

### Why It's Important:

- Teaches **loop control logic** and **debugging nested loops**.
- Strengthens the foundation for **matrix operations**, **data processing**, and **algorithm design**.
- Encourages thinking in **steps and conditions**, which is key to programming logic.

---

## List of Programs

### 1. Simple For Loops

**Description:**  
Prints even numbers from 0 to 10 and then prints “SIT” five times.

**Output:**
```
0
2
4
6
8
10

SIT
SIT
SIT
SIT
SIT
```

---

### 2. Right Aligned Star (*) Triangle

**Description:**  
Displays a right-aligned triangle using stars.

**Output:**
```
        * 
      * * 
    * * * 
  * * * * 
* * * * * 
```

---

### 3. Left Aligned Star (*) Triangle

**Description:**  
Displays a left-aligned triangle using stars.

**Output:**
```
* 
* * 
* * * 
* * * * 
* * * * * 
```

---

### 4. Inverted Star (*) Pyramid

**Description:**  
Displays an inverted centered pyramid of stars.

**Output:**
```
*********
 *******
  *****
   ***
    *
```

---

### 5. Inverted Left Aligned Star (*) Triangle

**Description:**  
Displays a left-aligned triangle of stars in descending order.

**Output:**
```
* * * * * 
* * * * 
* * * 
* * 
* 
```

---

### 6. Inverted Right Aligned Star (*) Triangle

**Description:**  
Displays a right-aligned triangle of stars in inverted form.

**Output:**
```
* * * * * 
  * * * * 
    * * * 
      * * 
        * 
```

---

### 7. Pyramid Star (*) Pattern

**Description:**  
Prints a centered pyramid of stars.

**Output:**
```
    *
   ***
  *****
 *******
*********
```

---

### 8. Reversing Digits in a Number

**Description:**  
Takes a 4-digit number and prints it in reverse order.

**Sample Output:**
```
Enter the last four digits of your PRN number: 3029
Reversed digits: 9203
```

---

### 9. Floyd's Triangle

**Description:**  
Prints Floyd’s Triangle using increasing natural numbers row by row.

**Sample Output:**
```
Enter the number of rows for Floyd's Triangle: 5
1 
2 3 
4 5 6 
7 8 9 10 
11 12 13 14 15 
```

---

### 10. Password Verification

**Description:**  
A secure password validation program that:
- Requires at least one capital letter, one number, and one special character.
- Prompts the user to re-enter the password for verification.

**Sample Output:**
```
Set password: 785@A
Password is set successfully.

Enter password: 785@A
System Unlocked
```

---

## Learning Outcomes

* Implemented control structures (`if`, `else`, `switch`)  
* Practiced loop-based programming with real-world examples  
* Learned how to use nested loops for geometric patterns  
* Understood number processing using mathematical operations  
* Applied string validation logic to enforce password rules  
* Improved command over formatting structured output in the console  
