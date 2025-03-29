# Tic-Tac-Toe Game

![Tic-Tac-Toe](https://img.shields.io/badge/Python-3.x-blue) ![Tkinter](https://img.shields.io/badge/Tkinter-GUI-orange)

A simple Tic-Tac-Toe game built with Python and Tkinter. This project allows two players to take turns marking "X" or "O" on a 3x3 grid, with the goal of getting three of their symbols in a row, column, or diagonal. The game includes a graphical user interface (GUI) and announces the winner or a draw at the end of each game.

## Features
- 3x3 game board with clickable buttons.
- Alternating turns between Player X and Player O.
- Win detection for rows, columns, and diagonals.
- Draw detection when the board is full with no winner.
- Pop-up messages to announce the winner or a draw.
- Automatic game reset after each round.

## Prerequisites
To run this project, you need:
- **Python 3.x** installed on your system. You can download it from [python.org](https://www.python.org/downloads/).
- **Tkinter**: This library comes pre-installed with Python. If it’s missing, you can install it:
  - On Windows: Tkinter is included with Python.
  - On Linux: Run `sudo apt-get install python3-tk` (for Debian/Ubuntu).
  - On macOS: Tkinter is usually included, but ensure you have a compatible Python version.

## Installation
1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/yourusername/tic-tac-toe.git
Replace yourusername with your GitHub username.

Navigate to the project directory:
cd tic-tac-toe
How to Run
Ensure you have Python installed (check with python --version or python3 --version).
Run the game by executing the Python script:
bash


python tic tac toe.py
Or, if your system uses python3:
bash


python3 tic tac toe.py
A window will open displaying a 3x3 grid. Click the buttons to play as "X" or "O."
Gameplay
The game starts with Player X.
Players take turns clicking empty buttons to place their symbol ("X" or "O").
The game checks for a winner after each move:
A player wins by getting three of their symbols in a row, column, or diagonal.
If the board is full and no one wins, the game ends in a draw.
A pop-up message announces the result, and the board resets for a new game.
File Structure
tic tac toe.py: The main Python script containing the game logic and GUI.
README.md: This file, providing project documentation.
Code Overview
The project uses:

Tkinter: For creating the GUI with a 3x3 grid of buttons.
Object-Oriented Programming: The game logic is encapsulated in a TicTacToe class.
Event Handling: Button clicks trigger moves, win checks, and game resets.
Future Improvements
Add a "Play Again" button instead of auto-resetting.
Include a score tracker for multiple rounds.
Enhance the GUI with colors or themes.
Add an AI opponent for single-player mode.
Contributing
Contributions are welcome! If you’d like to improve this project:

Fork the repository.
Create a new branch (git checkout -b feature-branch).
Make your changes and commit them (git commit -m "Add feature").
Push to your branch (git push origin feature-branch).
Open a Pull Request on GitHub.
License
This project is licensed under the MIT License. See the  file for details.

- Dipan
Happy coding! If you have questions or suggestions, feel free to open an issue on this repository.

