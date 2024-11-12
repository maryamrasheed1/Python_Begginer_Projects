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
