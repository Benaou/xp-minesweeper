# xp-minesweeper
HTML5 / JavaScript recreation of the classic Windows XP version of Minesweeper

Left-click to clear the space.
Right-click to mark mines.
Middle-click to clear surrounding mines if the number equals the number of marked mines around it.

Use +/- to increase/decrease difficulty:
- Beginner: 9x9 with 10 mines
- Intermediate: 16x16 with 40 mines
- Expert: 31x16 with 99 mines

First click generates the board and guarantees the spot you click is an open space to help get started.

Implemented an algorithm to help if you get stuck!
Press F to flag spaces that must be flags due to the number next to them. (e.g. an 8 means all 8 spaces around it must be flags)
Press S to sweep the field based off of the flags placed (essentially middle-clicks every square for you).
Press D to use more advanced techniques to find flags (e.g. the 121 pattern)
Press E to use more advanced tehniques to clear spaces
