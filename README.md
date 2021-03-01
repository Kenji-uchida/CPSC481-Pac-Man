# Pacman State-Space Search
Pacman State-Space Search is an implementation of the general search algorithms Breadth-First Search (BFS) and Depth-First Search (DFS) in a Pacman scenario. This was written in 
Python using a Queue for BFS and a Stack for DFS. In fact, the algorithm implementations are the exact same except for the data storage. The purpose of using a Pacman scenario is
to find paths through a maze and collect the cherries/points. 

## How to test
If you run the command: ```python autograder.py``` then you will see the test cases that were wrote to assure the algorithms are written properly. The test cases for BFS and DFS both pass.

### Files
This project contains a lot of files but most is to display/configure the GUI of the application. A few files to describe:
```
search.py - Where the BFS and DFS searches are performed
pacman.py - The main file that runs the Pacman game and handles the game state
game.py - The logic behind how the Pacman world works such as Agent State, Agent, Direction, and Grid
util.py - The optimized data structures used for searching
searchAgents.py - Different types of Pacman agents
layout.py - Stores layout files and content

The rest of the files can be assumed by their title and looking at the code what they implement
```

#### Authors
Kenji Uchida
Eric van der Roest
Jordan Wermuth
Tyler Bloom
