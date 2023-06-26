# CPT113
## Description of the game 

Hangman: Countries Edition is a challenging text-based guessing game where players need to correctly identify the name of a country. The game begins with a random country's name hidden by a series of underscores, representing the letters in the word. Players must guess one letter at a time, and if the letter is in the country's name, it is revealed in its correct position(s). However, incorrect guesses result in strikes. Players have a limited number of attempts to guess the country before the hangman is fully revealed, leading to a loss. Hints are available but come with penalties, so players must strategize to achieve the highest score by guessing the country with the fewest incorrect attempts and hints. It's a fun and engaging way to test your knowledge of countries while challenging yourself to win the game!


## Features of the game 

Random word selection: The game randomly selects a word from a predefined list of countries.

1) Hidden word representation: The unknown word is initially displayed with asterisks (*) representing each letter.
2) User input: The player can input a single letter as a guess.
3) Letter matching: The game checks if the guessed letter matches any letters in the chosen word. If there is a match, the corresponding asterisks in the unknown word are replaced with the correct letter.
4) Wrong guesses tracking: The game keeps track of the number of wrong guesses made by the player. The player has a maximum number of allowed wrong guesses.
5) Feedback on correct/incorrect guesses: The game provides feedback to the player on whether their guess is correct or incorrect.
6) Guessed letters tracking: The game keeps track of the letters that the player has already guessed and prevents the player from guessing the same letter multiple times.
7) Win condition: If the player correctly guesses all the letters in the word, they win the game and receive a victory message.
8) Lose condition: If the player exhausts the maximum number of wrong guesses without correctly guessing the word, they lose the game and receive a defeat message. The correct word is also displayed.
9) User interface: The game provides a simple command-line interface where the player can interact by entering letters as guesses.

## How to play the game 

To play the Hangman game, you will be presented with a hidden word represented by asterisks. Your task is to guess the letters in the word by inputting a single letter at a time. If your guess is correct, the corresponding asterisks will be replaced with the letter in the correct positions. However, if your guess is wrong, the game will keep track of the number of wrong guesses. You have a limited number of attempts to guess the word. Be careful not to guess the same letter twice. If you successfully guess all the letters in the word before running out of attempts, you win the game. But if you exceed the maximum number of wrong guesses without guessing the word correctly, you lose.


## Object oriented concept & implementation of linked lists/stacks/queues in the game 

