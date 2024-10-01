## import sys : Here sys is a system module which is work on command line argument. In code 218 no line sys module check when user input the argument, its length more then 2 or not if more then 2 sys module exit and print "Usage: python maze.py maze.txt" which is show how to print the maze(here have 3 maze, if we want solve the maze just write in argv[1]= maze1.txt/maze2.txt/maze3.txt).

## Maze(): Call the Maze class.This class solve and display the maze.

## __init__(self, filename):This function handle by Maze() class.This function read the file which user given argv[1] by 'with open(filename) as f:'.Then file 'f' store in 'contents'. 'contents' read height and width of the maze.Creat a array 'walls[]' and find start and goal of the maze.if the maze has extra row then its handle by 'IndexError'.





