# Classic Snake Game in C 🐍

A highly efficient, console-based implementation of the classic Snake game written entirely in C. This project leverages the Windows API for real-time console manipulation, ensuring smooth, flicker-free rendering and responsive keyboard inputs.
## ✨ Technical Features

* **Flicker-Free Rendering:** Utilizes Windows API (`SetConsoleCursorPosition`) to overwrite console output dynamically instead of clearing the screen, eliminating visual stuttering.
* **Real-Time Input Handling:** Uses `_kbhit()` and `_getch()` for non-blocking, asynchronous keystroke detection.
* **Dynamic Data Tracking:** Employs array manipulation to manage the snake's growing tail logic seamlessly.
* **Modular Architecture:** Cleanly separated game logic (`Setup`, `Draw`, `Input`, `Logic`) for high maintainability.

## 🚀 Getting Started

**Prerequisites:**
You will need a C compiler like GCC (MinGW for Windows) installed on your system.

**Compilation & Execution:**
1. Clone this repository: `git clone https://github.com/YourUsername/snake-game-c.git`
2. Navigate to the directory: `cd snake-game-c`
3. Compile the source code: `gcc src/snakegame.c -I include -o bin/snakegame.exe`
4. Run the game: `./bin/snakegame.exe`

## 🧠 Core Technologies & Concepts
* C Programming Language
* Windows API (`windows.h`)
* Game Loop Architecture

## 🤝 Let's Connect
Designed and developed by **Punit**. 
Let's talk about tech, logic-driven applications, and game development on [LinkedIn](https://www.linkedin.com/in/punitbhyan).
