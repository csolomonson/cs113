# SudokuSolver
Author: Cole Solomonson
CS113 SU24

## Description
This project solves basic 9x9 Sudoku games using a flexible set of algorithms. The code works by assigning each Tile object to three Group objects: a Row, Column, and Square. There are strategies implemented that systematically deal with each Tile and Group to logically eliminate possibilities and solve tiles. Whenever a Tile or Group strategy successfully eliminates a possibility, any affected Tiles and Groups are added to a stack to be examined next. Further, at the beginning of each step, the Groups and Tiles are heap sorted by “solvedness” to ensure that more solved Tiles and Groups are examined first. This stack guarantees that any breakthroughs that are possible are made in each given step.
## Background
I was inspired to make this project when I was playing Sudoku on my phone. I realized that the strategy that I was using could be automated pretty simply, and started thinking about how different Groups intersect and interact. 
## Note to the teacher
I regrettably had a lot of progress for this project lost when the replit course was deleted. I didn’t realize that I had lost my project until this Sunday afternoon. I tried to get everything back to a working state, but with only a few hours, I wasn’t able to. I understand that I won’t get full credit for this project, since it isn’t working. I hope you can look at my code and see this project for what it was meant to be, and not what it currently is.  
## Wireframe
## UML
