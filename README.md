# Number Guessing Game

## Overview
This Java program implements a simple number guessing game where the player needs to guess a randomly generated number between 0 and 99. The player has a limited number of attempts to guess the correct number.

## How to Play
1. The program generates a random number between 0 and 99.
2. The player is prompted to enter their guess.
3. If the guess is correct, the player wins.
4. If the guess is incorrect, the program provides feedback on whether the correct number is greater or smaller than the guessed number.
5. The player has a total of 5 attempts to guess the correct number.
6. If the player exceeds the maximum number of attempts or makes invalid inputs, the game ends.

## Features
- Randomly generated number between 0 and 99.
- Input validation for guesses (must be between 0 and 99).
- Limited attempts for the player (5 attempts).
- Feedback on whether the correct number is greater or smaller than the guessed number.
- End-of-game summary, displaying the correct number and the player's guesses in case of failure.

## How to Run
1. Clone the repository to your local machine:
    ```bash
    git clone https://github.com/snilsumelis/Number_Guessing_Game
    ```
2. Navigate to the project directory:
    ```bash
    cd your-repository
    ```
3. Compile and run the `Main` class in the `src` directory.

## Example Output
```bash
Tahmininizi giriniz : 50
50 sayısı gizli sayıdan büyüktür
kalan hakkınız : 4
Tahmininizi giriniz : 25
25 sayısı gizli sayıdan küçüktür
kalan hakkınız : 3
Tahmininizi giriniz : 37
37 sayısı gizli sayıdan küçüktür
kalan hakkınız : 2
Tahmininizi giriniz : 42
42 sayısı gizli sayıdan büyüktür
kalan hakkınız : 1
Tahmininizi giriniz : 40
Tebrikler doğru tahmin ettiniz. Tahmin ettiğiniz sayı : 40
