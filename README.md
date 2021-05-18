# Maze-solver
Maze solver with Various Search algorithms, GUI animation with features.Implemented using Java. 
Skeleton code was provided and the assignments required us to improve/add more features to it. 

maze51.java / maze51.jar: 
To revise the maze game by switching the start and goal.
Design and implement the following task to revise the maze program to set its start at the top-left corner and its goal at the bottom-right corner. Current program sets its start at the bottom-left corner and its goal at the top-right corner. Your task is to revise the maze program (with new grid and new maze), to run the maze with the new start and goal, and to display the status of the result of the search.


maze52.java / maze52.jar:
Design and implement the following task. After a maze is generated, we like to save the maze into a text file. A maze can be represented by an object of MxN matrix (or of an MxN array). By placing a character of " " for an open cell (that an agent can occupy or pass through) and "#" for a wall (that is, a closed or blocked cell that an agent cannot occupy or pass through). A closed cell is a piece of wall to block an agent to move in over the cell. Initially the start cell is marked in red and the goal cell is marked in green. The blocked cell is marked in black. Also note that the border (the outer cells) should be marked as blocked.

The output of the maze to a text file will be: 

#####
# #G#
# # #
#S  #
##### 

In the saved text file of a maze, each open (unblocked) cell is represented by a blank character and each closed (blocked) cell is represented by a "#" character. The start cell is marked as "S" character and the goal is marked as "G" character. 


New button with “S” is added from maze51 into maze52. This button will save the maze and save it in a txt file. 


maze53.java / maze53.jar:
Design and implement the program (continuing the previous task) so that it can load a maze from a text file. 
For the control panel of the maze GUI, add a button ("Load maze") to load a maze (using a file explorer to navigate the file system and to select a file with file-name box for the input file).

New button with “LOAD” is added from maze52, “S” button is changed to “SAVE” for better presentation. The path of the text file to load is set to user home. The LOAD button can take any saved maze and can continue running through the maze with the search algorithms. 

Some txt files are provided for the SAVE and LOAD features. 
