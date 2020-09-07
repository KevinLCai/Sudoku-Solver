# Sudoku-Solver
Solves any solvable game of Sudoku!

This is a mini-project that requires the user to input the values of a solvable sudoku board and will print out the solved version. It uses a backtracking, brute-force algorithm that recursively finds the first blank space, and checks every digit (1-9) to see if it is valid in a game of Sudoku. 

If there is no valid digit, then the algorithm will backtrack and check if there is a different digit that is valid for the previous block. It continues this logic until it can no-longer find an empty, non-valid block. Then it returns the solved board to the user.
