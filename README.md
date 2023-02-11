# Pacman vs Ghosts Challenge

Ms. Pacman is a classic, non-deterministic, multi-agent game that is considered difficult
for most humans. 

In this project avaluation for the AI course whe have to design a controller for Ms. Pacman. Any AI approach, other than that already available in the framework, is acceptable. 

Implement your controller, using the API of the code framework. The implementation is to be made in the file **pacman\src\screenpac\controllers\g07.java**. Change the controller to be used in a simulation in the function main of the class **pacman\src\screenpac.model.Game**.

## Game On

The competition is won by the group with the highest average score taken over three runs.
Should a draw occur, the total duration time of the runs will be used as performance
measure. The lower the better.

### Rules
1. The competition has two stages;
2. All groups are invited to the first stage of the competition, under the following
conditions:
    - 3 (three) simulations with 4 (four) lives each;
    - Ghost team used: **PincerTeam**
3. A group ranking will be produced based on the score of the three simulations.
4. Only the three first ranked groups will have the chance to participate in the second
phase (finals), which will take place under to following conditions:
    - 3 (three) simulations with 4 (four) lives each;
    - Ghost team used: **LegacyTeam**
5. The competition rank will be that of the finals followed by the group rank obtained
in the first stage.
6. No code changes are allowed during the competition.
7. Unspecified events will be judged by the instructor;
8. Appeals, complaints or grievance claims are not accepted.

## Mazes

There are 4 mazes that are processed before each run, pill index indicate the number of normal pills and power index indicates the number of special pills. It also indicates the size of the maze and the distribution of neighbours in each (walkable) node (majoraty most comon having only 2 neighbours).

Printed maze info in **screenpac.model.Maze.processOldMaze(OldMaze maze)**
Printed mazes processes in **screenpac.model.Level**
