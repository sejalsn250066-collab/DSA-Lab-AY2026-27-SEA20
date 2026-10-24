# Practical No. 2

## Title

Student Result Database Management Using Array of Structures

## Problem Statement

Design and implement a student result management system using an array of structures. The system should allow users to add new student records, update existing records, search for specific students, display records, and sort records based on performance metrics such as total marks or average.

The database stores details such as roll number, name, program, course, subject marks, total marks, and average.

## Objectives

- To understand the use of arrays and structures in C.
- To implement basic database operations such as insert, update, search, display, and sort.
- To develop logical thinking for managing structured data.
- To simulate a real-world student result management system.

## Theory

### Structure

A structure is a user-defined data type in C that allows grouping variables of different data types under a single name.

Unlike arrays, which store multiple values of the same data type, structures can store different types of data together.

For example:

```c
struct Student
{
    int rollNo;
    char name[50];
    float marks;
};