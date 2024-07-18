# Snake Game in Assembly 8086

This is a simple Snake game implemented in Assembly 8086. It's a classic arcade game where the player controls a snake that moves around the screen, eating food and growing longer. The objective is to grow the snake as long as possible without colliding with the boundaries of the game or itself.

![Snake Game 1](https://i.ibb.co/9c7r9cC/image.png)
![Snake Game 2](https://i.ibb.co/1TYtPf5/image.png)

## Features

- Classic Snake gameplay.
- Increasing difficulty as the snake grows longer.
- Score tracking.

## Prerequisites

Before you can run the game, you'll need an environment that supports running Assembly 8086 programs. Here's what you'll need:

- An 8086 emulator, such as DOSBox, to run the game.
- A text editor or assembler to edit and assemble the source code.

## How to Run

1. Clone or download this repository to your local machine.

2. Open your 8086 emulator (e.g., DOSBox).

3. Navigate to the directory where you've saved the game files.

4. Assemble the source code (e.g., using TASM) to create an executable file.

5. Run the game by executing the generated executable.

```bash
nasm main.asm -o main.com -l main.lst
main.com
```

6. Enjoy playing the Snake game! Use the arrow keys to control the snake's movement.

## Controls

- Use the arrow keys (Up, Down, Left, Right) to navigate the snake.
- Try to collect as much food as possible without running into the boundaries or colliding with the snake's own body.

## How to Play

1. Use the arrow keys to move the snake.
2. Your snake will grow longer each time it eats a piece of food.
3. The game gets progressively more challenging as the snake grows longer.
4. The game ends when you collide with the boundaries or yourself.
5. Try to achieve the highest score possible!


## Acknowledgments

- This project was inspired by the classic Snake game.
- Thanks to the Assembly 8086 community for sharing knowledge and resources.

## Author

- Ahmed Abdullah

## Contact

If you have any questions, suggestions, or issues, please feel free to contact the author at [business.ahmadabdullah@gmail.com].

Enjoy the game!

Feel free to modify and expand this README to provide more details about your specific Snake game in Assembly 8086. You can add information about the game's features, the game loop, any customizations, and more.
