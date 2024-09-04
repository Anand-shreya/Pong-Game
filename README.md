# Interactive Pong Game

This is an interactive version of the classic Pong game, where the player can specify any object of their choice as a paddle. The game uses object tracking to detect and track the selected object in real-time using a webcam feed.

## Features
- **Customizable Paddle:** Players can choose their paddle by adjusting HSV values to match the object's color, enabling the game's tracking system to lock onto the object.
- **Object Tracking:** Implemented with OpenCV, the game detects and tracks the chosen object in the webcam feed, dynamically updating the paddle position.
- **Collision Detection:** Robust algorithms are used to accurately register ball-paddle collisions, ensuring a smooth gaming experience.
- **Dynamic Difficulty:** The game's challenge increases as the ball's velocity accelerates by 1.3 times after each successful collision with the paddle.

## Tech Stack
- **Python**
- **OpenCV**
