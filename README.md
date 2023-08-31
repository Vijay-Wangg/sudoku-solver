
# sudoku-solver
Simple Sudoku solver created using Html, Css, Javascript

# About
Solver: First the program scans each cell and if there exists only one possibility, then it inserts that number. The program does this until the puzzle is stuck. Then it runs a backtracking DFS search to "try out" the possibilities, eliminating those (and its children) that doesn't work.

I aimed for code readability and simplicity over running time, although this program can solve a Sudoku puzzle in ~0.2s on average (Note that solving Sudoku puzzles is NP-complete).
