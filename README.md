# Tetris Game made with C++ and RayLib 

A classic Tetris game implemented in C++ using the Raylib graphics library. This project includes core Tetris functionalities such as block movement, rotation, collision detection, row clearing, scoring, and sound effects.

![image](https://github.com/user-attachments/assets/c7430595-5ef9-4078-ba20-710bfbb87fc9)

![image](https://github.com/user-attachments/assets/6a56a379-320a-49c7-ae17-fe6c74032031)


## Project Structure
1. `game.cpp / game.h`: Controls the main game execution loop and manages the core gameplay mechanics.
2. `grid.cpp / grid.h`: Creates and manages the Tetris grid with rows and columns, allowing blocks to move, rotate, and stack within the grid.
3. `block.cpp / block.h / colors.h / colors.cpp`: Defines the different Tetris blocks (tetrominoes) with unique shapes and colors.
4. `position.cpp / position.h`: Manages block positions within the grid, including movement (left, right, down) and rotation logic to fit blocks within available spaces.

## Features
1. Game Loop: Manages the core game flow and state transitions.
2. Grid Creation: Generates a Tetris grid where blocks can move and stack.
3. Tetromino Blocks: Implements various Tetris blocks with unique colors and shapes.
4. Movement & Rotation: Blocks can move left, right, down, and rotate to fit available spaces within the grid.
5. Collision Detection: Prevents blocks from moving through other blocks or outside the grid boundaries.
6. Row Clearing: Removes completed rows and shifts blocks down accordingly.
7. Game Over Detection: Ends the game when blocks reach the top of the grid.
8. User Interface: Displays current score, level, and game status.
9. Scoring System: Awards points for each cleared row, with higher scores awarded as levels progress.
10. Sound Effects: Adds audio feedback for actions like block placement and row clearing, enhancing the game experience.
