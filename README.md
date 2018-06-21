# **React-Tac-Toe - 0.0.1**

## **Description:**
React-Tac-Toe is a simple tic-tac-toe game bootstrapped with Create React App.

This project is based off of Facebook's React tutorial.

## **Development Tools:**

- _Languages:_ Javascipt, HTML, and CSS

- _Frameworks:_ React.js

## **Game Capabilities:**
- Let's you play tic-tac-toe.
- Indicates when one player has won the game.
- Stores the hisory of moves during the game.
- Allows players to jump back in time to see older versions of the game board.

## **How to run the project locally:**

### _Follow the instructions below and run the provided terminal commands_.
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

## **Game Consists of 3 Components:**
- _Square:_ renders a single button
- _Board:_ renders 9 squares
- _Game:_ renders a board

## **Upcoming Features - 0.0.2:**
- Display the location for each move in the format (col, row) in the move history list.
- Bold the currently selected item in the move list.
- Rewrite Board to use two loops to make the squares instead of hardcoding them.
- Add a toggle button that lets you sort the moves in either ascending or descending order.
- When someone wins, highlight the three squares that caused the win.
- When no one wins, display a message about the result being a draw.