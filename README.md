# Generic AVL Tree in C++

## Description

This project implements a generic AVL tree using C++ templates. The class provides several methods for interacting with the AVL tree, including insertion, deletion, searching, and tree traversal. Additionally, a forward iterator is provided to traverse the AVL tree in an inorder fashion.

## Public Methods / Interfaces

### Insert

**Signature**: `void insert(T data);`

**Description**: Inserts data appropriately into the AVL tree.

### print_tree

**Signature**: `void print_tree();`

**Description**: Prints the tree using inorder traversal and displays it in a readable format.

### Erase

**Signature**: `void erase(T data);`

**Description**: Deletes the node passed to it and ensures AVL tree properties are maintained.

### Find

**Signature**: `Iterator find(T data);`

**Description**: If the element passed is found in the AVL tree, it returns the iterator pointing to the node. If not, an iterator pointing to `nullptr` is returned.

### Empty

**Signature**: `inline bool empty();`

**Description**: Checks if the AVL tree pointed to by "this" is empty or not.

### Begin

**Signature**: `inline Iterator begin();`

**Description**: Returns an iterator to the first node (in inorder traversal) of the AVL tree.

### End

**Signature**: `inline Iterator end();`

**Description**: Returns an iterator which is next to the last node in the inorder traversal of the tree (which is `nullptr`).

## Getting Started

The main source code for the implementation is present in `generic_avl.h`.

## Dependencies

- C++ 14 and above
- GNU G++ version 9.3.0 or higher

## Installing

Clone this repository:
```sh
https://github.com/ShubhamK-2907/generic-AVL-Project
```
or download the zip folder and extract it.
