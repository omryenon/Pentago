# Pentago - what is that?
 
 Pentago is a 2 player abstract strategy invented by Tomas Floden.
 This game is played on a 6x6 grid subdivided into four
 3x3 subgrids. The game begins with an empty grid.  On each turn, a player
 places a token in an empty slot on the grid, then rotates one of the
 subgrids either clockwise or counter-clockwise.  Each player attempts to
 be the first to get 5 of their own tokens in a row, either horizontally,
 vertically, or diagonally.

 # This project

 This program simulates a game between 2 Players. Each of them can be a human or computer.
 So, you can play against your friend, against the computer or watch the computer plays against itself.
 The initial grid can be an empty grid (Classic game), or a partially stuffed grid (for analyzing the game).

The Computer's Algorithm for determine each move is based on Mini-Max Algorithm. For more information you are welcome to take a look in the Documentation attached to the repository.

# Running the Program

For an empry grid run - python3 Pentago.py , for partially stuffed grid run Pentago.py BOARDSTATE : for example- python3 Pentago.py -b "w.b.bw.w.b.wb.w..wb....w...bw.bbb.ww"

In the beginning of the game you will be required for: Names of Players, player types (computer/human), player tokens (black/white).

Enjoy!