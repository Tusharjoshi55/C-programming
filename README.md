# C Programming: Basic to Advanced 🚀

A complete **C Programming course repository** designed to take you from **beginner to advanced level**.
This repository covers **fundamentals, problem-solving, algorithms, and advanced concepts** of the C language with examples and exercises.

Perfect for:

* Beginners learning programming
* College students studying C
* Developers preparing for coding interviews
* Anyone wanting strong programming fundamentals

---

# 📚 Course Structure

The course is divided into **10 modules** progressing from basic concepts to advanced programming.

```
C-Programming-Course
│
├── 01-introduction
├── 02-basic-syntax
├── 03-operators
├── 04-control-statements
├── 05-functions
├── 06-arrays
├── 07-pointers
├── 08-structures-unions
├── 09-file-handling
├── 10-advanced-concepts
└── projects
```

---

# 1️⃣ Introduction to C

## Topics Covered

* History of C
* Features of C
* Structure of a C program
* Compilation process
* First program

## Example

```c
#include <stdio.h>

int main() {
    printf("Hello, World!");
    return 0;
}
```

## Exercises

1. Print your name and college name.
2. Print numbers from 1 to 10.
3. Print ASCII values of characters.

---

# 2️⃣ Basic Syntax

## Topics

* Keywords
* Identifiers
* Variables
* Data Types
* Constants

## Data Types

| Type   | Description           |
| ------ | --------------------- |
| int    | Integer numbers       |
| float  | Decimal numbers       |
| char   | Single character      |
| double | Large decimal numbers |

## Example

```c
int age = 20;
float marks = 85.5;
char grade = 'A';
```

---

# 3️⃣ Operators

## Types of Operators

### Arithmetic

```
+  -  *  /  %
```

### Relational

```
==  !=  >  <  >=  <=
```

### Logical

```
&&  ||  !
```

### Assignment

```
=  +=  -=  *=  /=  %=
```

### Example

```c
int a = 10;
int b = 5;

printf("%d", a + b);
```

---

# 4️⃣ Control Statements

## Conditional Statements

### if

```c
if (a > b) {
    printf("A is greater");
}
```

### if-else

```c
if (a % 2 == 0)
    printf("Even");
else
    printf("Odd");
```

### switch

```c
switch(day) {
    case 1: printf("Monday"); break;
    case 2: printf("Tuesday"); break;
}
```

## Loops

### for loop

```c
for(int i=1;i<=10;i++){
    printf("%d", i);
}
```

### while loop

```c
while(i <= 10){
    printf("%d", i);
    i++;
}
```

### do while

```c
do{
    printf("%d", i);
    i++;
}while(i<=10);
```

---

# 5️⃣ Functions

Functions help organize code and reuse logic.

## Types

* Library Functions
* User-defined Functions

## Example

```c
#include<stdio.h>

int add(int a, int b){
    return a + b;
}

int main(){
    int result = add(5,4);
    printf("%d", result);
}
```

---

# 6️⃣ Arrays

Arrays store multiple values in one variable.

## Example

```c
int arr[5] = {1,2,3,4,5};

for(int i=0;i<5;i++){
    printf("%d", arr[i]);
}
```

## Types

* 1D Array
* 2D Array
* Multidimensional Arrays

---

# 7️⃣ Pointers 🔥

Pointers store **memory addresses**.

## Example

```c
int a = 10;
int *p;

p = &a;

printf("%d", *p);
```

## Topics

* Pointer basics
* Pointer arithmetic
* Pointer to pointer
* Pointers with arrays
* Pointers with functions

---

# 8️⃣ Structures and Unions

Used to store **multiple data types together**.

## Structure Example

```c
struct Student {
    int id;
    char name[20];
};

struct Student s1;
```

---

# 9️⃣ File Handling

File handling allows storing data permanently.

## Modes

| Mode | Description |
| ---- | ----------- |
| r    | Read        |
| w    | Write       |
| a    | Append      |

## Example

```c
FILE *fp;

fp = fopen("data.txt", "w");

fprintf(fp, "Hello");

fclose(fp);
```

---

# 🔟 Advanced Concepts

## Topics

* Dynamic Memory Allocation
* Recursion
* Linked Lists
* Bitwise Operators
* Command Line Arguments

### malloc Example

```c
int *ptr;

ptr = (int*) malloc(5 * sizeof(int));
```

---

# 💻 Practice Problems

### Basic

* Fibonacci Series
* Factorial
* Prime Number
* Armstrong Number

### Intermediate

* Matrix multiplication
* String reverse
* Palindrome check
* Sorting algorithms

### Advanced

* Linked list implementation
* Stack using arrays
* Queue implementation
* File based record system

---

# 🚀 Mini Projects

### 1. Student Management System

Features:

* Add Student
* Delete Student
* Search Student
* Save to File

### 2. Calculator

Operations:

* Add
* Subtract
* Multiply
* Divide

### 3. Bank Management System

Features:

* Create account
* Deposit
* Withdraw
* Balance check

---

# 🛠 Requirements

* GCC Compiler
* Code Editor (VS Code / CodeBlocks / Dev C++)
* Basic understanding of programming

Compile program:

```
gcc program.c -o program
./program
```

---

# 📖 Learning Path

Recommended order:

1. Introduction
2. Syntax & Variables
3. Operators
4. Control Statements
5. Functions
6. Arrays
7. Pointers
8. Structures
9. File Handling
10. Advanced Concepts

---

# 🤝 Contribution

Contributions are welcome.

Steps:

```
1 Fork the repository
2 Create a new branch
3 Commit changes
4 Submit a Pull Request
```

---

# ⭐ Support

If this repository helped you, please give it a ⭐ on GitHub.

---

# 📜 License

This project is open-source and available under the **MIT License**.
