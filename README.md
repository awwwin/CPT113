# Hangman Game
## Description of the game 

The objective of Hangman: Countries Edition is to accurately guess the name of a country in a text-based format, presenting a challenging gameplay experience. The objective of the game is to guess the name of a randomly selected country, which is initially concealed by a sequence of underscores that correspond to the letters in the word. The process of guessing one letter at a time and revealing it in the correct position(s) if it is present in the country's name is a crucial aspect of the game. Incorrect guesses lead to strikes. The game of hangman involves a finite number of guesses for players to correctly identify the country being represented, with failure to do so resulting in the gradual revelation of the hangman and ultimate defeat. In this game, players must use strategic thinking to attain the maximum score by accurately guessing the country with the least number of incorrect attempts and hints, which come with associated penalties. The game provides an enjoyable and captivating means of assessing one's understanding of countries, while simultaneously encouraging the player to strive for victory.


## Features of the game 

Random word selection: The game chooses a word at random from a prepared list of countries.

1) Hidden word representation: The unknown word is originally presented with asterisks (*) signifying each letter.
2) User input: The player may enter a single letter as a guess.
3) Letter matching: The game checks to see if the guessed letter matches any letters in the chosen word. If there is a match, the matching asterisks in the unknown word are substituted with the proper letter.
4) Wrong guesses tracking: The game maintains track of the amount of incorrect guesses made by the player. The player is only allowed a certain amount of incorrect predictions.
5) Feedback on correct/incorrect guesses: The game informs the player whether their guess was correct or incorrect.
6) Tracking of previously guessed letters: The game maintains track of the letters that the player has already guessed and prevents the player from guessing the same letter several times.
7) Win condition: If the player correctly guesses all of the letters in the word, they win the game and receive a victory message.
8) Lose condition: If a player exhausts the maximum number of incorrect guesses without correctly guessing the word, they lose the game and receive a defeat message. The proper term is also displayed.
9) User interface: The game includes a simple command-line interface via which the user can interact by entering letters as guesses.


## How to play the game 

In order to play the Hangman game, you will be presented with a word that is hidden and represented by asterisks. Your objective is to guess the letters in the word by entering one letter at a time. When you make a correct guess, the asterisks will be replaced with the corresponding letter in the correct positions. In case your guess is incorrect, the game will record the number of incorrect guesses. You are allowed a limited amount of attempts to guess the word. Please ensure that you do not make the mistake of guessing the same letter more than once. To win the game, you need to guess all the letters in the word correctly before you run out of attempts. If you make more incorrect guesses than the maximum allowed limit without correctly guessing the word, you will lose the game.


## Object oriented concept & implementation of linked lists/stacks/queues in the game

* The Hangman game code incorporates several object-oriented concepts. It uses classes to encapsulate related data and functionality. The Stack class represents a stack data structure and provides operations like push, pop, peek, and isEmpty. The HangmanGame class serves as the main game controller, encapsulating the game logic and managing the game state. It utilizes class members to store data such as the unknown word, guessed letters, and the number of wrong guesses. Methods within the classes are used for specific tasks such as letter matching and initializing the unknown word. Object-oriented concepts such as encapsulation, abstraction, and modularity are employed to organize the code and make it more maintainable and reusable (KENA CHECK BALIK)

* In the Hangman game code,  a linked list is implemented to store the words for the Hangman game. The linked list is represented by a private nested class called Node, which contains a character array word to store the word and a pointer next to the next node in the list. The HangmanGame class includes a pointer wordList to the head of the linked list. The addWord() function is used to add words to the linked list by creating a new node and updating the appropriate pointers. In the destructor ~HangmanGame(), the linked list is cleaned up by iterating through the list and deleting each node. The linked list allows efficient storage and retrieval of the words for the Hangman game, enabling random selection of a word during gameplay. ( KENA BACA BALIK) 

