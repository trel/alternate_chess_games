# Alternate Chess Games

## Table of Contents
 - [Tank Chess](#tank-chess)
 - [Tower Chess](#tower-chess)
 - [Poison Tower Chess](#poison-tower-chess)
 - [Good and Evil Chess](#good-and-evil-chess)
 - [Tunnel Chess](#tunnel-chess)
 - [King Archer Chess](#king-archer-chess)
 - [King Pawn Chess](#king-pawn-chess)

## Tank Chess
- Dec 5, 2020, E and T

1. If any piece lands on the center square comprised of spaces 4d 4e 5d 5e, then the tank clears all pieces currently on rows 4 and 5, including the just-placed piece

2. The tank does not affect regular turn-taking

--------------
## Tower Chess
- Dec 5, 2020, O and T

1. A tower stands where it is built

2. A tower cannot move

3. A tower can be built by moving a piece into the space of a piece/tower of the same color:

 | Tower Type | Straight Range | Diagonal Range | Can Attack Through (Jump) Own Pieces | Once Attacked |
 | :---        |    :----:   |     :----:  |    :----:  |   :--- |
 | rook-rook-queen | infinite | infinite | no | rook-queen-2 |
 | rook-rook-rook | infinite | 0 | no | rook-rook-2 |
 | rook-rook-bishop | 4 | 4 | no | rook-rook-2 or rook-bishop-2 |
 | rook-rook-knight | 4 | 0 | yes | rook-rook-2 or rook-knight-2 |
 | rook-rook-pawn | 4 | 1 (forward only) | no | rook-rook-2 or rook-pawn |
 | rook-queen-2 | 4 | 4 | no | rook-queen |
 | rook-rook-2 | 4 | 0 | no | rook-rook |
 | rook-bishop-2 | 2 | 2 | no | rook-bishop |
 | rook-knight-2 | 3 | 0 | yes | rook-knight |
 | rook-queen | 2 | 2 | no | falls |
 | rook-rook | 2 | 0 | no | falls |
 | rook-bishop | 1 | 1 | no | falls |
 | rook-knight | 2 | 0 | yes | falls |
 | rook-pawn | 2 | 1 (forward only) | no | falls |

4. When a tower attacks a piece, the piece is removed from the board

5. When a tower attacks a tower, the attacked tower drops a level

6. When a piece attacks a tower:
   - the piece takes the place of the fallen tower  
     OR
   - the tower drops a level
     - if non-knight, the piece lands in the space in front of the tower
     - else, the knight can choose to land in one of two spaces
       - if both spaces are occupied, the knight does not move

---------------------
## Poison Tower Chess  
- Dec 5, 2020, E and O

Same as Tower Chess but with the following changes:

1. When the king is in one of the 8 squares around a tower (of his making) he can poison an empty square within range of the tower.

2. Each tower can launch one poison bomb per game.

3. The poison bomb stays in that particular square for the REST of the game.

4. If any piece lands/walks on/over the poison square it is removed from the board.

---------------------
## Good and Evil Chess
- Dec 12, 2020, E and T

1. Each player may mark one unoccupied square as either good or evil
2. It takes a turn to mark a square as good or evil
3. Both good and evil squares last throughout the game
4. Good squares
   - If any piece lands on a good square, that player restores one removed piece
     - The restored piece must be placed on one of its original unoccupied spaces (queen on queen space, knight on either knight space, etc.)
   - A king is in check behind/through a good square
5. Evil squares
   - If any piece lands/walks on/over an evil square, that piece is removed from the board
   - A king is not in check behind/through an evil square
   
---------------------
## Tunnel Chess
- Dec 20, 2020, E and O and T

1. Two ends of the tunnel can be dug on the board, one by each player
2. An end may be dug at any time during the game
3. It takes a turn to dig an end of the tunnel
4. When only a single end of the tunnel has been dug
   - If any piece lands/walks on/over the end, that piece is removed from the board
5. Once both ends of the tunnel have been dug
   - If any piece lands/walks on/over either end, that piece is placed at the other end of the tunnel
   - If a piece can attack an end of the tunnel, a king on the other end is in check.
   - The tunnel is bidirectional, pieces can enter and exit either end
   - The tunnel is usable by both players
6. The tunnel is blocked if the other end of the tunnel is occupied by a piece of the same color
   - If the tunnel is blocked, a king is in check behind/through the open end of the tunnel

---------------------
## King Archer Chess
- Dec 20, 2020, E and O and T

1. Each king carries a bow and can shoot arrows straight and diagonal

2. A king is in check if he is within range of the other king's arrow

 | Game Element | Default | Alternate Values |
 | :---   |  :----:  |  :----:  |
 | Number of Arrows | 3 | 1-infinite | 
 | Arrow Range | 4 | 1-infinite | 
 | Over Other Pieces | yes  | no |
 | Arrow Protection/Shield | pawns  | other pieces / none | 

---------------------
## King Pawn Chess
- Dec 4, 2021, E and O and T

1. Every pawn can move (and attack) like a king, in addition to its regular initial two-square advance

 | Game Element | Default | Alternate Values |
 | :---   |  :----:  |  :----:  |
 | Pawn Protection/Shield | none | other pieces | 
