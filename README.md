Number Guessing Game

Project Overview

The Number Guessing Game is a Python console-based application. In this game, the computer randomly selects a number between 1 and 100. The player has 7 attempts to guess the correct number. After each incorrect guess, the program displays a hint indicating whether the guess is too high or too low. If the player guesses the correct number within the given attempts, a success message is displayed. Otherwise, the game ends and the correct number is revealed. The player can also choose to play the game again.

Features

- Randomly generates a number between 1 and 100.
- Gives the player 7 attempts to guess the number.
- Displays "Too High" or "Too Low" after each incorrect guess.
- Shows the remaining attempts.
- Displays a success message when the correct number is guessed.
- Reveals the correct number if all attempts are used.
- Handles invalid input using exception handling.
- Allows the player to play multiple rounds.

Technologies Used

- Python 3
- Random Module
- Google Colab

Logic Used

- Uses random.randint() to generate a random number.
- Uses a while loop to restart the game if the player chooses to play again.
- Uses a for loop to limit the player to 7 attempts.
- Uses if-elif-else statements to compare the guessed number with the secret number.
- Uses try-except to handle invalid input without crashing the program.
- Uses break to end the game immediately when the correct number is guessed.
- Uses the else block of the for loop to display the Game Over message when all attempts are completed.

How to Run the Program

1. Open Google Colab.
2. Create a new notebook.
3. Copy and paste the Python code into a code cell.
4. Click the Run button or press shift + enter
5. Enter your guesses when prompted.
6. After the game ends, choose whether to play again or not.

Sample Output

Welcome to the Number Guessing Game!

I have selected a number between 1 and 100.
You have 7 attempts.

Attempt 1
Enter your guess: 50
Too High!
Remaining Attempts: 6

Attempt 2
Enter your guess: 25
Too Low!
Remaining Attempts: 5

Attempt 3
Enter your guess: 37
Correct!
You guessed the number in 3 attempts.

Do you want to play again? (yes/no): no

Thank you for playing!


Concepts Used

- Variables
- Input and Output
- Random Module
- While Loop
- For Loop
- If-Elif-Else
- Try-Except
- Break Statement
- Continue Statement

Author

Name: Dheeraj Thummapala
B.Tech - Computer Science Engineering
SRM INSTITUTE OF SCIENCE AND TECHNOLOGY RAMAPURAM

Internship Project-1
Think Champ Pvt. Ltd.
