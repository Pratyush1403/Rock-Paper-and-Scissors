**Rock Paper Scissors Game**

## Project Overview
This project is a simple implementation of the classic Rock, Paper, Scissors game using HTML, JavaScript, and CSS. The game allows a player to choose between three moves (Rock, Paper, or Scissors) and then competes against the computer's randomly selected move. The project also includes a scorekeeping feature that keeps track of wins, losses, and ties.

## Project Structure
The project consists of three main components: the HTML structure, JavaScript logic, and CSS styling.

### HTML (index.html)
- `<!DOCTYPE html>`: Declares the document type as HTML5.
- `<html lang="en">`: Specifies the document language as English.
- `<head>`: Contains metadata and links to external resources.
  - `<meta charset="UTF-8">`: Defines the character encoding as UTF-8.
  - `<meta name="viewport" content="width=device-width, initial-scale=1.0">`: Configures the viewport for responsive design.
  - `<title>Rock Paper Scissors</title>`: Sets the title of the webpage.
  - `<link rel="stylesheet" href="rockpaperscissor.css">`: Links the CSS stylesheet.
- `<body>`: Contains the game elements.
  - `<h1>`: Displays the game title.
  - Three buttons with images for Rock, Paper, and Scissors moves.
  - `<p>` elements for displaying game results, chosen moves, and the score.
  - A button to reset the score.
  - `<script src="rockpaperscissor.js"></script>`: Links the JavaScript file for game logic.

### JavaScript (rockpaperscissor.js)
- Initializes and maintains the game's state, including the player's score.
- Defines functions for making moves, updating the score, resetting the score, and picking the computer's move.
- Uses `localStorage` to persist the score even if the webpage is refreshed or closed.

### CSS (rockpaperscissor.css)
- Styles the appearance of the game elements, including buttons, background color, and text color.
- Defines classes for styling and layout.

## How to Play
1. Open the `index.html` file in a web browser.
2. Click one of the three buttons (Rock, Paper, or Scissors) to make your move.
3. The computer will randomly select its move.
4. The game will display the result (Win, Lose, or Tie) and update the score.
5. You can reset the score at any time by clicking the "Reset Score" button.

Enjoy playing Rock Paper Scissors!

## Notes
- The game uses random computer moves, making each round unpredictable.
- The score is stored locally using `localStorage`, so you can continue your game even after closing the browser.

Have fun playing the Rock Paper Scissors game!
