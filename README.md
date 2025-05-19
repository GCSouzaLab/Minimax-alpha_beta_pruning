# Minimax-alpha_beta_pruning

| Element  | Definition |
| -------- | -------    |
| **Estado Inicial**    |   Matriz do jogo da velha vazia                                                                 |

| **Estado Objetivo**   | Formar uma sequência de três "X" na horizontal, vertical ou diagonal                            |

| **Função Sucessor**   | Jogadores escolhem um elemento não marcado para marcarem com seu respectivo síbolo ("X" ou "O") |

| **Custo de Caminho**  | Ganhou o jogo = 1, Perdeu o Jogo = -1, Empatou = 0                                              |


##### **Resumo:**
The game starts in a 3x3 matrix and the player's objective is to form a sequence of three identical symbols horizontally, vertically or diagonally before his opponent can do the same. 

Each player can place one symbol across the matrix. 

The game ends when one of the players completes the sequence described above or the matrix is ​​completely filled without a final result.

