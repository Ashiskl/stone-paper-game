# stone-paper-game
import random
items=["rocks","paper","scissor"]
user_choice=input("enter your move= rocks,paper,scissor=")
comp_choice=random.choice(items)
print(f"user choice={user_choice},computer choice={comp_choice}")
while True:
    
    if user_choice==comp_choice:
        print("both chosses same =Match tie")
    elif user_choice=="rocks":
        if comp_choice=="paper":
            print("computer win")
        elif comp_choice=="scissor":
            print(" you win  ")
    elif user_choice=="paper":
        if comp_choice=="rocks":
            print(" you won")
        elif comp_choice=="scissor":
            print(" computer won")
    elif user_choice=="scissor":
        if comp_choice=="paper":
            print("you won..")
        elif comp_choice=="rocks":
            print("computer won")
    break

    
   
                    
