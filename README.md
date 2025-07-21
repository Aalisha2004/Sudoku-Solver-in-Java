# Sudoku-Solver-in-Java

This project implements a Sudoku Solver using backtracking in Java. It takes a 9x9 partially filled Sudoku grid as input and fills it with valid digits (1–9) to complete the puzzle, following Sudoku rules.

## ✅ Features
Solves standard 9x9 Sudoku puzzles

Uses recursive backtracking algorithm

Checks for validity using row, column, and 3x3 sub-grid constraints

Displays the solved Sudoku board if a solution exists

## 🧠 Algorithm Overview
Backtracking Approach:

Recursively attempts to fill empty cells with digits 1 through 9.

For each cell, it checks whether placing a digit is safe:

Not repeated in the same row

Not repeated in the same column

Not repeated in the same 3x3 subgrid

If placing a digit leads to a valid solution, it continues.

If no digit fits, it backtracks to try another possibility.

## Functions:

isSafe(...): Checks if a digit can be safely placed at a given cell.

sudokuSolver(...): Recursive function that attempts to solve the board.

printSudoku(...): Prints the Sudoku grid.

main(...): Initializes a Sudoku puzzle and starts the solving process.

## 📝 Notes
This implementation assumes the input is a valid, partially filled Sudoku grid.

Empty cells are represented with 0.
