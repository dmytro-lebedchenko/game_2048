# 2048 Game
1. Training project

2. <b>Project purpose:</b>
Implement the 2048 game like in [this reference](https://play2048.co/).

3. <b>Project task:</b>
  - The game field is 4 x 4
  - Each cell can be empty or contain one of the numbers: 2, 4, 8 ... 2^n
  - The player can move cells with keyboard arrows
  - All the numbers should be moved in the selected direction until all empty cells are filled in
     - 2 equal cells should be merged into a doubled number
     - The merged cell can’t be merged twice during one move
  - The move is possible if at least one cell is changed after the move
  - After move 2 or 4 appears in a random empty cell. 4 probability is 10%
  - When 2048 value is displayed in any cell, win message should be shown.
  - The `game over` message should be shown if there are no more available moves.
  - Hide start message when game starts.
  - Change the `Start` button to `Restart` after the first move.
  - Increase score with each move. The score should be increased by the sum of all merged cells.

3. <b>Tech stack:</b> HTML, CSS/SCSS, JavaScript.

4. [PREVIEW LINK](https://dmytro-lebedchenko.github.io/game_2048/)
