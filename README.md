# Pacman-Game
# Pacman Game

This repository contains a simple Pacman game implemented using Python and the Pygame library. The goal of the game is to move Pacman around the screen, avoid walls, and collect all the food items.

## Features

- Pacman can move up, down, left, and right using the arrow keys.
- Basic wall collision detection to prevent Pacman from moving through walls.
- Food items are scattered around the screen for Pacman to collect.

## Requirements

- Python 3.x
- Pygame library

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Rohithds/pacman-game.git
   cd pacman-game
   ```

2. Install the Pygame library:
   ```bash
   pip install pygame
   ```

## How to Play

1. Run the game script:
   ```bash
   python pacman_game.py
   ```

2. Use the arrow keys to move Pacman around the screen.

3. Collect all the food items to win the game.

4. Avoid colliding with walls, as Pacman cannot pass through them.

## Customization

- You can add more walls by modifying the `walls` list in the code. Each wall is defined as a `pygame.Rect` object.
- Additional food items can be added to the `food_positions` list.

## Acknowledgments

- This project uses the [Pygame](https://www.pygame.org/) library.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

