# Board-Game
Space themed board game inspired by chess.\
The players first decide whether the game ends after a certain amount of time or certain amount of turns.\
A player can move 3 times each turn or until their time per turn runs out(if they decide the game ends after a certain amount of time).\
After the game ends, the winner is the player with more pieces left.\
\
The game starts with 4 rows of pieces on both sides.\
There are powerups indicated by a ? on the board which upgrade pieces to level 2 when collected.\
The powerups spawn on a random tile on row 8 or 9 every 3 turns.\
There are asteroids which pieces cannot move onto.\
There are portals which teleport the piece to the other portal, destroying any piece near it.\
\
Pieces in the front row are called transport pieces. They can move 4 tiles and cannot attack. They are used for collecting powerups.\
Pieces in the 2nd row(from the front) are called defence pieces. They can move and attack with a range of 1 tile, but can only be destroyed by pieces in the third row.\
Pieces in the 3rd row(from the front) are called attack pieces. They can move two tiles and attack with a range of 1 tile.\
Pieces in the back row are called ranged pieces. They can move one tile and attack with a range of 3 tiles.\
\
An upgraded transport piece can transfer its upgrade to another piece 1 tile away. If it collects another powerup, it can spawn another piece in typed into the terminal. The piece name is t for transport, d for defence, a for attack, and r for ranged.\
An upgraded defence piece can only be destroyed by an upgraded piece from the 3rd row.\
An upgraded attack piece can destroy upgraded defence pieces.\
An upgraded ranged piece can move one tile and attack with a range of 4 tiles.\
\
Make sure you are in the correct path when running the file.\
\
cd path\
python Piano.py
