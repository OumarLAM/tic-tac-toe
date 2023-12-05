# 🎮 Tic-Tac-Toe React App 🎮

This is a simple React app that lets you play the classic tic-tac-toe game with another player on the same browser. You can also see the history of moves and jump to any previous state of the game.

## 🛠️ Technologies Used 🛠️

- **React**: A JavaScript library for building user interfaces
- **useState**: A React hook that lets you add state to functional components

## 🚀 How to Run 🚀

1. Clone this repository and navigate to the project folder
    ```bash
        git clone https://github.com/OumarLAM/tic-tac-toe.git
        cd tic-tac-toe
    ```
2. Install the dependencies with `npm install`
3. Start the app locally with `npm start`
4. Open http://localhost:3000 to view it in the browser

## 📜 Available Commands 📜

- `npm start`: Start the app locally in your development environment, by default it will be in http://localhost:3000.
- `npm test`: Run tests using watch mode.
- `npm run lint`: Run linter.

## 📚 Code Structure 📚

- The main component of the app is the `Game` component, which renders the `Board` and the `Square` components.
- The `Game` component also keeps track of the history of moves, the current move, and the next player.
- The `Board` component displays the status of the game and the 3x3 grid of squares.
- The `Square` component renders a single button that shows either 'X', 'O', or nothing.
- The `Board` component handles the logic of placing a mark on a square, checking for a winner, and clearing the lines.
- The `Game` component handles the logic of switching between moves and resetting the game.

## 🧩 Helper Functions 🧩

- `calculateWinner`: A function that takes an array of 9 squares and returns the winner ('X', 'O', or null) based on the rules of tic-tac-toe.

## 💡 Ideas for Improvements 💡

Here are some ideas for improvements that you could make to the tic-tac-toe game, listed in order of increasing difficulty:

1. For the current move only, show “You are at move #…” instead of a button.
2. Rewrite Board to use two loops to make the squares instead of hardcoding them.
3. Add a toggle button that lets you sort the moves in either ascending or descending order.
4. When someone wins, highlight the three squares that caused the win (and when no one wins, display a message about the result being a draw).
5. Display the location for each move in the format (row, col) in the move history list.

## Author 👤

- [Oumar LAM](https://github.com/OumarLAM)