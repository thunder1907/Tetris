# 🎮 Tetris Game in C++

This is a console-based implementation of the classic Tetris game using C++. The project includes all the standard Tetris mechanics such as falling tetrominoes, line clearing, scoring, and game-over conditions.

## 🚀 Features

- **🧩 Tetromino Pieces**: All seven standard tetrominoes (I, O, T, S, Z, J, L) are implemented.
- **📊 Grid Representation**: The game board is a 10x20 grid.
- **🎮 Piece Movement**: Players can move pieces left, right, rotate, and drop them.
- **⏳ Gravity**: Tetrominoes fall at a constant speed, which increases as the game progresses.
- **🚫 Collision Detection**: Prevents blocks from overlapping or moving out of bounds.
- **🧹 Line Clearing**: Full rows are removed, and the grid shifts downward.
- **🏆 Scoring System**: Points are awarded for cleared lines.

## 🕹️ Controls

- **⬅️ Left Arrow (←)**: Move the piece left.
- **➡️ Right Arrow (→)**: Move the piece right.
- **🔼 Up Arrow (↑)**: Rotate the piece.
- **🔽 Down Arrow (↓)**: Soft drop (move the piece down faster).
- **␣ Spacebar**: Hard drop (instantly drop the piece to the bottom).
- **⏏️ Escape (ESC)**: Pause or quit the game.

## 🎲 Game Progression

- The falling speed of tetrominoes increases after a certain number of cleared lines.
- The current score and level are displayed on-screen.
- The game ends when blocks reach the top of the grid.

## 💻 Technical Details

- **🖥️ Language**: C++ (C++17 or later recommended).
- **📂 Data Structures**: Structs or classes are used to represent tetrominoes.
- **📊 Grid Representation**: 2D arrays or vector-based grids are used for the game board.
- **⌨️ Input Handling**: Real time user input is handled efficiently.
- **🚫 Collision Detection**: Efficient collision detection and game logic are implemented.

## 🛠️ How to Run

1. Clone the repository to your local machine.
2. Compile the source code using a C++ compiler (e.g., `g++`).
3. Run the executable file to start the game.

```bash
g++ -o tetris main.cpp
./tetris
