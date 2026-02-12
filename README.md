



https://pig-game-javascrypt.netlify.app/



# Pig Game

Welcome to the **Pig Game**! This is a simple, two-player game where players take turns rolling a dice, trying to be the first to reach 20 points. The game is built using HTML, CSS, and JavaScript.

## Game Rules

## Game Rules

1. **Objective**: The first player to reach 20 points wins the game. (This can be changed.)
2. **Gameplay**:
   - Players take turns to roll a dice.
   - The number rolled is added to the current player's score unless a 1 is rolled.
   - If a player rolls a 1, their turn ends and the current score for that turn is reset to 0.
   - A player can choose to "Hold", which adds their current score to their total score and ends their turn.
3. **Winning the Game**: The first player to reach or exceed 20 points on their total score wins the game.

## Files Included

- `index.html`: The HTML file that contains the structure of the game.
- `style.css`: The CSS file that styles the game.
- `script.js`: The JavaScript file that contains the game logic.

## Installation

To play the Pig Game, follow these steps:

1. **Clone the Repository**:
    
2. **Open `index.html`** in your web browser to start playing the game.

## How to Play

1. **Start a New Game**: Click the "🔄 New game" button to start a new game.
2. **Roll the Dice**: Click the "🎲 Roll dice" button to roll the dice. The dice image will update to show the number rolled.
3. **Hold Your Score**: Click the "📥 Hold" button to add your current score to your total score and end your turn.
4. **Switch Turns**: If you roll a 1, your current score for that turn is reset to 0, and it becomes the other player's turn.

## Code Overview

### HTML (`index.html`)

- The HTML file sets up the structure of the game, including the player sections, buttons, and dice image.

### CSS (`style.css`)

- The CSS file styles the game elements, including the layout, fonts, and colors.

### JavaScript (`script.js`)

- The JavaScript file contains the game logic, including:
  - Initializing the game state (`init` function).
  - Switching between players (`switchPlayer` function).
  - Handling the dice roll and hold actions (event listeners for the buttons).

## Future Improvements

- Add sound effects for rolling the dice and winning the game.
- Implement player customization options, such as changing player names and colors.
- Create a more dynamic and interactive user interface.

## Credits

This game was inspired by the classic dice game Pig. The game was developed using the following technologies:
- HTML
- CSS
- JavaScript

Enjoy playing the Pig Game! Have fun and may the best player win!
