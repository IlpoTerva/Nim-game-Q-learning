# Nim-game-Q-learning

Nim-game is a game where two players take turns taking a match out of pile. The one who has to take the last match loses the game.
Here is image of the game:

![image](https://github.com/user-attachments/assets/964450b6-9b35-43bb-bfa9-6d01beb6ea11)


Game logic: You can only take from one row at the time. For instance you can take 7 matches out of the fourth row, but you cannot take 1 match from row 2 and one from row 3 in one turn.

Q-learning is a reinforcement learning algorithm, where the agent assigns a value for each action it might take.

In this project I implemented Q-learning algorithm for this Nim game.

In the file nim.py is the game itself and the q-learning algorithm to teach the game to AI bot.

play.py is file which is used to play the game. As of now the game is played in command line.
