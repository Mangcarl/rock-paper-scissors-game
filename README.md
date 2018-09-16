# rock-paper-scissors-game
it is just a code that i get from an exercise and i want to make it better
# if possible, make changes and find ways to make it shorter if possible
player1 = input("player 1\nrock, paper, or scissors?\nPlease type what you want:")
player2 = input("player 2\nrock, paper, or scissors?\nPlease type what you want:")
true = True
while true:
    if player1 == "rock" and player2 == "rock":
        print("its a tie")
    elif player1 == "scissors" and player2 == "scissors":
        print("its a tie")
    elif player1 == "paper" and player2 == "paper":
        print("its a tie")
    elif player1 == "rock" and player2 == "scissors":
        print("player 1 you win")
    elif player1 == "scissors"and player2 == "paper":
        print("player 1 you win")
    elif player1 == "paper" and player2 == "rock":
        print("player 1 you win")
    elif player2 == "rock" and player1 == "scissors":
        print("player 2 you win")
    elif player2 == "scissors" and player1 == "paper":
        print("player 2 you win")
    elif player2 == "paper" and player1 == "rock":
        print("player 2 you win")
    while true:
        ask = input("do you want to continue?: ")
        if ask == "no":
            true = False
            break
        else:
            continue
