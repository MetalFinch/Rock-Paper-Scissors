 Rock Paper Scissors Game

A simple Python console game where you play Rock, Paper, Scissors against the computer.
Perfect for beginners learning about:

Functions

Conditional logic (if, elif, else)

Random number generation

User input and output

🎮How to Play

Run the Python script in your terminal:

python rock_paper_scissors.py


When prompted, type one of the following:

rock
paper
scissors


The computer will randomly choose one option.
You’ll then see who wins!

Game Logic
Player Choice	Computer Choice	Result
rock	scissors	 Rock smashes scissors — You win!
paper	rock	Paper covers rock — You win!
scissors	paper	 Scissors cuts paper — You win!
same choice	same choice It’s a tie!
otherwise You lose.
 How It Works

get_choices()
Prompts the user for input and randomly selects the computer’s move.
Returns a dictionary with both choices.

check_win(player, computer)
Compares the two choices and determines the outcome.

The game prints both choices and the result to the screen.

Requirements

Python 3.x

No external libraries needed (only uses Python’s built-in random module).

Example Output
Enter a choice (rock, paper, scissors): rock
You chose rock, computer chose paper
Paper covers rock! You lose.

Future Improvements

Add input validation (handle typos)

Keep score for multiple rounds

Add a graphical interface or web version
