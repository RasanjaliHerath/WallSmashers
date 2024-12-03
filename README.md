# Wall Smashers - Brick Breaker Game

## Overview

**Wall Smashers** is a classic "Brick Breaker" game built using HTML5, JavaScript, and the `<canvas>` element. The player controls a paddle at the bottom of the screen to bounce a ball and break bricks positioned at the top. The game continues until all bricks are destroyed or the ball falls past the paddle.

## Key Features

- **HTML5 Canvas**: The game utilizes the HTML5 `<canvas>` element to render the game visuals, including the ball, paddle, bricks, and score.
  - The canvas dimensions are set to 900px (width) by 600px (height) for an optimal game area.
  
- **Game Objects**:
  - **Ball**: A red ball moves around the canvas, bouncing off walls, the paddle, and bricks.
  - **Paddle**: A green rectangular paddle positioned at the bottom of the screen. The player controls the paddle using the arrow keys.
  - **Bricks**: Green rectangular bricks arranged in a grid. The ball destroys the bricks when it collides with them, and the score increases.
  - **Score**: The score is displayed in the top-left corner, incrementing every time a brick is destroyed.
  
- **User Input**: 
  - The player can move the paddle left or right using the arrow keys. The paddle is restricted from moving outside the canvas bounds.

- **Game Mechanics**:
  - **Collision Detection**: The game detects collisions between the ball and bricks, paddle, and walls. The ball bounces off walls, the paddle, and the top edge of the screen. When it hits a brick, the brick is destroyed.

    ## Output
  
![ws](https://github.com/user-attachments/assets/86bd4f2d-54ab-48b7-9a44-3e9535f45718)


![GameOver](https://github.com/user-attachments/assets/3d6fb33f-8ddf-4717-b341-d18d7aaa0e38)
