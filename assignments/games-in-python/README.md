# 📘 Assignment: Hangman Game Challenge

## 🎯 Objective

Create the classic Hangman word-guessing game using Python strings, loops, user input, and random selection. By completing this assignment, you'll practice fundamental programming concepts including string manipulation, loops, conditionals, and working with randomized data.

## 📝 Tasks

### 🛠️ Game Setup and Word Selection

#### Description
Initialize the game by setting up a word list and randomly selecting a word for the player to guess. Create the data structures needed to track game progress.

#### Requirements
Completed program should:

- Maintain a predefined list of words to choose from
- Randomly select a word for each game session
- Initialize tracking for guessed letters, correct guesses, and incorrect guesses
- Display initial game state with underscores for unknown letters (e.g., `_ _ _ _`)

### 🛠️ Game Loop and User Input

#### Description
Implement the main game loop that accepts letter guesses from the player and validates input while updating the game state.

#### Requirements
Completed program should:

- Accept single letter guesses from the user
- Validate that input is a single letter and hasn't been guessed before
- Update the display to show correctly guessed letters
- Track the number of incorrect guesses remaining
- Show feedback for each guess (correct or incorrect)

### 🛠️ Win/Lose Conditions and Game End

#### Description
Implement logic to detect when the player wins or loses and display appropriate messages.

#### Requirements
Completed program should:

- Detect when the player has guessed all letters (win condition)
- Detect when the player has exhausted all attempts (lose condition)
- Display the hidden word when the game ends
- Show a win or lose message with appropriate feedback
- Optionally offer to play again
