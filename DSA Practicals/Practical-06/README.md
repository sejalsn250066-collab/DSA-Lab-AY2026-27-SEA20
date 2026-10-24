
# Practical No. 6

## Title
Train Ticket Booking System Using Queue

## Problem Statement
A railway reservation system needs to manage train ticket bookings efficiently.

Passengers requesting tickets should be given confirmed seats if seats are available. If all seats are occupied, additional passengers should be added to a waiting list.

When a confirmed passenger cancels their ticket, the first passenger from the waiting list should be shifted to confirmed status.

Implement a queue-based train ticket booking system to manage confirmed bookings and waiting passengers.

## Objectives

- To understand the concept of Queue as a linear data structure.
- To implement queue operations such as insertion and deletion.
- To apply the FIFO (First-In-First-Out) principle in a real-world application.
- To manage confirmed and waiting-list train ticket bookings.
- To understand how cancellation affects waiting-list passengers.
- To develop problem-solving and data management skills using queues.
- To understand the practical use of queues in reservation systems.

## Theory

### Queue

A Queue is a linear data structure in which insertion of elements takes place at one end called the **rear**, while deletion takes place at the other end called the **front**.

A queue follows the **FIFO (First-In-First-Out)** principle.

The passenger who joins the queue first gets processed first.

### Queue Operations

#### 1. Enqueue

Enqueue is used to add a new passenger to the rear of the queue.

#### 2. Dequeue

Dequeue removes the passenger from the front of the queue.

#### 3. Peek

Peek displays the passenger at the front without removing them.

#### 4. IsEmpty

IsEmpty checks whether the queue contains any passengers.

#### 5. IsFull

IsFull checks whether the queue has reached its maximum capacity.

## Train Ticket Booking System

The train ticket booking system uses queues to manage confirmed passengers and waiting-list passengers.

The system maintains two logical queues:

### Confirmed Booking Queue

Passengers are added to the confirmed booking queue when seats are available.

```text
Front → Passenger 1 → Passenger 2 → Passenger 3 ← Rear