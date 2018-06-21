# React-Tac-Toe Version: 0.0.1

## Description:
This project is a simple tic-tac-toe game built with React, Javascipt, HTML, and CSS.
React-Tac-Toe is based on Facebook's React tutorial.

## Game Capabilities Overview:
- Let's you play tic-tac-toe
- Indicates when one player has won the game
- Stores the hisory of moves during the game
- Allows players to jump back in time to see older versions of the game board

## How to run the project locally:

### Follow the instructions below by running the following terminal commands
First, copy the repository and clone the project locally:
```
git clone https://github.com/garrettmmoore/react-tac-toe.git
```
Next, move into the project directory:
```
cd react-tac-toe
```
Then, install node dependencies:
```
npm install
```
Finally, run the game:
```
npm start
```



## Three Components:
- Square: renders a single <button>
- Board: renders 9 squares
- Game: renders a board

## Next Up Version: 0.0.2:
- Display the location for each move in the format (col, row) in the move history list.
- Bold the currently selected item in the move list.
- Rewrite Board to use two loops to make the squares instead of hardcoding them.
- Add a toggle button that lets you sort the moves in either ascending or descending order.
- When someone wins, highlight the three squares that caused the win.
- When no one wins, display a message about the result being a draw.