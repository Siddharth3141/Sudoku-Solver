# Sudoku Solver
A Sudoku solver using recursion and backtracking in python.

###Usage
Run `main.py`

###Example:
`Original:`
```
╔═══╤═══╤═══╦═══╤═══╤═══╦═══╤═══╤═══╗
║ 2 │ 5 │   ║   │ 1 │   ║   │   │ 9 ║
╟───┼───┼───╫───┼───┼───╫───┼───┼───╢
║   │ 7 │ 1 ║   │   │   ║   │ 8 │   ║
╟───┼───┼───╫───┼───┼───╫───┼───┼───╢
║   │   │ 3 ║ 6 │   │ 4 ║   │   │   ║
╠═══╪═══╪═══╬═══╪═══╪═══╬═══╪═══╪═══╣
║ 7 │   │ 9 ║ 5 │   │   ║   │   │ 4 ║
╟───┼───┼───╫───┼───┼───╫───┼───┼───╢
║   │ 4 │   ║   │   │ 9 ║   │   │   ║
╟───┼───┼───╫───┼───┼───╫───┼───┼───╢
║   │   │   ║ 4 │   │ 7 ║   │   │ 8 ║
╠═══╪═══╪═══╬═══╪═══╪═══╬═══╪═══╪═══╣
║   │ 1 │ 8 ║   │ 5 │   ║ 9 │   │   ║
╟───┼───┼───╫───┼───┼───╫───┼───┼───╢
║ 9 │   │   ║ 1 │   │   ║ 5 │   │ 7 ║
╟───┼───┼───╫───┼───┼───╫───┼───┼───╢
║   │ 2 │   ║   │ 4 │   ║ 8 │ 6 │ 1 ║
╚═══╧═══╧═══╩═══╧═══╧═══╩═══╧═══╧═══╝
```
`Solved:`
```
╔═══╤═══╤═══╦═══╤═══╤═══╦═══╤═══╤═══╗
║ 2 │ 5 │ 4 ║ 3 │ 1 │ 8 ║ 6 │ 7 │ 9 ║
╟───┼───┼───╫───┼───┼───╫───┼───┼───╢
║ 6 │ 7 │ 1 ║ 2 │ 9 │ 5 ║ 4 │ 8 │ 3 ║
╟───┼───┼───╫───┼───┼───╫───┼───┼───╢
║ 8 │ 9 │ 3 ║ 6 │ 7 │ 4 ║ 2 │ 1 │ 5 ║
╠═══╪═══╪═══╬═══╪═══╪═══╬═══╪═══╪═══╣
║ 7 │ 8 │ 9 ║ 5 │ 6 │ 1 ║ 3 │ 2 │ 4 ║
╟───┼───┼───╫───┼───┼───╫───┼───┼───╢
║ 1 │ 4 │ 2 ║ 8 │ 3 │ 9 ║ 7 │ 5 │ 6 ║
╟───┼───┼───╫───┼───┼───╫───┼───┼───╢
║ 3 │ 6 │ 5 ║ 4 │ 2 │ 7 ║ 1 │ 9 │ 8 ║
╠═══╪═══╪═══╬═══╪═══╪═══╬═══╪═══╪═══╣
║ 4 │ 1 │ 8 ║ 7 │ 5 │ 6 ║ 9 │ 3 │ 2 ║
╟───┼───┼───╫───┼───┼───╫───┼───┼───╢
║ 9 │ 3 │ 6 ║ 1 │ 8 │ 2 ║ 5 │ 4 │ 7 ║
╟───┼───┼───╫───┼───┼───╫───┼───┼───╢
║ 5 │ 2 │ 7 ║ 9 │ 4 │ 3 ║ 8 │ 6 │ 1 ║
╚═══╧═══╧═══╩═══╧═══╧═══╩═══╧═══╧═══╝
```