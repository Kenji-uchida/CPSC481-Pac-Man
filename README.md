# Pacman Heuristic Search
Pacman Heuristic Search is an implementation of A* search algorithm and a formulation of a new problem with a heuristic for it. This was written in Python using a Priority Queue for A* search. The new problem finds the shortest path through the maze that touches all four corners. We implemented the function "aStarSearch" in search.py and implemented the class "CornersProblem" in searchAgents.py. 

## How to test
If you run the command: ```python autograder.py``` then you will see the test cases that were wrote to assure the algorithms are written properly. The test cases for BFS and DFS both pass.

### Files
This project contains a lot of files but most is to display/configure the GUI of the application. A few files to describe:
```
search.py - Where the BFS, DFS, & A* searches are performed
pacman.py - The main file that runs the Pacman game and handles the game state
game.py - The logic behind how the Pacman world works such as Agent State, Agent, Direction, and Grid
util.py - The optimized data structures used for searching
searchAgents.py - Different types of Pacman agents
layout.py - Stores layout files and content

The rest of the files can be assumed by their title and looking at the code what they implement
```
#### Authors
Kenji Uchida,
Eric van der Roest,
Jordan Wermuth,
Tyler Bloom
