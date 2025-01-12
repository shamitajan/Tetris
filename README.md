# Tetris Game 🎮

Welcome to the **Tetris Game** project! This implementation of the classic Tetris game showcases clean object-oriented design and functionality, developed using [C++].

## 🎯 **Features**
- **Dynamic Gameplay**: Randomized pieces and rotations for a challenging experience.
- **Board Interaction**: Seamlessly handles block placement and movement.
- **Next Piece Preview**: Displays the upcoming piece to enhance strategy.
- **Real-time Rendering**: Efficient drawing of pieces and board in every frame.

## 🛠️ **Code Structure**
The project is built with a modular approach, leveraging object-oriented programming principles. Here's a brief overview of the key files:

1. **Game.h & Game.cpp**:
   - Manages the main game logic, including:
     - Piece initialization.
     - Drawing the board and pieces.
     - Switching to the next piece.

2. **Board**:
   - Handles the structure and layout of the Tetris board.
   - Includes methods to check for free blocks and block placement.

3. **Pieces**:
   - Defines the shapes and rotations of Tetris pieces.
   - Provides initial positions and block types.

4. **IO**:
   - Handles input/output operations, including drawing on the screen.

## 🚀 **Getting Started**
### Prerequisites
- A C++ compiler (e.g., GCC, MSVC).
- A Windows or Linux environment.

🎮 **Gameplay Instructions**
**Controls:**
Use arrow keys to move the pieces left, right, or down.
Press up arrow to rotate the piece.
Spacebar drops the piece instantly.
**Objective:**
Complete horizontal lines on the board to score points.
Avoid letting the blocks reach the top of the screen.

**📚 Code Highlights
Random Piece Generation:**
Pieces are generated using a random number generator seeded with the current time to ensure variability.
**Efficient Rendering:**
Blocks are rendered using pixel-perfect calculations for smooth visuals.
**Dynamic Board Management:**
Pieces integrate seamlessly with the board, and completed lines are cleared automatically.

📧 Contact
For feedback, suggestions, or collaboration, feel free to reach out:

Email: jshamita075@gmail.com
