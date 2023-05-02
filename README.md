# Guess The Number Game

This is a simple number guessing game where the player needs to guess a randomly generated number within a range. The game provides hints to the player about whether their guess is higher or lower than the actual number.

## How to Play

1. The computer will generate a random number within a given range (default is 1 to 20).
2. The player needs to guess the number by entering an integer value.
3. If the guessed number is higher than the actual number, the game will display a message asking the player to try a smaller number.
4. If the guessed number is lower than the actual number, the game will display a message asking the player to try a greater number.
5. The player wins the game if they correctly guess the number.
6. The game ends when the player correctly guesses the number or chooses to quit.

## Getting Started

To run this game on your local machine, follow these steps:

1. Clone this repository to your local machine.
2. Open the terminal and navigate to the directory where you cloned the repository.
3. Run the following command to start the game:

   ```
   python guess_the_number.py
   ```

4. Follow the on-screen instructions to play the game.

## Customization

You can customize the range of the randomly generated number by changing the values in the `random.randint()` function call in the code.

```python
import random

# Change the values below to customize the range of the random number.
lower_range = 1
upper_range = 20

r = random.randint(lower_range, upper_range)
```

## Code Analysis

The code generates a random integer within the range of 1 to 20 using the `random.randint()` function. It then enters a while loop that runs until the player correctly guesses the number. Within the loop, the player is prompted to enter an integer value. If the value entered by the player is less than the random number, a message is displayed asking the player to try a greater number. If the value entered by the player is greater than the random number, a message is displayed asking the player to try a smaller number. If the player enters the correct number, a congratulatory message is displayed and the loop is exited.
