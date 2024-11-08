'''Number Guessing Game
A Python game where the user guesses a randomly generated number between 1 and 100. The program provides feedback on whether the guess is too low or too high until the correct number is guessed.

Features:
Tracks attempts.
Provides feedback on each guess.
Congratulates the user when the correct number is guessed.
Example Output:
Guess Number (Between 1 and 100): 50
Too High!
Guess Number (Between 1 and 100): 35
Too Low!
Guess Number (Between 1 and 100): 42
Congratulations! Your Guessed The Correct Number in 3 attempts.'''

# Number_Guessing_Game_Project

import random
number_guess= random.randint(1,100)
attempt=0
while True:
    guess= int(input("Guess Number (Between 1 and 100):"))
    attempt+=1
    if guess < number_guess:
        print("Too Low!")
    elif guess>number_guess:
        print("Too High!")
    else:
        print(f"Congratulations! Your Guessed The Corecct Number in {attempt} attempts.")
        break
