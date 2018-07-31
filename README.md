# hello-world
Test00

import random
random_num = random.randint(0, 10)
right = 0
play ="y"
while play =="y":
    while right == 0:
        guess = int(input("Guess a number between 0 and 10 "))
        if guess == random_num:
            print("you got it!")
            right = 1
        else:
            print("wrong")
            right = 0
    play = input("play again? y/n")
    if play == "y":
        right = 0
