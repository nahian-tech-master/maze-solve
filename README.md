
# MAZE SOLVE BY PYTHON PROGRAMME

> This is a Python program that solves a maze represented in a text file. The program implements both Depth-First Search (DFS) to find a solution path from a start point A to a goal point B in the maze.
### FEATURE
- Read a maze from a text file.
- Solve the maze using Depth-First Search or Breadth-First Search.
- Display the solution path in the console.
- Visualize the maze solution in an output image file.
### Installation
- Python 3.x
- PIL (Python Imaging Library) for visualizing the maze solution
### Installation Steps
1) Navigate to the project directory
2) Install the required library:pip install pillow

## How to programme work

### import sys :
Here sys is a system module which is work on command line argument. In code 218 no line sys module check when user input the argument, its length more then 2 or not if more then 2 sys module exit and print "Usage: python maze.py maze.txt" which is show how to print the maze(here have 3 maze, if we want solve the maze just write in argv[1]= maze1.txt/maze2.txt/maze3.txt).

### Maze(): 
Call the Maze class.This class solve and display the maze.

### __init__(self, filename):
This function handle by Maze() class.This function read the file which user given argv[1] by 'with open(filename) as f:'.Then file 'f' store in 'contents'. 'contents' read height and width of the maze.Creat a array 'walls[]' and find start and goal of the maze.if the maze has extra row then its handle by 'IndexError'.

### print(self): 
This function also hanble by Maze() class. This function print the original maze photo.

### neighbors(self, state): 
This function also hanble by Maze() class.This function find all possible path to solve the maze.

### solve(self) : 
This function solve the maze if there is atleast one solution.Its starts by creating a node which is start point(A). Then it add next node by using add method of 'stackFrontier' or 'QueueFrontier'.

### output_image(self, filename, show_solution=True, show_explored=False)
This function creates an image of the maze, optionally showing the solution and the explored paths.The maze is saved as an image file named maze.png.

# OUTPUT:
## maze1

![image alt](https://github.com/nahian-tech-master/maze-solve/blob/main/maze-solve/maze1.png)

## maze2

![image alt](https://github.com/nahian-tech-master/maze-solve/blob/main/maze-solve/maze2.png)

## maze3

![image alt](https://github.com/nahian-tech-master/maze-solve/blob/main/maze-solve/maze3.png)


