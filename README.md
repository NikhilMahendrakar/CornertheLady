# Corner the Queen

Corner the Queen is a strategic game where the goal is to move the queen piece to the bottom-left corner (a1) of an 8x8 board before the AI does.

## Table of Contents

- [Game Rules](#game-rules)
- [Features](#features)
- [AI Difficulty Levels](#ai-difficulty-levels)
- [How to Play](#how-to-play)
- [Setup](#setup)
- [Contributing](#contributing)
- [License](#license)

## Game Rules

1. The game is played on an 8x8 grid.
2. The queen starts on any cell in the top row or the rightmost column.
3. The queen can move west (left), south (down), or southwest (diagonally down-left).
4. The player and the AI alternate turns.
5. The goal is to move the queen to the lower-left corner (a1).
6. The player who moves the queen to a1 wins the game.

## Features

- Interactive 8x8 game board.
- AI opponent with three difficulty levels: Easy, Medium, and Hard.
- Visual representation of possible moves.
- Game rules are accessible via a button.
- Simple and intuitive user interface.

## AI Difficulty Levels

- **Easy**: AI makes random valid moves.
- **Medium**: AI uses a minimax algorithm with a depth of 2.
- **Hard**: AI uses a minimax algorithm with a depth of 4.

## How to Play

1. Load the game in your browser.
2. Click on the cells to move the queen.
3. Alternate turns with the AI.
4. The game ends when the queen reaches the bottom-left corner (a1).
5. Click the "Rules" button to view the game rules.
6. Choose AI difficulty using the dropdown menu.

## Setup

To set up and run the game locally, follow these steps:

1. Clone the repository:

    ```bash
    git clone https://github.com/yourusername/corner-the-lady.git
    cd corner-the-lady
    ```

2. Open the `game.html` file in your preferred web browser to start the game.

## Contributing

Contributions are welcome! If you have any suggestions or find any bugs, please open an issue or create a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

