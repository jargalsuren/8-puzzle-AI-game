# 8-puzzle-AI-game
<br>

The 15-puzzle is a sliding tile game that was invented in the 1870s by Noyce Palmer Chapman. We
will focus primarily on its smaller cousin, the 8-puzzle, in this assignment. The game board consists
of eight sliding tiles bearing the numbers 1-8 that move on a 3 × 3 grid. When the puzzle is in the
solved state state, there is a blank space in the top left-hand corner, followed by the tiles in increasing
numerical order from left to right, top to bottom. Any tile horizontally or vertically adjacent to the
blank space can be moved into the space, effectively swapping the position of that tile and the space.
From a scrambled configuration of the tiles, the aim is to repeatedly move appropriate tiles into the
blank space until the tiles and blank square are restored to their solved configuration. This puzzle
easily generalizes to n
2 − 1 tiles, for any natural number n > 3.

In this project, we are coding up 8-puzzle and its natural generalizations to higher dimensions, applying the A* search algorithm with various admissible heuristics.
