# SpiderLine4: AI Project

This repository is a project to explore and study the following types of AI algorithms: Minimax,
Minimax with αβ cuts cuts and Monte Carlo Tree Search playing the game SpiderLine4.

# Download and Project Execution
To download this repository and explore the code, make sure you have git installed and type in the terminal:
```
$ git clone https://github.com/UShouldRun/spiderline4
```
To run the project, make sure the following steps are/were done:
 - installed one of the latest versions of python (3.10 should be enough);
      if not type in your terminal the equivalent to mine on ubuntu:
      ```
      $ sudo apt update
      $ sudo apt install python3.11
      ```
 - installed pygame;
      if not lets install pip in case you haven't yet:
      ```
      $ sudo apt install python3-pip
      $ pip install pygame
      ```

With all have that done, we should be good to run the project. So now run in the terminal the following:
```
$ python3 main.py
```

# Game

SpiderLine4 is based on the classic Connect4 game. But, instead of only being possible to
place the pieces from bottom to top, we can place them from bottom to top, top to bottom,
left to right and right to left. The first player to connect 4 pieces of their color wins.

# Project's Aim

In this work, the aim was to implement a game for two players and solve different versions of this game,
using different AI algorithms. 

Human-human, human-computer and computer-computer game modes are being developed, where the
computer exhibits different skills (levels of difficulty).
Computer performance's also compared regarding the different skills (hard, medium, easy),
corresponding to different evaluation functions, different depth levels of Minimax,
different successor generation ordering and variants of the Minimax Search
with αβ cuts, Negamax and the Monte Carlo Tree Search algorithms.

We focused on the analysis of the results of the computer players (wins, draws, losses, and other quality
parameters, such as the number of plays to obtain the win/loss) and average time spent and memory usage to obtain the plays.

# Open Source Project Credits

All the code is free to use and experiment with, but all github accounts stated bellow should be mencionned.

Project made by Henrique Teixeira (UShouldRun), João Ferreira (johnpierre), Pedro Pereira (PedroPeras).
