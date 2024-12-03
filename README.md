# Binary Trees Project

This repository contains the implementation of various functions and operations on binary trees as part of the ALX Software Engineering program. The project is designed to enhance understanding of binary trees, their properties, and traversal methods.

## Project Overview

The project involves creating and manipulating binary trees using the C programming language. It covers a range of tasks from basic node creation to more complex operations like tree traversal and checking tree properties.

## Learning Objectives

By the end of this project, you should be able to:

- Understand what a binary tree is and differentiate it from a Binary Search Tree (BST).
- Explain the advantages of binary trees in terms of time complexity compared to linked lists.
- Define and calculate the depth, height, and size of a binary tree.
- Implement different traversal methods: pre-order, in-order, and post-order.
- Identify and describe complete, full, perfect, and balanced binary trees.

## Key Features

- **Node Creation**: Functions to create new nodes in a binary tree.
- **Insertion**: Insert nodes as left or right children.
- **Deletion**: Delete entire binary trees.
- **Traversal**: Pre-order, in-order, and post-order traversal functions.
- **Property Checks**: Functions to check if a node is a leaf, if a tree is full, perfect, or balanced.
- **Measurement**: Calculate the height, depth, and size of a tree.
- **Sibling and Uncle**: Find the sibling or uncle of a given node.

## Binary Trees

Trees are simply nodes connected together. A binary tree is a kind of data structure used for storage purposes. Each node of a binary tree can only have a maximum of two nodes called the children. A simple binary tree consists of the ROOT, PATH, and CHILD nodes.

- **Root Node**: The node at the top of the tree. A tree can only have one root node and one path from the root node to any other node.
- **Path**: The sequence of nodes along the edges of a tree.
- **Child Node**: The node below a given node connected by its edge downward. It can be a LEFT CHILD or RIGHT CHILD.
- **Parent Node**: Any node except the root node with one edge upward.
- **Leaf Node**: The node without any child node, that is, the last or tail node at the end of every binary tree.
- **Subtree**: The descendants of a node.
- **Visiting**: Checking the value of a node when control is on the node.
- **Traversing**: Passing through nodes in a specific order.

### Binary Search Tree (BST) Operations

- **Insert**: Inserting an element in a tree or creating a tree.
- **Search**: Searching for an element in a tree.
- **Preorder Traversal**: Traversing a tree in a pre-order way.
- **Inorder Traversal**: Traversing a tree in an in-order way.
- **Postorder Traversal**: Traversing a tree in a post-order way.

#### Insert Operation

The first insert operation in a tree is to create a tree. To insert an element in a tree, first locate its location. Search from the root node and if the value you are looking for is less than the root node value, search for the empty location in the left subtree or node and insert the data or element. Otherwise, search for the empty location in the right subtree or node and insert the element or data.

#### Search Operation

To perform a search for an element in a tree, start from the root node. If the value of the element being searched for is less than that of the root node, search for the element in the left subtree or node. Otherwise, search for the element in the right subtree or node.

#### Preorder Traversal

This type of traversal method is a situation whereby the root node is visited first, then the left subtree or node, and finally the right subtree or node.

#### Inorder Traversal

This type of traversal method is a situation whereby the left subtree or node is visited first, then the root node, and finally the right subtree or node.

#### Postorder Traversal

This type of traversal method is a situation whereby the left subtree or node is visited first, then the right subtree or node, and finally the root.

## Requirements

- All code is written in C and compiled on Ubuntu 20.04 LTS using `gcc`.
- Code follows the Betty style guide.
- No global variables are used, and each file contains no more than 5 functions.

## Usage

To compile and run the code, use the provided `main.c` files as examples. The functions are implemented in separate files and can be compiled together using `gcc`.

## Repository Structure

- `binary_tree_node.c`: Functions for node creation.
- `binary_tree_insert_left.c`: Insert nodes as left children.
- `binary_tree_insert_right.c`: Insert nodes as right children.
- `binary_tree_delete.c`: Delete binary trees.
- `binary_tree_traversal.c`: Functions for tree traversal.
- `binary_tree_properties.c`: Check various properties of the tree.
- `binary_tree_measurement.c`: Measure height, depth, and size.
- `binary_tree_relationships.c`: Find siblings and uncles.
