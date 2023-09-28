Implementation of a recursive backtracking algorithm to solve Sudoku board.

Algorithm will proceduraly solve a provided Sudoku board until a mistake is made, at which point it will revert to the previous tile and repeat until the board is solved.

A custom board can be defined by editing the array in code.

## Example
### Input:
| 2 | 8 | 0 | 0 | 9 | 7 | 3 | 0 | 0 | <br />
| 4 | 0 | 7 | 0 | 3 | 0 | 8 | 0 | 0 |  
| 0 | 3 | 5 | 0 | 0 | 8 | 0 | 0 | 6 |  
| 0 | 0 | 0 | 0 | 1 | 3 | 0 | 8 | 0 |  
| 8 | 0 | 1 | 0 | 0 | 0 | 5 | 0 | 7 |  
| 0 | 5 | 0 | 7 | 8 | 0 | 0 | 0 | 0 |  
| 3 | 0 | 0 | 8 | 0 | 0 | 7 | 2 | 0 |  
| 0 | 0 | 8 | 0 | 2 | 0 | 4 | 0 | 3 |  
| 0 | 0 | 4 | 3 | 7 | 0 | 0 | 5 | 8 |  
### Output
| 2 | 8 | 6 | 1 | 9 | 7 | 3 | 4 | 5 |  
| 4 | 1 | 7 | 6 | 3 | 5 | 8 | 9 | 2 |  
| 9 | 3 | 5 | 2 | 4 | 8 | 1 | 7 | 6 |  
| 7 | 4 | 2 | 5 | 1 | 3 | 6 | 8 | 9 |  
| 8 | 9 | 1 | 4 | 6 | 2 | 5 | 3 | 7 |  
| 6 | 5 | 3 | 7 | 8 | 9 | 2 | 1 | 4 |  
| 3 | 6 | 9 | 8 | 5 | 4 | 7 | 2 | 1 |  
| 5 | 7 | 8 | 9 | 2 | 1 | 4 | 6 | 3 |  
| 1 | 2 | 4 | 3 | 7 | 6 | 9 | 5 | 8 |  
