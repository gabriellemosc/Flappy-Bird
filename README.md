# Flappy Bird - Python  🎮

## Description
This is a Python implementation of the classic Flappy Bird game using the **Pygame** library. The objective is to control the bird, making it fly between pipes without colliding with them.

## Features
- Smooth bird animation with different wing positions.
- Randomly generated pipes for an endless challenge.
- Collision detection system.
- Score tracking.
- Moving ground to simulate a scrolling effect.

## 🚀 Technologies Used
- **Python 3.x**
- **Pygame**

## Installation

### Clone the Repository...

```
git clone https://github.com/gabriellemosc/Flappy-Bird/
```

### Install Pygame 🛠️
Run the following command to install the required library:
```bash
pip install pygame
```

## Running the Game 🎯
1. Navigate to the game directory in the terminal.
2. Run the game with:
```bash
python flappybird.py
```

## Game Controls 🕹️
- **Spacebar**: Make the bird jump.
- **ESC / Close Button**: Exit the game.

## Game Files Structure
```
Flappy_Bird/
│── imgs/               # Folder containing game images
│   ├── pipe.png        # Pipe image
│   ├── base.png        # Ground image
│   ├── bg.png          # Background image
│   ├── bird1.png       # Bird animation frame 1
│   ├── bird2.png       # Bird animation frame 2
│   ├── bird3.png       # Bird animation frame 3
│── flappybird.py       # Main game script
│── README.md           # Documentation file
```

## Known Issues & Fixes 🔧
### Issue: FileNotFoundError
If you get an error related to missing images:
1. Ensure the `imgs/` folder exists inside the same directory as `flappybird.py`.
2. Verify that the file names match exactly as used in the code.
3. Check if your working directory is correct by adding `print(os.getcwd())` in the script.



### Issue: Game running too fast or too slow  ⚠️
Modify the frame rate in `pygame.time.Clock().tick(30)` inside the `main()` function to adjust the game speed.



## License ✔️
This project is open-source and free to use for educational and personal purposes.

## Credits
Developed by **<a href="https://github.com/gabriellemosc">Gabriel Lemos</a>**.


