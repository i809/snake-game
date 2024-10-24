# snake-game
# Snake Game - Java Mini Project

This is a simple implementation of the classic Snake Game using Java. The game is built with Java Swing for the graphical user interface and basic object-oriented programming principles.

## Project Structure

/snake_game
├── bin
│   └── Compiled class files (auto-generated)
└── src
    └── snake_game
        ├── GameFrame.java      // Main window frame for the game
        ├── GamePanel.java      // Main game logic, rendering, and event handling
        └── SnakeGame.java      // Entry point to run the game

## How to Play

- Use the arrow keys (`↑`, `↓`, `←`, `→`) to control the movement of the snake.
- Eat the food to grow the snake and increase your score.
- Avoid running into the walls or the snake's own body to prevent the game from ending.

## How to Run

1. Clone the repository:

    ```bash
    git clone https://github.com/yourusername/SnakeGame.git
    ```

2. Navigate to the project directory:

    ```bash
    cd SnakeGame/eclipse-workspace/snake_game/src/
    ```

3. Compile the Java files:

    ```bash
    javac snake_game/*.java
    ```

4. Run the game:

    ```bash
    java snake_game.SnakeGame
    ```

## Features

- **Simple and Intuitive Gameplay**: Control the snake using arrow keys.
- **Score Tracking**: The player's score increases as the snake eats food.
- **Game Over**: The game ends when the snake collides with itself or the walls.
- **Dynamic Difficulty**: The game becomes progressively challenging as the snake grows longer.

## Future Enhancements

- Add support for levels and increasing speed as the game progresses.
- Implement power-ups and obstacles for a more challenging gameplay experience.
- Introduce a multiplayer mode or an online leaderboard.

## Requirements

- **Java 8** or higher
- Basic Java knowledge to modify or extend the game features.
