# Tic Tac Toe Game

A simple Python-based Tic Tac Toe game where a user plays against an AI. The game allows user input and evaluates win/tie conditions after each move.

## Features

- **User vs AI Gameplay:**
  - The user enters their move manually.
  - The AI makes random valid moves.

- **Board Initialization:**
  - Creates a 3x3 game board using NumPy.

- **Move Validation:**
  - Ensures the user enters valid row and column indices (0-2).
  - Prevents moves in already occupied positions.

- **Win/Tie Detection:**
  - Checks for horizontal, vertical, and diagonal wins.
  - Determines if the game ends in a tie.

## How to Run

1. **Clone the Repository:**

   ```bash
   git clone <repository-url>
   cd <repository-directory>
