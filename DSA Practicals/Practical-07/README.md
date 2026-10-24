# Practical No. 7

## Title
Dynamic Text Editor Using Singly Linked List

## Problem Statement
Design and implement a text editor that stores lines of text dynamically using a singly linked list.

The system should support insertion and deletion of lines at any position, display the text in normal and reverse order, and allow reversing the entire linked list.

## Objectives

- To understand the structure and operations of singly linked lists.
- To implement dynamic storage and manipulation of text lines.
- To perform insertion and deletion of nodes at different positions.
- To display linked list elements in normal and reverse order.
- To reverse the entire linked list.
- To develop proficiency in pointer manipulation and linked list traversal.
- To simulate a real-world text editor application using a linked list.

## Theory

### Linked List

A linked list is a dynamic linear data structure in which elements are stored in separate nodes. Unlike arrays, linked list elements do not need to be stored in continuous memory locations.

Each node contains two main fields:

1. **Data** – Stores the actual information.
2. **Link** – Stores the address of the next node.

A singly linked list can be represented as:

```text
Head
 ↓
[Data | Next] → [Data | Next] → [Data | NULL]