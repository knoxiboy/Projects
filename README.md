Sudoku Solver - How It Works
This particular algorithm employs the use of backtracking, one of the more common methods to solve Sudoku puzzles. I've written a simple algorithm to give an idea of how the program works.

Start.
1.We start with the first empty cell.
2.We generate a list of possible valid values that can be filled in that cell.
3.We iterate over this list and start with the first value. This value is placed in the required cell.
4.We move on to the next cell. We again generate a list of possibilities. However, if no list can be generated, then this means that there is something wrong with the value of the previous cell. We then move back to the previous cell and place the next value on the generated list in the cell now. We repeat this step until the current cell has a valid value placed inside it.
5.We stop when we reach the 81st cell (the last cell in a Sudoku puzzle) and have placed a valid value.
6.The puzzle has now been solved.
Stop.
