# Sudoku CSP Solver

This project solves Sudoku puzzles using:
- Constraint Satisfaction Problem (CSP)
- AC-3 Algorithm
- Backtracking with MRV and Forward Checking

## Input Format
The Sudoku board must be provided in a text file:

- Exactly 9 lines
- Each line contains exactly 9 digits (0-9)
- 0 represents an empty cell

Example:

004030050
609400000
005100489
000060930
300807002
026040000
453009600
000004705
090050200

## How to Run

1. Run the Python file:
   python sudoku_solver.py

2. Enter the file name:
   easy.txt

## Output
- Solved Sudoku Grid
- Backtracking Calls
- Failures
- Execution Time
