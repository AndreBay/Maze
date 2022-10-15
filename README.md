# Maze

Purpose of this project was to develop an automated system for generating the structure of the maze and finding a way out of it. There should be two user roles in the system: the "Administrator" role and the "Player" role. There is user authorization in the system (login/password entry).

Algorithms to generate maze:
  - DFS (Depth-first search) algorithm
  - Prim’s algorithm

Algorithms to generate maze:
  - Lee algorithm
  - Wall follower algorithm

The "Administrator" role

The administrator should be able to create a maze by pre-configuring its parameters: set the width (from 7 to 19 cells) and height (from 7 to 19 cells) of the maze. Then choose the algorithm for generating the maze (in depth and Prima) and the method of arranging the entrance and exit. To do this, automatic and manual placement of input and output must be implemented in the system. With automatic placement, the system must set the input and output arbitrarily. With manual placement, the administrator must set the input and output independently. In both cases, the following restrictions should be taken into account: the entrance and exit should be located only on the perimeter of the maze, should not be in corners, and the distance between them should be at least one cell. Also, the administrator should be given the opportunity to choose one of the four design themes of the maze, the ability to save the created maze to a file of a given format and download the maze from the file.

The "Player" role

The player must be able to pass the mazes created by the administrator in automatic mode. To do this, he must load the maze. Before starting the passage, the system must provide the player with the opportunity to choose the theme of the maze, the algorithm for finding the way out of the maze (wave algorithm or one-hand algorithm). Two types of visualization of the passage (dynamic and static) should be implemented for them. For the one-hand algorithm, the user will be able to choose the type of dynamic visualization of the passage of the maze (step-by-step view or with a delay), as well as settings for the speed of movement of the character (slow, normal, fast).
The system should also be able to obtain background information, both about the system itself and the capabilities provided by it.
