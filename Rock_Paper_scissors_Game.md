# Rock_Paper_Scissors_Game_Project
import random
choices=["rock" , "paper" , "scissors"]
computer_choice= random.choice(choices)

user_choice= input("Enter rock , paper , scissors:").lower()
if user_choice not in choices:
    print("invalid input.")
else:
    print (f"you chose: {user_choice}")
    print (f"computer chose: {computer_choice}")
if user_choice== computer_choice:
    print("Its a tie")
elif(user_choice=="rock" and computer_choice=="scissors") or \
    (user_choice=="scissors"and computer_choice=="paper") or \
    (user_choice=="paper" and computer_choice=="rock") :
    print("You Win")
else:
    print("You Lose")
