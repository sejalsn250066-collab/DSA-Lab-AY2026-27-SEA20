# Practical No. 5

## Title
Circular Queue Implementation Using Array for Parcel Handling System

## Problem Statement
Design and implement a circular queue using a static array to simulate a parcel handling system at a post office.

Parcels arrive at the post office and are queued in a First-In-First-Out (FIFO) manner. The system should support operations such as adding a parcel to the queue, deleting a parcel once it is processed, and displaying the current queue status.

## Objectives

- To understand the concept of circular queues and their advantages over linear queues.
- To implement queue operations using a static array.
- To simulate a real-world parcel handling system using FIFO logic.
- To understand and manage front and rear pointers in a circular queue.
- To efficiently utilize the available space in a fixed-size queue.
- To develop problem-solving skills using queue data structures.

## Theory

### Queue

A Queue is a linear data structure that follows the **FIFO (First-In-First-Out)** principle. The element inserted first is the first element to be removed.

Insertion is performed at the **rear**, while deletion is performed from the **front**.

### Circular Queue

A Circular Queue is a variation of a queue in which the last position of the array is connected back to the first position.

This allows the queue to reuse the empty spaces created after deleting elements from the front.

For example, if the queue size is 5:

```text
0 → 1 → 2 → 3 → 4
↑               ↓
└───────────────┘