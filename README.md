# ScrabbleWordScorer
 
This is a simple C program that calculates the scores for words entered by two players in a Scrabble game. The program uses a pre-defined set of points for each letter of the alphabet to compute the score for each word.

### How to Use
Clone the repository to your local machine.
Compile the C program using a C compiler (e.g., gcc scrabble.c -o scrabble).
Run the program (./scrabble).
Enter words for both Player 1 and Player 2 when prompted.
### Features
Scoring Words: The program scores words based on the points assigned to each letter of the alphabet in the game of Scrabble.

Case Insensitivity: The program is case-insensitive, considering both uppercase and lowercase letters when calculating scores.

Player Comparison: After entering words for both players, the program compares the scores and declares the winner or identifies a tie.

### Weak Points
Input Validation: The program assumes valid input and does not thoroughly validate input data. It relies on the user to provide well-formed words without unusual edge cases.

Limited to English Alphabet: The scoring system is designed for the English alphabet and may not work correctly for words containing characters outside the A-Z range.

No Blank Tile Handling: The program does not handle blank tiles, which are a part of the Scrabble game. It assumes that each letter contributes to the score directly.

### Contributions
Contributions are welcome! Feel free to fork this repository, make improvements, and submit a pull request.

### License
This project is licensed under the MIT License - see the LICENSE file for details.