# Practical No. 3

## Title

Searching Contact Names Using Sequential Search and Binary Search

## Problem Statement

You are building a contact manager application. A user wants to search for a specific contact name either by scanning the contacts one by one or by using a faster lookup method when the contact list is sorted.

Write a C program to locate a specific contact name using both Sequential Search and Binary Search techniques. Compare the results obtained using the two searching methods.

## Objectives

- To understand the concept of searching in data structures.
- To implement Sequential Search and Binary Search techniques.
- To compare the working and efficiency of different searching algorithms.
- To understand the importance of sorted data for Binary Search.
- To apply searching techniques to a real-world contact management application.
- To develop algorithmic thinking and problem-solving skills.

## Theory

Searching is the process of finding a particular element from a collection of data. It is one of the fundamental operations performed on arrays and other data structures.

The efficiency of a searching technique depends on the organization of data and the algorithm used.

### Sequential Search

Sequential Search, also called Linear Search, checks each element one by one from the beginning of the list.

- It compares each contact with the search name.
- The search continues until the required element is found or the end of the list is reached.
- It can be applied to both sorted and unsorted data.
- It is simple and suitable for small datasets.

**Time Complexity:** O(n)

**Space Complexity:** O(1)

### Binary Search

Binary Search is an efficient searching technique that works on sorted data.

- It compares the search element with the middle element of the list.
- If the search element is smaller than the middle element, the left half is searched.
- If the search element is larger than the middle element, the right half is searched.
- The process continues until the element is found or the search range becomes empty.

**Time Complexity:** O(log n)

**Space Complexity:** O(1) for iterative implementation.

## Comparison of Searching Techniques

| Feature | Sequential Search | Binary Search |
|---|---|---|
| Data Requirement | Sorted or unsorted | Must be sorted |
| Searching Method | Checks elements one by one | Divides search space into halves |
| Best-case Time | O(1) | O(1) |
| Worst-case Time | O(n) | O(log n) |
| Space Complexity | O(1) | O(1) |
| Suitable For | Small or unsorted datasets | Sorted and larger datasets |

## Key Concepts

- Searching
- Sequential Search
- Linear Search
- Binary Search
- Sorted Data
- Arrays
- Time Complexity
- Space Complexity
- Algorithm Comparison

## Algorithms

### 1. Sequential Search

1. Start from the first contact in the list.
2. Compare the current contact name with the search name.
3. If both names are equal, return the position of the contact.
4. Otherwise, move to the next contact.
5. Repeat the process until the contact is found or the end of the list is reached.
6. If the contact is not found, display an appropriate message.
7. Stop.

### 2. Binary Search

1. Arrange the contact names in alphabetical order.
2. Set `low = 0` and `high = n - 1`.
3. Calculate the middle position using `mid = (low + high) / 2`.
4. Compare the middle contact name with the search name.
5. If they are equal, return the position of the contact.
6. If the search name comes before the middle name, set `high = mid - 1`.
7. If the search name comes after the middle name, set `low = mid + 1`.
8. Repeat the process until the contact is found or `low > high`.
9. If the contact is not found, display an appropriate message.
10. Stop.

## Program

The C implementation for this practical is available in [`program.c`](program.c).

## Result

The program successfully implements Sequential Search and Binary Search for finding contact names. The searching techniques are compared based on their working and number of comparisons or iterations required to find a contact.

## Conclusion

This practical demonstrates the implementation of Sequential Search and Binary Search techniques using contact names. Sequential Search can work with sorted or unsorted data, while Binary Search requires sorted data and reduces the search space by half in each step. The comparison helps in understanding the efficiency and appropriate use of different searching algorithms.
