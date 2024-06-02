# Title: Password Breaker Game
### Problem Statement

### Objective:
Develop a console-based password breaker game where users can guess a randomly selected password from a predefined list of passwords. The game should offer two modes: Easy and Hard, with different rules and feedback mechanisms.

### Game Description:

Welcome Message:

Display a welcome message to the user indicating the start of the game.
Game Mode Selection:

Prompt the user to select a game mode: Easy or Hard.
### Gameplay Mechanics:

### Easy Mode:
The user is allowed unlimited guesses.
After each incorrect guess, the user is informed of the number of correct letters (letters that are present in both the guessed password and the actual password).
The game continues until the user correctly guesses the password or chooses to quit by typing "quit".
Hard Mode:
The user is limited to 5 guesses.
After each incorrect guess, the user is informed of the number of correct letters and the number of remaining attempts.
If the user exhausts all 5 guesses without guessing the password correctly, the game ends and reveals the password.
Quit Option:

At any point during guessing, the user can type "quit" to end the current game. The correct password and the number of guesses used will be displayed.
Replay Option:

After each game (regardless of win or loss), the user is prompted with the option to play again.
If the user chooses "yes", a new game starts with a new randomly selected password.
If the user chooses "no", the game ends.
Functional Requirements:

The game should randomly select a password from the predefined list at the start of each game.
The game should accept user input for guesses and mode selection.
The game should provide appropriate feedback based on the mode (number of correct letters and remaining attempts).
The game should handle case-insensitive inputs.
The game should correctly handle the quit and replay options.
Non-Functional Requirements:

The game should be user-friendly with clear prompts and messages.
The game should handle invalid inputs gracefully (e.g., inputs other than "easy", "hard", "yes", "no").
### Sample Password List:

passwords = ['about', 'after', 'again', 'below', 'could',             'every', 'first', 'found', 'great', 'house', 'large', 'learn',             'never', 'other', 'place', 'plant', 'point', 'right', 'small',             'sound', 'spell', 'still', 'study', 'their', 'there', 'these',             'thing', 'think', 'three', 'water', 'where', 'which', 'world',             'would', 'write']
### Implementation:
The game should be implemented in Python, leveraging built-in libraries for random password selection and user input handling. The code should be structured to ensure readability and maintainability.

By completing this project, users will have a fun and interactive way to test their guessing skills and improve their problem-solving abilities.
