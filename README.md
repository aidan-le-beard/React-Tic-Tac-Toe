# React-Resizable-Tic-Tac-Toe-and-Co-Caro

Check it out in action on my website: https://aidan-le-beard.github.io/React-Resizable-Tic-Tac-Toe-and-Co-Caro/

### To execute on Windows:

1) Download all code (git clone https://github.com/aidan-le-beard/React-Tic-Tac-Toe)
2) Open command prompt
3) cd over to the folder where the files are located
4) Have react installed (npm install)
5) Run "npm start"
6) If it doesn't open automatically, go to http://localhost:3000/

### Sample Output:

![image](https://github.com/aidan-le-beard/React-Resizable-Tic-Tac-Toe-and-Co-Caro/assets/33675444/cb39092d-4948-4db6-859b-95fe6fb4e773)

### Personal Improvements:

1) For the current move only, show "You are at move #..." instead of a button.
2) Rewrote Board to use a singular loop to make the squares, instead of hardcoding them.
3) Added a toggle button to sort the moves in either ascending or descending order.
4) Added highlighting to the X amount of squares that caused the win.
5) If no one wins, displays a message about the result being a draw.
6) Displayed the location for each move in the format (row, col) in the move history list.
7) Rewrote calculateWinner() to calculate winning lines based on board size, rather than hardcoding them.
8) Rewrote calculateWinner() to calculate win condition based on number in a row required to win, rather than hardcoding it.
9) Added dropdown/select menu to change board size.
10) Added dropdown/select menu to change how many Os/Xs in a row to win.
11) Dynamically disable select options based on options chosen, so game remains winnable at all times.
12) Added Co Caro (Cờ Carô) blocked rule option: if both sides of a winning line are blocked by opponent, it doesn't win.