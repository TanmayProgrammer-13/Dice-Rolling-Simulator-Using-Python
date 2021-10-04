import random 

again = True

while again:
    print(random.randint(1,6))
    another_roll = input("Want To Roll The Dice Again? (Y/N): ")
    if another_roll.lower() == "y":
        continue
    else:
        break
