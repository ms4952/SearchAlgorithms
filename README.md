# SearchAlgorithms
Sliding Brick Game
A sliding brick puzzle is played on a rectangular w by h board (w cells wide and h cells tall). Each cell in the board can be either 
free, have a wall, or be the goal.
On top of the board (over some of the free cells) there is a set of solid pieces (or bricks) that can be moved around the board. 
One of the bricks is special (the master brick).
A move consists of sliding one of the bricks one cell up, down, left or right. Notice that bricks collide with either walls or other
bricks, so we cannot move a brick on top of another. Bricks can only slide, they cannot rotate nor be flipped.
To solve the puzzle, we have to find a sequence of moves that allows you to move the master brick on top of the goal. 
No other pieces are allowed to be placed on top of the goal

The code constitutes following 
a function that given a state and a positive integer N, does the following: 1) generate all the moves that can be generated in the board,
2) select one at random, 3) execute it, 4) normalize the resulting game state, 5) if we have reached the goal, or if we have executed N 
moves, stop; otherwise, go back to 1.
A function that solves a given sliding bricks puzzle using a breadth-first strategy.
A function that solves a given sliding bricks puzzle using a depth-first strategy.
A function that solves a given sliding bricks puzzle using an iterative deepening search strategy.
