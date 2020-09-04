# DotsBoxesAdversarialSearch
A project that allows the user to play a game of the pencil and paper game with either a computer player that chooses randomly from the open moves, 
or one that uses the minimax algorithm with alpha beta pruning.  

Note that the minimax algorithm can be quite computationally expensive, with a non-polynomial asymptotic behavior. I tried to limit the depth such that
the computer player never takes more than 5 minutes. However, based on the grid size you're playing on, and your own personal machine, you mileage will 
likely vary. 

I reccomend playing on a 4 x 4 grid, but the program allows for any grid size up to 1000 nodes that doesn't mess up the graphics, or a 16 x 62 to 2 x 500 grid.
