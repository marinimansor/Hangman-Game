Hangman Game
This is a simple implementation of the Hangman game in C++. The game allows the player to guess letters in order to complete a hidden word. The player has a limited number of incorrect guesses before losing the game.

How to Play
1. The game selects a random word from a provided word list file named "wordlist.txt". You can download the file from the GitHub link provided: https://github.com/marinimansor/Hangman-Game
2. The player is presented with a blank representation of the word, with underscores representing each letter.
3. The player guesses letters by entering them one at a time.
4. If the guessed letter is present in the word, it is revealed in the correct position(s). If not, a part of the hangman is drawn.
5. The player continues guessing letters until either the word is completely revealed (win) or the hangman is fully drawn (loss).
6. The game ends, and a message is displayed to indicate whether the player won or lost.

Dependencies
The program requires a C++ compiler and the following standard library headers:
iostream
vector
fstream
string
time.h

Usage
1. Clone or download the source code from the GitHub repository: https://github.com/marinimansor/Hangman-Game.
2. Download the word list file "wordlist.txt" from the repository: wordlist.txt.
3. Compile the source code using a C++ compiler. For example, using g++: g++ hangman.cpp -o hangman
4. Run the compiled executable:./hangman
5. Follow the on-screen instructions to play the game.

Customization
-The word list is loaded from the "wordlist.txt" file. You can modify this file to change the available words for guessing. Make sure each word is on a separate line.
-The number of maximum incorrect guesses allowed before losing the game is set to 10. If you want to change this, modify the condition in the do-while loop in the main function.
-The program includes platform-specific commands for clearing the screen (system("cls") for Windows) and pausing the program (system("pause") for Windows). If you're using Linux or macOS, you'll need to replace these commands with the appropriate ones (system("clear") and removing system("pause"), respectively) in the code.

Contact:
umairahazham1702@gmail.com for any inquiries, questions, or feedback related to the project.
  
License
This project is licensed under the MIT License. Feel free to use and modify the code according to your needs.

Acknowledgments
This Hangman game implementation is based on the original code provided by OpenAI as a part of the GPT-3.5 model examples.
