# Space Shooter

## Technical Setup

### Prerequisites

You need to have Python installed on your system. If you don't have Python installed, you can download it from [here](https://www.python.org/).

Additionally, this game requires the `pygame` library. You can install `pygame` using pip:

```sh
pip install pygame
```

### Installation

1. **Clone the repository:** 
   Navigate to the directory where you want to store the game and run:
   ```sh
   git clone <repository-url>
   ```
   Replace `<repository-url>` with the actual URL of the repository.

2. **Navigate to the game directory:**
   ```sh
   cd space-shooter
   ```

3. **Ensure all assets are in place:**
   Make sure the `Assets_Pygame` directory contains the required images and sounds:
   ```
   Assets_Pygame/
   ├── Grenade+1.mp3
   ├── Gun+Silencer.mp3
   ├── spaceship_yellow.png
   ├── spaceship_red.png
   └── space.png
   ```

4. **Run the game:**
   ```sh
   python space_shooter.py
   ```

## How to Play

### Controls

- **Yellow Ship:**
  - Move Left: `Q`
  - Move Right: `D`
  - Move Up: `Z`
  - Move Down: `S`
  - Shoot: `Left Ctrl`

- **Red Ship:**
  - Move Left: `Left Arrow`
  - Move Right: `Right Arrow`
  - Move Up: `Up Arrow`
  - Move Down: `Down Arrow`
  - Shoot: `Right Ctrl`

### Objective

The goal of the game is to reduce your opponent's health to zero using your spaceship's bullets. Each player starts with 10 health points. The last player standing wins!

### Game Mechanics

1. **Movement:**
   - You can move your spaceship in four directions using the designated keys.

2. **Shooting:**
   - Pressing the designated Ctrl key will shoot a bullet from your spaceship. Each player can have a maximum of 3 bullets on the screen at any time.

3. **Health:**
   - Each time a spaceship is hit by a bullet, the respective player's health decreases by 1.

4. **Winning:**
   - When a player's health reaches zero, the game ends, and a message declaring the winner is displayed on the screen.

### Game Flow

- On launching the game, both spaceships will appear on opposite sides of the screen.
- Use the movement keys to dodge bullets and position yourself strategically.
- Use the shooting keys to fire bullets at your opponent.
- The game continues until one player's health reaches zero.
- A message indicating the winner is displayed.
- The game automatically exits after displaying the winner for a few seconds.

Enjoy playing Space Shooter!