# Generalised Data Structures Library

A C++ library of **generic data structures** providing object-oriented implementations of both linear and non-linear structures.  
Designed with templates for **data type independence**, this library is reusable, modular, and extensible — suitable for academic learning and real-world application development.

---

## 🚀 Technology Stack
- **Language:** C++  
- **Paradigm:** Object-Oriented Programming (OOP)  
- **Core Concept:** Generic Programming with Templates  

---

## 📖 Project Overview
This project offers ready-to-use functionalities for fundamental and advanced operations on data structures.  
It emphasizes clean OOP principles, modularity, and extensibility, making it easy to integrate into client applications.

---

## ✨ Key Features
- **Linear Data Structures**
  - Singly Linear Linked List  
  - Singly Circular Linked List  
  - Doubly Linear Linked List  
  - Doubly Circular Linked List  
  - Stack (LIFO)  
  - Queue (FIFO)  

- **Non-Linear Data Structures**
  - Binary Search Tree (BST) with insert, delete, and traversal operations  

- **Algorithms**
  - Searching: Linear Search, Binary Search  
  - Sorting: Bubble Sort, Selection Sort, Insertion Sort  

- **Generic Implementation**
  - Uses C++ templates for type independence  
  - Works seamlessly with integers, floats, strings, and custom objects  

- **Library Format**
  - Designed as a reusable C++ library  
  - Can be linked with client applications  

---

## 🧑‍💻 Example Usage
### Creating a Stack of Integers
```cpp
#include "Stack.h"

int main() {
    Stack<int> s;
    s.push(10);
    s.push(20);
    s.display(); // Output: 20 10
    s.pop();
    s.display(); // Output: 10
    return 0;
}
🎯 Learning Outcomes
Mastery of C++ OOP principles

Strong foundation in linear and non-linear data structures

Practical knowledge of searching and sorting algorithms

Implementation of generic programming with templates

Experience in designing reusable libraries for software development
