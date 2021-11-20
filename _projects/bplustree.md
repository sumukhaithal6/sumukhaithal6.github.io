---
title: "Generic B+ Tree"
excerpt: "B+ Tree data structure for generic types. Supports all features of Standard Template Library (STL) container."
collection: projects
---
## Abstract
We implement the B+ tree data structure. We will be supporting member functions like insert, delete, clear. A few STL algorithms like find will also be made member functions to make it more efficient. The B + tree data structure will support predicate as a type to support ordering as per client's needs. A constant bidirectional iterator will be supported which will do inorder traversal of the tree. All Generic algorithms like find and copy which work with constant bidirectional iterators have been supported. Iterator traits class has been provided for this type.
## Key Features
1. Performed automated testing for insert, delete for B+ tree using uniform_int_distribution.  [(Link)](https://github.com/DhruvaKashyap/BPlus-Tree/blob/main/include/tests.h)
2. Used concepts and allocators and developed a STL-like interface for B + tree. [(Link)](https://github.com/DhruvaKashyap/BPlus-Tree/blob/main/include/bplus.h#L19)
3. Experimented with Template metaprogramming for the project.

## [Code](https://github.com/DhruvaKashyap/BPlus-Tree)