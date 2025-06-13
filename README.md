# Checkers
A classic 2-player Checkers game implemented in C with full board logic, piece promotion to kings, and turn-based gameplay in the terminal.

## 🎮 Game Overview

- This project simulates a traditional 8x8 Checkers board in the console. It allows two players to:
- Enter their names
- Choose their own symbols (X or O)
- Play in alternating turns
- Promote pieces to kings upon reaching the opponent's baseline
- Automatically detect and handle legal/illegal moves, captures, and wins
- Terminal colors are used for better visualization of players and kings.

## 🧠 Key Features

- Turn-based 2-player gameplay
- Symbol selection with input validation
- Piece movement & capturing with logic for both sides
- King piece logic (up/down movement)
- Win detection when all opponent pieces are eliminated
- Interactive board rendering after every move

## 🛠️ Technologies Used

- Language: C
- Console Library: ANSI escape codes (for color)
- IDE Tested On: Turbo C++, Code::Blocks, GCC (Windows)

## 🗂️ File Structure
.
├── CHECKERS GAME.c       # Main source file
├── README.md             # Project documentation

## ▶️ How to Compile & Run

### On GCC (Linux/Mac/Windows):
gcc "CHECKERS GAME.c" -o checkers
./checkers

### On Turbo C++ / Code::Blocks:

- Create a new project
- Add the CHECKERS GAME.c file
- Compile and Run
Ensure your terminal supports ANSI escape sequences for colors (or comment them out if unsupported).

## 📜 License

This project is licensed under the MIT License.

## 💡 Future Improvements

- Add AI player with basic heuristics
- GUI version with SDL or OpenGL
- Save/load game state feature
- Multiplayer over LAN/Internet
