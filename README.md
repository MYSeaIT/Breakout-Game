# Breakout Game

## Introduction
This project is a simple implementation of the classic Breakout game using HTML5 Canvas, CSS, and Vanilla JavaScript. Players control a paddle with the keyboard to bounce a ball and break bricks.

## Game Features
- Responsive canvas gameplay area
- Score tracking
- Paddle and ball dynamics
- Collision detection between ball, bricks, and walls
- Restart game feature when all bricks are cleared

## Development Setup
To run this game, open the index.html file in a modern web browser. No additional server or dependencies are required.

## Challenges and Resolutions
During the development, we've encountered several issues, which are outlined below:

**Challenge 1: Ball Collision Detection**
- *Error:* The ball was passing through bricks occasionally without detecting a collision.
- *Resolution:* Adjusted the collision detection algorithm to account for the ball's diameter.

**Challenge 2: Paddle Movement**
- *Error:* The paddle would continue to move even after the key was released.
- *Resolution:* Implemented keyUp event to stop the paddle movement when the arrow keys are released.

**Challenge 3: Game Responsiveness**
- *Error:* The canvas would not resize based on the browser window size, leading to inconsistent gameplay.
- *Resolution:* Added event listeners to adjust the canvas size and game elements dynamically on window resize.

**Challenge 4: Performance Optimization**
- *Error:* The game animation was not smooth in some browsers.
- *Resolution:* Utilized requestAnimationFrame for better performance and smoother animations.

**Challenge 5: Paddle Control Limits**
- *Error:* The paddle was able to move outside the canvas boundaries.
- *Resolution:* Added constraints to the paddle movement to keep it within the canvas.

**Challenge 6: Score Reset**
- *Error:* The score would not reset after the game was restarted.
- *Resolution:* Added a function to reset the score when all bricks were broken.

## Conclusion
The development of this Breakout Game project has been a rewarding experience, offering insights into game development with JavaScript and HTML5 Canvas. The encountered challenges have led to a more robust and enjoyable game.
