# 📘 Assignment: Games in Python

## 🎯 Objective

Build a classic Hangman game in Python. You will practice using strings, loops, conditionals, and random selection to create an interactive word-guessing game.

## 📝 Tasks

### 🛠️	Hangman Game Logic

#### Description
Write a Python program that lets a player guess letters to uncover a hidden word. The player has a limited number of incorrect guesses before the game ends.

#### Requirements
Completed program should:

- Randomly select a word from a predefined list
- Display the word as blanks (e.g., `_ _ _ _`)
- Allow the player to guess one letter at a time
- Show the current progress after each guess
- Track and display the number of incorrect guesses remaining
- End the game with a win message if the word is guessed, or a lose message if attempts run out

**Example:**
```plaintext
Word: _ _ _ _ _
Guess a letter: a
Incorrect! Tries left: 5
Word: _ a _ _ _
Guess a letter: t
Correct!
...
```

### 🛠️	Replay and User Experience

#### Description
Enhance your Hangman game to allow players to play multiple rounds and improve the user interface.

#### Requirements
Completed program should:

- Ask the player if they want to play again after each game
- Reset the game state for each new round
- Provide clear instructions and feedback for each guess
- Handle invalid input gracefully (e.g., repeated or non-letter guesses)