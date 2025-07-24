# Program on Data Types in C++

## Tools Used
- **Language:** C++
- **Compiler:** g++ (GNU Compiler Collection)
- **IDE:** VS Code

## Theory

### Topic Overview
This experiment demonstrates:
- The usage of different **primitive data types** in C++
- How to measure **memory size** of variables using the `sizeof` operator
- The concept of **storage classes** in C++ such as `auto`, `register`, `static`, and `extern`

These programs help in understanding how variables are declared, how memory is managed, and how variable lifespan and visibility are handled in C++.

---

### Program 1: `exp2A.cpp` – Size of Primitive Data Types
This program:
- Takes user input for different data types: `char`, `int`, `float`, `double`, `bool`, `long`, and `long long`
- Displays the value and memory size (in bytes) for each using the `sizeof()` operator

#### Algorithm:
1. Declare variables for each data type
2. Take input from the user
3. Use `sizeof()` to print the memory size of each variable
4. Display value and size for each type

---

### Program 2: `exp2B.cpp` – Storage Classes Demonstration
This program demonstrates different **storage classes** in C++:
- `auto`: default for local variables
- `register`: hints the compiler to store variable in CPU register
- `static`: retains value across function calls
- `extern`: declares a global variable accessible across files

#### Algorithm:
1. Declare and initialize an `auto` and `register` variable
2. Define a function with a `static` variable and call it twice
3. Use a globally declared `extern` variable and print its value

---

## Conclusion
Through this experiment :
- Learn how different data types consume memory in C++
- Understand the behavior and scope of various **storage classes**
- Gain hands-on experience with input/output operations and memory handling

These concepts are essential for writing optimized and well-structured C++ programs, especially in low-level and embedded system applications.
