
# Practical No. 8

## Title
Binary Search Tree Operations for Online Directory System

## Problem Statement
Design and implement a Binary Search Tree (BST) to manage an online directory system where names are stored in sorted order.

The system should support fast searching and recursive tree traversals including inorder, preorder, and postorder. A search function should also be implemented to locate a specific name in the directory.

## Objectives

- To understand the structure and properties of Binary Search Trees.
- To implement insertion and searching operations in a BST.
- To implement recursive tree traversals.
- To understand inorder, preorder, and postorder traversal techniques.
- To simulate a real-world online directory system.
- To understand how BSTs maintain sorted data.
- To develop skills in recursive programming and tree-based data structures.

## Theory

### Binary Search Tree

A Binary Search Tree (BST) is a hierarchical data structure in which each node contains a key and two child pointers: `left` and `right`.

The BST follows these properties:

- Values smaller than the parent node are stored in the left subtree.
- Values greater than the parent node are stored in the right subtree.
- Each subtree also follows the same BST property.
- The left or right pointer of a leaf node is `NULL`.

A BST can be represented as:

```text
             Root
            /    \
        Smaller  Greater