# Snake Game in Java

This is a simple Snake Game implemented in Java using Swing for graphical interface and AWT for event handling.

## Project Structure

The project consists of three main classes:

1. **SnakeGame**:
   - Contains the main method to initialize the game.
   - Creates an instance of GameFrame.

2. **GameFrame**:
   - Extends `JFrame` to create the main game window.
   - Sets up the game's UI components and properties.
   - Initializes an instance of GamePanel.

3. **GamePanel**:
   - Extends `JPanel` and implements `ActionListener` for game logic and rendering.
   - Manages the game mechanics such as snake movement, collision detection, and apple spawning.
   - Handles user input using a custom key adapter (`MyKeyAdapter`).
   - Displays game over screen and updates score.

## Getting Started

To run the Snake Game on your local machine, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/snake-game-java.git

2. Open the project in your preferred Java IDE (e.g., IntelliJ IDEA, Eclipse).
3. Navigate to SnakeGame.java and run the main method.
4. Use the arrow keys (Up, Down, Left, Right) to control the snake.
   - Navigate through the game area, eat apples to score points, and avoid colliding with the snake's own body or the game borders.
  
## Features
- **Snake Movement:** Control the snake using arrow keys.
- **Apple Spawning:** Randomly generates apples for the snake to eat.
- **Collision Detection:** Detects collisions with borders and the snake's body.
- **Game Over:** Displays a game over screen when the snake collides, showing the final score.

## Future Improvements
- Implement levels with increasing difficulty.
- Add sound effects and background music.
- Incorporate high score tracking and display.
