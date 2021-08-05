# Conway's Game of Life
The Game of Life is a cellular automaton created by John H. Conway in 1970. The game is a zero-player game in which an initially configured 2D grid of cells evolves according to the Game of Life rules.

Built using Python 3.8, this implementation of Conway's Game of Life allows the user to easily run the Game of Life using a 2D grid of choosen number of rows and columns in either a Linux or Windows terminal/console.

## Rules
Imagine an infinite 2D orthogonal grid of square cells, each of which is in one of two possible states, live or dead. Every cell interacts with its eight neighbors, which are the cells that are directly horizontally, vertically, or diagonally adjacent.

1. Any live cell with fewer than two live neighbors dies, as if by loneliness.
2. Any live cell with more than three live neighbors dies, as if by overcrowding.
3. Any live cell with two or three live neighbors lives, unchanged, to the next generation.
4. Any dead cell with exactly three live neighbors comes to life.

## How to Run
This project is built using Python 3.8 and requires that the user has at least Python 3 installed in order to run the program. Python 3+ can be installed here.

In order to run this project the user must open a terminal/console and navigate to the project folder. Once inside the folder simply run `python main.py` in order to begin the program.

Once the program has been started the user will be prompted to input the number of rows and columns to make the Game of Life grid.
