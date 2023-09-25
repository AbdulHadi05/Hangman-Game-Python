# Hangman-Game-Python
Hangman is a classic word-guessing game where one player thinks of a word, and the other player tries to guess it one letter at a time. In this project, we have implemented fundamental programming logic to build a simple Hangman game in Python. The player's objective is to guess the correct word within a limited number of attempts to save the "Hangman".

# Game Mechanics:

The game randomly selects a codeword from a predefined list.
The player is given a limited number of attempts (lives) to guess the word.
The player inputs a letter as their guess.
If the input is not a single alphabetical character, the game prompts the player to enter a valid guess.
If the guessed letter is part of the codeword, it is revealed in its correct position(s).
If the guessed letter is not part of the codeword and hasn't been guessed before, the Hangman's drawing progresses.
The player can continue guessing until they either:
Successfully guess the entire word and save the Hangman.
Run out of lives and the Hangman is hanged.

**End of Game:**

If the player successfully guesses the entire word, they win and see the codeword.
If the player runs out of lives, they lose, and the Hangman is hanged. The correct codeword is revealed.
The game provides an option to play again by typing 'y' or 'Y'.

# Game Components:

**pre_body() Function:**

Initializes the game variables and selects a random word from a predefined list.

**replay() Function:**

Asks the player if they want to play again. If yes, it resets the game variables and starts a new game.

**body() Function:**

Implements the core game logic, including handling player guesses, updating the display, and checking for win or loss conditions.
