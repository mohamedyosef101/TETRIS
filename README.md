# Tetris Game in Python
Tetris involves complex logic like collision detection, rotations, scoring, and a great example for me to practice OOP principles. Also, I may use it as an environment to test some RL algorithms (e.g. Deep Q-Learning). 

## Features
* Multiple Tetris shapes (I, J, L, O, S, T, Z)
* Game board manipulation
* Shape rotation and movement
* Collision detection
* Scorekeeping
* Game loop

## Requirements
* Python 3.x

## Installation
* Clone this repository: `git clone https://github.com/mohamedyosef101/tetris.git`
* Navigate to the project directory: `cd tetris`
* Install dependencies: `pip install -r requirements.txt`

## Playing the Game
1. Run the game: `python main.py`
2. Use arrow key to move the falling shape.
3. Press the up arrow key to rotate the shape.
4. Lines are cleared when they are completely filled. 
5. The game ends when a shape collides with the top of the board.

## Getting Started with the Code
The project is structured with the following key classes: 
* `TetrisGame`: Encapsulates the overall game logic and state.
* `Board`: Represents the game board grid.
* `Shape`: Defines the different Tetris shapes and their behaviors.
* `Tile`: Represents an individual square within a shape.
* `Ground`: Represents the bottom boundary of the game board.

## Contributing

We welcome contributions to this project! Please see the `CONTRIBUTING.md` file  for guidelines on how to submit pull requests.

## License 
This project is licensed under the MIT License (see `LICENSE.md` for details).

## Credits
* Carmen Santos. (2024). [Python TETRIS Game OOP](https://youtu.be/u-fuaFaHxQM). YouTube.