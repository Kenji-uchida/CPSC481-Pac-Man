# Multi-Agent Pacman
For this project, we designed agents (including ghosts) for the classic version of Pacman by implementing minimax search and evaulation function design. We completed ReflexAgent in multiagents.py to play Pacman. Our ReflexAgent considers the location of food and ghosts in order to beat the game and includes methods that query the GameState for information.

## How to test
The agent will run against the openClassic layout 10 times and will receive points depending on the outcome.
0 points if the agent times out or doesn't succeed
1 point if the agent wins at least 5 times
2 points if the agent wins all 10 times 
Extra point if the average score is greater than 500
Extra 2 points if the average score is greater than 1000 
Run the command: ```python autograder.py -q q1``` to test with graphics.
Run the command: ```python autograder.py -q q1 --no-graphics``` to test with no graphics.

### Files
Here are the descriptions of the main files in this project. All other files display/configure the GUI of the application.
```
multiAgents.py - Where all of the multi-agent search agents reside
pacman.py - The main file that runs the Pacman game and handles the game state
game.py - The logic behind how the Pacman world works
util.py - The optimized data structures used for searching

The rest of the files can be assumed by their title and looking at the code what they implement
```
#### Authors
Kenji Uchida,
Eric van der Roest,
Jordan Wermuth,
Tyler Bloom
