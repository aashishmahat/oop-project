# Tic-Tac-Toe Game

## Overview

This project is a graphical Tic-Tac-Toe game created using the SFML (Simple and Fast Multimedia Library). The game features a graphical user interface, sound effects, and the ability to enter player names. It allows two players to play Tic-Tac-Toe on a 3x3 board.

## Features

- **Graphical Interface**: A visually appealing game window with a background image and grid lines.
- **Player Names**: Input fields for players to enter their names.
- **Sound Effects**: Audio feedback for placing marks and game results.
- **Game State Management**: Displays win or draw messages and saves the game result to a file.
- **Reset Functionality**: Allows the game to be restarted by pressing the 'R' key.

## Prerequisites

Before running the game, ensure you have the following:

- **SFML Library**: You need to have the SFML library installed. You can download it from [SFML's official website](https://www.sfml-dev.org/).
- **Assets**: Ensure you have the following files in the same directory as the executable:
  - `background.jpg` (Background image for the game window)
  - `x_sound.wav` (Sound effect for placing an 'X')
  - `o_sound.wav` (Sound effect for placing an 'O')
  - `win_sound.wav` (Sound effect for winning the game)
  - `draw_sound.wav` (Sound effect for a draw)
  - `arial.ttf` (Font file for text rendering)

## How to Compile

1. **Install SFML**: Follow the [SFML installation guide](https://www.sfml-dev.org/tutorials/2.5/) for your platform.
2. **Compile the Code**: Use a C++ compiler that supports SFML. For example, with g++, you can use the following command:

   ```bash
   g++ -o TicTacToe main.cpp -lsfml-graphics -lsfml-window -lsfml-system -lsfml-audio
   ## How to Run

After compiling, run the executable:

```bash
./TicTacToe
## Game Controls

- **Click**: Select a cell to place your mark.
- **'R' Key**: Reset the game if it has ended.
- **Enter Player Names**: Enter names for Player 1 and Player 2 when prompted in the input window.

## File Structure

- `main.cpp`: Contains the main game logic and implementation.
- `background.jpg`: Background image for the game window.
- `x_sound.wav`: Sound effect for 'X'.
- `o_sound.wav`: Sound effect for 'O'.
- `win_sound.wav`: Sound effect for a win.
- `draw_sound.wav`: Sound effect for a draw.
- `arial.ttf`: Font file used for displaying text.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contributing

Contributions are welcome! Please fork the repository and submit pull requests for any enhancements or bug fixes.

## Contact

For any questions or feedback, you can reach me at [080bct004@ioepc.edu.np](mailto:080bct004@ioepc.edu.np).

