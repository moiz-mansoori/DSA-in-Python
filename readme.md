# DSA in Python: Linked List, Stack, Queue, Circular Queue, Trees, and Recursion

## Description

This repository provides a Python files containing implementations of essential data structures for **Data Structures and Algorithms (DSA)**: **Linked List, Stack, Queue, Circular Queue, Trees, and Recursion**. It also includes a **Lab Manual** with various tasks and exercises. Each data structure includes fundamental methods and example usage. This is a useful resource for understanding these data structures in Python.

## Table of Contents

- [Data Structures](#data-structures)
  - [Linked List](#linked-list)
  - [Stack](#stack)
  - [Queue](#queue)
  - [Circular Queue](#circular-queue)
  - [Trees](#trees)
    - [General Tree](#general-tree)
    - [Binary Tree](#binary-tree)
    - [Preorder, Inorder, and Postorder Traversal](#preorder-inorder-and-postorder-traversal)
  - [Recursion](#recursion)
- [Lab Manual](#lab-manual)
- [Example Usage](#example-usage)
- [Contributing](#contributing)
- [License](#license)

---

## Installation

1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-username/dsa-in-python.git
   cd dsa-in-python
   ```

2. **Requirements**
   - Python 3.x

3. **Run the Code**
   All implementations are in a single file named `data_structures.py`. Run the file to test the implementations:
   ```bash
   python data_structures.py
   ```

---

## Data Structures

### Linked List

A **Linked List** is a linear data structure where elements are stored in nodes, with each node pointing to the next. This implementation includes:
- `insert(data)`: Insert a node at the end.
- `insert_at_beginning(data)`: Insert a node at the beginning.
- `delete(data)`: Delete a specific node.
- `display()`: Display all elements.

### Stack

A **Stack** is a LIFO (Last In, First Out) structure. This implementation includes:
- `push(data)`: Add an element to the top.
- `pop()`: Remove and return the top element.
- `peek()`: View the top element.
- `is_empty()`: Check if the stack is empty.

### Queue

A **Queue** is a FIFO (First In, First Out) structure. This implementation includes:
- `enqueue(data)`: Add an element to the end.
- `dequeue()`: Remove and return the front element.
- `is_empty()`: Check if the queue is empty.
- `display()`: Display all elements.

### Circular Queue

A **Circular Queue** connects the last element back to the first. This implementation includes:
- `enqueue(data)`: Add an element if there's space.
- `dequeue()`: Remove and return the front element.
- `is_empty()`: Check if the queue is empty.
- `is_full()`: Check if the queue is full.
- `display()`: Display all elements in order.

### Trees

#### General Tree

A **General Tree** is a tree where nodes can have multiple children. This implementation includes:
- `add_child(parent, child)`: Add a child to a parent node.
- `display()`: Print the tree structure.

#### Binary Tree

A **Binary Tree** is a tree where each node has at most two children. This implementation includes:
- `insert(data)`: Insert a node in the tree.
- `search(data)`: Search for a value in the tree.
- `display()`: Print the tree in a structured format.

#### Preorder, Inorder, and Postorder Traversal

- **Preorder (Root, Left, Right)**: Visit the root first, then traverse the left subtree, followed by the right subtree.
- **Inorder (Left, Root, Right)**: Traverse the left subtree first, visit the root, and then traverse the right subtree.
- **Postorder (Left, Right, Root)**: Traverse the left and right subtrees first, then visit the root.

### Recursion

**Recursion** is a method of solving problems where a function calls itself. This repository includes examples such as:
- **Factorial Calculation**
- **Fibonacci Series**
- **Binary Search Using Recursion**
- **Tower of Hanoi Problem**

---

## Lab Manual

This repository includes a **Lab Manual** containing various tasks and exercises related to the above data structures. It is designed for students to practice and understand fundamental concepts through hands-on coding exercises.

---
---

## Contributing

Contributions are welcome! If you would like to add features or fix issues, please fork the repository and submit a pull request.

---
