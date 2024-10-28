# Guess-My-Number

A simple web-based number guessing game where players try to guess a randomly generated number between 1 and 20. Built with HTML, CSS, and JavaScript.

## How to Play
Enter a number between 1 and 20 in the input field and click the "Check!" button.

The game will respond with hints, letting you know if your guess is too high, too low, or correct.

If you guess the correct number, the background color changes, and your score is checked against the high score.

Each incorrect guess decreases your score by 1. If your score reaches zero, you lose.

To start a new game, click the "Again!" button, which resets your score and generates a new random number.

## Code Breakdown

** secretNumber: Random number between 1 and 20 generated at the start and after each game reset.
** score: Initial score set to 20, decreases with each incorrect guess.
** highScore: Tracks the highest score achieved during the session.
displayMessage function: Updates the message displayed on the page based on the game's current state.

## Event Listeners

** Check Button (.check):

Checks if the player's guess matches the secret number.
Adjusts the score and provides feedback (too high, too low, correct).
Updates the high score if the player's score exceeds the current high score.

** Again Button (.again):

Resets the game by re-initializing the score, generating a new secret number, and restoring the original styling and layout.

## Features

Responsive feedback for correct/incorrect guesses. 

Dynamic high score tracking within a single session.

Visual enhancements when the correct number is guessed (background color and number width changes).
 
