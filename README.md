# GridWorld

### Environment:
1) Agent: The agent starts from (0,0) and the goal is to reach the bottom right corner
2) Grid: It is a n * n grid. It consists of walls, demons, and bullets.
3) If the agent goes out of the grid, the game is terminated.
4) The agent cannot pass through the walls.
5) The agent can collect bullets which it can use to kill demons, if encountered.
6) The game is terminated if a demon is encountered and the agent has no bullets.

### Actions:
The agent can move:
1) Up
2) Right
3) Down
4) Left


### Rewards:
1) The agent reaches the goal position: +10
2) The agent collects a bullet: +0.5
3) The agent kills a demon: +0.25
4) The agent goes out of bounds: -3
5) A demon kills the agent: -5
6) The agent tries to pass through a wall: -0.4
