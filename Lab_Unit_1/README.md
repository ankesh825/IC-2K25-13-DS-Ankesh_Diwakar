# Lab Unit-1 – Arrays

## Introduction

This lab contains C++ programs related to Arrays, 2D Arrays, Sparse Matrix and Matrix Calculator.

The main objective of this lab is to understand array concepts and perform different operations using C++.

## 1. Array Operations

### Definition
An array is a linear data structure that stores multiple elements of the same data type in contiguous memory locations.

### Syntax
```cpp
data_type array_name[size];
```

### Example
```cpp
int arr[5] = {10, 20, 30, 40, 50};
```

### Basic Operations
- Traversal – Accessing each element.
- Insertion – Adding an element.
- Deletion – Removing an element.
- Searching – Finding an element.
- Updating – Modifying an element.

### Example Output
```text
Array Elements: 10 20 30 40 50
```

**Time Complexity:** O(n) for traversal  
**Auxiliary Space Complexity:** O(1)

---

## 2. 2D Array Operations

### Definition
A two-dimensional array is a collection of elements arranged in rows and columns. It is commonly used to represent matrices.

### Syntax
```cpp
data_type array_name[rows][columns];
```

### Example
```cpp
int matrix[2][3] = {
    {1, 2, 3},
    {4, 5, 6}
};
```

### Basic Operations
- Matrix traversal
- Accessing row and column elements
- Matrix addition
- Row and column sum

### Example Output
```text
1 2 3
4 5 6
```

**Time Complexity:** O(r × c) for traversal  
**Auxiliary Space Complexity:** O(1)

---

## 3. Sparse Matrix

### Definition
A sparse matrix is a matrix in which most elements are zero.

To save memory, a sparse matrix can be represented using triplet representation, which stores only non-zero elements along with their row and column positions.

### Syntax
```cpp
int matrix[3][3];
```

### Example
```text
Original Matrix:

0 0 5
0 8 0
3 0 0
```

### Triplet Representation
```text
Row  Column  Value
3    3       3
0    2       5
1    1       8
2    0       3
```

The first row represents the number of rows, columns and non-zero elements.

### Basic Operations
- Identify non-zero elements.
- Count non-zero elements.
- Convert a matrix into triplet representation.

**Time Complexity:** O(r × c) for conversion  
**Auxiliary Space Complexity:** O(k), where k is the number of non-zero elements.

---

## 4. Matrix Calculator

### Definition
A matrix calculator is a program that performs mathematical operations on matrices using two-dimensional arrays.

### Syntax
```cpp
int A[2][2];
int B[2][2];
int result[2][2];
```

### Example
```text
Matrix A:
1 2
3 4

Matrix B:
5 6
7 8
```

### Basic Operations

**Matrix Addition**
```text
6  8
10 12
```

**Matrix Subtraction (A - B)**
```text
-4 -4
-4 -4
```

**Matrix Multiplication (A × B)**
```text
19 22
43 50
```

### Time Complexity
- Addition: O(r × c)
- Subtraction: O(r × c)
- Multiplication (standard algorithm): O(r × c × p), where A is r × c and B is c × p.

**Auxiliary Space Complexity:** O(r × p) for storing a multiplication result.

---

## Time and Space Complexity Summary

| Program | Time Complexity | Auxiliary Space |
|---|---|---|
| Array Operations (Traversal) | O(n) | O(1) |
| 2D Array Operations (Traversal) | O(r × c) | O(1) |
| Sparse Matrix Conversion | O(r × c) | O(k) |
| Matrix Addition | O(r × c) | O(r × c) |
| Matrix Multiplication | O(r × c × p) | O(r × p) |

*Complexities are based on the specified operations. Input and output storage are excluded unless stated.*

## Technologies Used

- **Programming Language:** C++
- **Compiler:** G++
- **Version Control:** Git and GitHub
- **Concepts:** Arrays, Loops, Functions and Matrices

## Learning Outcomes

After completing this lab, I learned:

1. How to declare and initialize arrays.
2. How to perform basic array operations.
3. How to work with two-dimensional arrays.
4. How to represent sparse matrices using triplets.
5. How to perform mathematical operations on matrices.
6. How to understand the time and space complexity of array operations.

## Conclusion

In this lab, I implemented four programs based on Arrays and Matrices using C++. These programs helped me understand array operations, matrix representation, sparse matrices and basic matrix calculations.

---

**Name:** Ankesh Diwakar  
**Roll No.:** IC-2K25-13  
**Course:** Integrated MCA  
**Institute:** IIPS, DAVV, Indore  
**Subject:** Data Structures

**GitHub:** https://github.com/ankesh825
