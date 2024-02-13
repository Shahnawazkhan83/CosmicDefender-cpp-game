# C++ Space Invaders Game with Raylib

Welcome to the Space Invaders game implemented in C++ using the Raylib library! This classic arcade game features a spaceship, laser beams, alien spaceships, obstacles, a mystery ship, collision detection, scoring system, high score tracking, and sound effects.

## Features

- Spaceship controlled by arrow keys
- Laser beams shot from the spaceship to destroy aliens
- Alien spaceships with varying movement patterns
- Obstacles to add challenge to the gameplay
- Mystery ship appearing randomly for bonus points
- Collision detection between lasers, aliens, and the spaceship
- Game over when the user ship is hit three times
- Different scores for different types of aliens
- High score tracking and storage in a text file
- Sound effects to enhance the gaming experience

## Dependencies

- Raylib library: [Download and installation instructions](https://www.raylib.com/)

## How to Play

1. Use the arrow keys to control the spaceship.
2. Press the spacebar to shoot lasers at the aliens.
3. Avoid getting hit by the aliens' lasers or colliding with them.
4. Destroy as many aliens as possible to score points.
5. Shoot the mystery ship for bonus points.
6. The game ends when the user ship is hit three times.

## Game Loop

The game loop consists of the following steps:

1. Initialize the game window and resources.
2. Load textures, sound effects, and set up the game environment.
3. Handle user input to control the spaceship and shoot lasers.
4. Update the positions of the spaceship, lasers, aliens, and obstacles.
5. Check for collisions between game elements.
6. Update the score and high score.
7. Display the game elements and user interface.
8. Repeat steps 3-7 until the game ends or the user quits.
9. Save the high score to a text file for future reference.
10. Cleanup and exit the game.

## How to Build and Run

1. Ensure you have the Raylib library installed.
2. Clone this repository to your local machine.
3. Navigate to the project directory.
4. Compile the source files using a C++ compiler, linking with the Raylib library.
5. Run the executable file generated after compilation.

Enjoy playing Space Invaders! If you encounter any issues or have suggestions for improvements, please feel free to contribute to the project. Thank you for playing!
