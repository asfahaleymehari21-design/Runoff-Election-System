# Runoff Election Project

A C program that simulates a runoff election voting system.

## Features

- Records ranked-choice votes
- Eliminates candidates with the fewest votes
- Redistributes votes automatically
- Detects ties
- Declares a winner when a candidate gets more than 50% of votes

## Concepts Used

- Arrays
- Structures
- Loops
- Functions
- Algorithms
- Vote tabulation
- Elimination logic

## Technologies

- C Programming Language
- CS50 Library

## How to Compile

```bash
clang runoff.c -o runoff -lcs50
```

## How to Run

```bash
./runoff Alice Bob Charlie
```

Example:

```bash
./runoff John Mike Sarah
```

## Example Workflow

```text
Number of voters: 3

Rank 1: Alice
Rank 2: Bob
Rank 3: Charlie
```

## Project Background

This project is inspired by the runoff election assignment from Harvard CS50.

## Author

Asfahaley Mahari