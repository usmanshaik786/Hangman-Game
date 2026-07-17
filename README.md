# CodeAlpha - Hangman Game 

A simple text-based **Hangman Game** developed in **Python**. The player tries to guess a randomly selected word by entering one letter at a time. The game allows a maximum of **6 incorrect guesses** before the player loses.

## Features

* Randomly selects a word from a predefined list of 5 words.
* Displays the word using underscores for unguessed letters.
* Accepts one-letter input from the player.
* Prevents duplicate letter guesses.
* Allows up to 6 incorrect guesses.
* Displays a winning message when the word is guessed.
* Reveals the correct word if the player loses.
* Console-based application (no graphics or audio).

## Technologies Used

* Python 3
* VS Code
* Git & GitHub

## Project Structure

```
Hangman-Game/
│── hangman.py
└── README.md
```

## How to Run

1. Clone the repository:

```bash
git clone https://github.com/usmanshaik786/Hangman-Game.git
```

2. Navigate to the project folder:

```bash
cd Hangman-Game
```

3. Run the program:

```bash
python hangman.py
```

If your system uses Python 3, run:

```bash
python3 hangman.py
```

## Game Rules

1. The game randomly selects one word from a predefined list.
2. Guess one letter at a time.
3. Correct guesses reveal the letter's position(s) in the word.
4. Incorrect guesses reduce the remaining attempts.
5. You have a maximum of **6 incorrect guesses**.
6. Guess the complete word before your attempts run out to win.

## Example

```
===================================
      WELCOME TO HANGMAN
===================================

Word: _ _ _ _ _ _
Incorrect guesses left: 6

Enter a letter: p
Correct guess!

Word: p _ _ _ _ _
```

## Future Improvements

* Difficulty levels (Easy, Medium, Hard)
* Larger word database
* Hint system
* Score tracking
* Multiple rounds
* ASCII Hangman graphics
* Categories (Animals, Fruits, Countries, etc.)

## Author

**Usman Shaik**

GitHub: https://github.com/usmanshaik786

## License

This project is open source and available for learning and educational purposes.

