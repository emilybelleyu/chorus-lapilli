# chorus-lapilli
Implementation of a variant of terni lapilli.

Terni lapilli (“three grains”) is a popular board game in ancient Rome, whereas this variant is chorus lapilli (“dancing grains”).

Chorus lapilli is like tic-tac-toe in that players take turn placing pieces on a 3×3 board and the goal is to get three pieces in a row. However, it differs from tic-tac-toe in two ways:

- After your first three moves, instead of adding further pieces you must instead move one of your existing pieces to an adjacent empty square. Therefore, after your third move you always occupy three squares. The move can be up, down, left, right, or diagonal.
- If it is your turn to move and you have three pieces on the board and one of your pieces is in the center square, your move must either win or vacate the center square.

After cloning the repo, play by running:
```
npm install && npm start
```