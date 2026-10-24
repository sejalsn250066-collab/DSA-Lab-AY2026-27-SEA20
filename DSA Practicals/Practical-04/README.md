# Practical No. 4

## Title

Decimal to Binary Conversion Using Stack

## Problem Statement

Develop a program that converts a given decimal number into its binary equivalent using a stack data structure.

The stack is used to reverse the order of binary digits generated during the conversion process.

## Objectives

- To understand the use of stacks in algorithmic problem-solving.
- To implement decimal-to-binary conversion using LIFO (Last-In-First-Out) logic.
- To reinforce the concept of number systems and data structures.
- To simulate how intermediate results can be stored and retrieved using stacks.

## Theory

### Stack

A stack is a linear data structure that follows the **LIFO (Last-In-First-Out)** principle.

In a stack, insertion and deletion take place at one end called the **top**.

The two basic operations of a stack are:

- **PUSH:** Adds an element to the top of the stack.
- **POP:** Removes an element from the top of the stack.

Another commonly used operation is:

- **PEEK/TOP:** Returns the top element without removing it.

### LIFO Principle

LIFO means **Last-In-First-Out**.

The element inserted last into the stack is the first element removed.

For example:

```text
        TOP
         ↓
       | 1 |  ← POP
       | 0 |
       | 1 |
       | 1 |
       -----