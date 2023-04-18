# Rock_Paper_Scissors
The game begins by defining the three possible options: rock, paper, and scissors. The program then enters a loop that will continue until the user types "q" to quit the game.
Inside the loop, the program prompts the user to input their choice of rock, paper, or scissors (in lowercase), and checks whether the input is valid. If the input is not one of the valid options, the program skips to the next iteration of the loop.

If the input is valid, the program generates a random number between 0 and 2 using the random.randint() function, and uses that number to select the computer's choice from the options list. The program then compares the user's choice with the computer's choice to determine the winner of the round.
If the user wins the round, the program increments the user_wins variable by 1. If the computer wins, the program increments the computer_wins variable by 1.
Once the user types "q" to quit the game, the program prints out the number of times the user and the computer won, and says goodbye.
Overall, this implementation of the Rock-Paper-Scissors game is a simple and effective way to play the game in Python.
