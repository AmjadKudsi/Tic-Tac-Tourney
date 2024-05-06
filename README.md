# Tic-Tac-Tourney
Tic-Tac-Toe game logic with Random, Minimax, and Heuristic AI agents competing against a human player in a round-robin tournament. Explore agent dynamics and performance in matches against human opponent.

## Overview:

The project aims to design and implement AI agents using Minimax, Minimax with Alpha-beta pruning, and Expectimax algorithms to play Tic-Tac-Toe optimally. These agents will compete against a human player, with the game logic relying on heuristic functions, random agents, and efficient algorithms. A tournament framework will orchestrate matchups between agents, tracking performance metrics such as execution time and the number of nodes explored. The deliverables include implementing game logic, AI agents, and the tournament framework, with evaluation focusing on flawless execution and tournament dominance based on win rates and performance metrics.

## Team Members:

- [Amjad Ali Kudsi](https://github.com/AmjadKudsi) & [Surya Manjri](https://github.com/suryamanjri00)

## Game Layout:

We're setting up a scenario for Tic-tac-toe where we'll train an agent to play against us. Our agent aims to minimize its utility, while we'll develop a strategy to maximize our own utility. To enhance the agent's decision-making beyond simple minimax, we'll employ alpha-beta pruning and expectimax. 

In this game, the state comprises the board positions of both the agent and its opponent. Initially, we'll have a 3x3 board with zeros indicating available positions, updating them to 1 when we make a move and to -1 when the agent makes a move. Actions represent available positions based on the current board state. Rewards range from 0 to 1 and are given only at the end of the game. Victory is achieved by placing three marks in a horizontal, vertical, or diagonal row.

## Project Explanatory Video:

- [![Demo Video](https://img.youtube.com/vi/WQJifk54LnY/0.jpg)](https://www.youtube.com/watch?v=WQJifk54LnY)

## Project Structure:

- **Python File:** [final_version.py](https://github.com/AmjadKudsi/Tic-Tac-Tourney/blob/main/final_version.py)
  - This Python file contains the entire code of execution.
 
- **Presentation:** [AI Project 1 Final.pptx](https://github.com/AmjadKudsi/Tic-Tac-Tourney/blob/main/AI%20Project%201%20Final.pptx)
  - A presentation summarizing the execution of this project.

- **Screenshots:** ([Screenshots Folder](https://github.com/AmjadKudsi/Tic-Tac-Tourney/tree/main/Screenshots))
  - Screenshots of the project execution.
  - *Start:*
  - ![Start](https://github.com/AmjadKudsi/Tic-Tac-Tourney/blob/main/Screenshots/Start.gif)

  - *Minimax Search Algorithm:*
  - ![Minimax](https://github.com/AmjadKudsi/Tic-Tac-Tourney/blob/main/Screenshots/Minimax.gif)
 
  - *Wrong Inputs from user:*
  - ![WrongInput](https://github.com/AmjadKudsi/Tic-Tac-Tourney/blob/main/Screenshots/WrongInput.png)
 
  - *Minimax Search Algorithm using Alpha-Beta Pruning:*
  - ![AlphaBetaPruning](https://github.com/AmjadKudsi/Tic-Tac-Tourney/blob/main/Screenshots/AlphaBetaPruning.gif)
 
  - *Expectimax Algorithm:*
  - ![Expectimax](https://github.com/AmjadKudsi/Tic-Tac-Tourney/blob/main/Screenshots/Expectimax.gif)
 
  - *Final Results:*
  - ![Results](https://github.com/AmjadKudsi/Tic-Tac-Tourney/blob/main/Screenshots/Results.png)
 
  - *Further Enhancements:* (Work in Progress!)
  - ![Enhancements](https://github.com/AmjadKudsi/Tic-Tac-Tourney/blob/main/Screenshots/Enhancements.gif)


Feel free to explore each section according to your interests. If you have any questions or suggestions, please contact the team members.

**Thank you for exploring our project!**


