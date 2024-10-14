# Tic Tac Toe Game 🎮

## Overview
This is a fully functional **Tic Tac Toe** game built using **React** with a stylish green-themed user interface. It supports two players taking turns to place their symbols ("X" and "O") on a 3x3 grid. The game tracks player actions, displays a game log, and announces the winner or a draw at the end of the game.

## Features
- **Two-player mode**: Players alternate between "X" and "O".
- **Winner Detection**: Automatically detects the winner or if the game ends in a draw.
- **Game Log**: Displays the history of moves, showing which player clicked which square.
- **Responsive Design**: Optimized for desktop and mobile devices with a sleek green theme.
- **Restartable**: Players can start a new game after each round.

## Technologies Used
- **React.js**: JavaScript library for building the user interface.
- **Tailwind CSS**: Utility-first CSS framework for styling.
- **JavaScript (ES6+)**: Includes modern JavaScript features like arrow functions and destructuring.

## Prerequisites
Make sure you have the following installed:

- **[Node.js](https://nodejs.org/)**: To run the development server.
- **npm**: Installed with Node.js.

## Project Structure

tic-tac-toe-game/
│
├── src/
│   ├── components/
│   │   ├── GameBoard.jsx
│   │   ├── Player.jsx
│   │   ├── Log.jsx
│   │   ├── GameOver.jsx
│   ├── App.jsx
│   ├── main.jsx
│   ├── winning-combinations.js
│
├── public/
│   ├── index.html
│
├── package.json
├── README.md
└── .gitignore

## Game Logic
The game board is represented by a 3x3 grid. Each player takes turns clicking on an empty square to place their symbol ("X" or "O"). The game checks for a winner after every move by comparing the current state of the game board against all possible winning combinations (rows, columns, diagonals). The game also checks for a draw when all squares are filled without a winner.

## Contributing
If you would like to contribute to the project, feel free to open a pull request or issue. All contributions and suggestions are welcome!

## License
This project is licensed under the MIT License - see the LICENSE file for details.
