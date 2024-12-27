# Tic-Tac-Toe Game

This repository contains a simple implementation of the classic Tic-Tac-Toe game using HTML, CSS, and JavaScript. The game allows two players to play against each other on the same device.

## Features

- Interactive 3x3 grid for gameplay.
- Alternating turns for Player X and Player O.
- Automatic detection of winning combinations.
- Displays a message for the winner or if the game ends in a draw.
- Reset and New Game functionality to start over easily.

## Project Structure

```
project-directory
|-- index.html       # Main HTML file
|-- style.css        # Styling for the game
|-- app.js           # Game logic
```

## How to Use

1. Clone or download this repository.
2. Open the `index.html` file in any modern web browser.
3. Start playing by clicking on the boxes to take turns as Player X and Player O.

### Controls

- **Click on any empty box**: Place your marker (X or O).
- **Reset Game button**: Clears the board and starts a new game.
- **New Game button**: Resets the game and hides the winner/draw message.

## Gameplay Rules

1. The game is played on a 3x3 grid.
2. Players take turns to place their marker (X or O) in an empty box.
3. The first player to align three markers in a row, column, or diagonal wins the game.
4. If all boxes are filled and no player achieves a winning combination, the game ends in a draw.

## Implementation Details

### HTML

- A basic structure with a 3x3 grid of buttons for the game board.
- Separate buttons for resetting the game and starting a new one.

### CSS

- Responsive and visually appealing design with centered alignment.
- Styled buttons and winner/draw messages for clarity.

### JavaScript

- Handles the game logic, including turn alternation, win/draw detection, and button enabling/disabling.
- Predefined winning patterns to check for victory conditions.

## Screenshots

1. **Game Board**
<img src="https://github.com/user-attachments/assets/135b3ed4-668d-4c37-9188-ef7bb7252638" width=300 height=350>

3. **Winner Message**
<img src="https://github.com/user-attachments/assets/cda22778-00e6-47a2-ad2f-137e3a5b9361" width=300 height=200>

4. **Game Draw Message**
<img src="https://github.com/user-attachments/assets/aad099d3-3ece-445f-9f57-d1d7cc06d3db" width=300 height=200>

## How to Contribute

1. Fork this repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them.
4. Push your changes to your fork and submit a pull request.

## License

This project is licensed under the MIT License. Feel free to use, modify, and distribute this code as per the license terms.

---

Enjoy the game! If you encounter any issues or have suggestions for improvements, feel free to open an issue or contribute to the repository.

