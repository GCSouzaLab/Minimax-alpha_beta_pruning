# Minimax-alpha_beta_pruning

| Element  | Definition |
| -------- | -------    |
| **Initial State**     |   Empty tic-tac-toe matrix  |

| **Objective State** | Form a sequence of three "X's" horizontally, vertically or diagonally |

| **Successor Function** | Players choose an unmarked element to mark with their respective symbol ("X" or "O") |

| **Road Cost** | Won the game = 1, Lost the game = -1, Drawn = 0 |

##### **Resume:**
The game starts in a 3x3 matrix and the player's objective is to form a sequence of three identical symbols horizontally, vertically or diagonally before his opponent can do the same. 

Each player can place one symbol across the matrix. 

The game ends when one of the players completes the sequence described above or the matrix is ​​completely filled without a final result.

