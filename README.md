# Guess The Number

## Description

This is a simple number guessing game where the user tries to guess a randomly generated number between 1 and 100. The player has 10 attempts to guess the correct number, and after each attempt, they receive feedback on whether their guess was too high, too low, or correct.

## Features

- Generates a random number between 1 and 100.
- Allows the user up to 10 attempts to guess the correct number.
- Displays previous guesses and remaining attempts.
- Provides hints if the guess is too high or too low.
- Displays a message when the game is won or lost.
- Offers a "Play Again" button to restart the game.

## Technologies Used

- HTML
- CSS
- JavaScript

## File Breakdown

### HTML (`index.html`)

- Creates the game layout with a heading, instructions, input field, submit button, and result display section.
- Links the external CSS (`style.css`) and JavaScript (`script.js`) files.

### CSS (`style.css`)

- Styles the game container, text, input fields, and buttons.
- Implements hover effects and animations for buttons.
- Uses a dark-themed background with a contrasting game area.

### JavaScript (`script.js`)

- Generates a random number between 1 and 100.
- Listens for user input and validates it.
- Provides feedback on guesses (too high, too low, correct).
- Tracks the number of remaining attempts.
- Ends the game when the user wins or exhausts their attempts.
- Allows the user to restart the game without refreshing the page.

## How to Play

1. Enter a number between 1 and 100 in the input field.
2. Click the "Submit Guess" button.
3. The game will indicate whether your guess is too high, too low, or correct.
4. You have 10 attempts to guess the correct number.
5. If you guess correctly, you win! Otherwise, the game will end when attempts reach 0.
6. Click the "Play Again" button to restart the game.

## Screenshot

![Screenshot](https://github.com/afaisal997/Guess-The-Number/blob/main/Screenshot.png)


## Live Demo

afaisal997.github.io/Guess-The-Number/

## Author

Developed by Abdullah Faisal
