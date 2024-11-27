# Brick Breaker Game

This is a simple **Brick Breaker** game built using Java and the `Swing` library. It is a work-in-progress project that includes the core mechanics for a playable game. The goal of the game is to break all the bricks by bouncing a ball off a paddle.

## Features
- Paddle movement using arrow keys.
- Ball movement with initial setup.
- Border constraints for paddle and ball.

## How to Run
1. Clone the repository or download the files.
2. Compile and run the `Main.java` file using any Java IDE or command-line tool.
   ```bash
   javac Main.java Gameplay.java
   java Main
3. Use the arrow keys to move the paddle:
Right Arrow: Move paddle right.
Left Arrow: Move paddle left.

##Future Improvements
- Implement a MapGenerator class for creating and rendering bricks.
- Add sound effects and animations for a better user experience.
- Add a scoring system for tracking performance.
- Implement levels or difficulty progression.

##Preview
Here's an outline of what the game currently looks like:

Paddle: A green rectangle at the bottom of the screen.
Ball: A yellow square that starts moving.
Borders: Yellow lines on the edges of the window.

## Missing Features
This version is a prototype. It lacks the following features, which I'll implement to complete the game:
1. **Brick Map**: Add bricks and track their state.
2. **Collision Detection**: Detect and handle collisions between the ball and bricks, paddle, and walls.
3. **Game Over and Win States**: Handle game-end conditions (when all bricks are cleared or the ball drops below the paddle).
4. **Timer Functionality**: Un-comment and implement the timer for smooth ball movement.

