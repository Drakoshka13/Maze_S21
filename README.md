# Labyrinths_Generator_and_Solver

#### The program is developed by students of School 21: yonnarge, marbrand, madamkyl

## General Information

The Maze program is a desktop application that allows solving two-dimensional mazes.

## Generation

In the Maze program, you can generate an ideal maze according to the Eller's algorithm without closed areas and loops by:

* Choosing the desired number of columns and rows in the maze
* Clicking the "Generate" button
* When clicking the "Solve" button, the maze will find a path from the top left cell to the bottom right

Note that you can use your own start and end points. Simply click on the desired cells.

Importing a maze from a txt file is available in the following format.

The file contains two numbers - the number of rows and columns, as well as two matrices containing the position of vertical and horizontal walls, respectively.

Example:
```
4 4
0 0 0 1
1 0 1 1
0 1 0 1
0 0 0 1

1 0 1 0
0 0 1 0
1 1 0 1
1 1 1 1
```
The generated maze can be exported to a txt file in the format described above.

## Limitations

When using the Maze program, the following limitations should be considered:

Maximum maze size - 50 x 50 cells.
Building solutions is only available for two points.
The maze cannot be scaled - the field is set to a size of 500 x 500 pixels, with a line width of 2 pixels.
Passage width - 1 cell.

## Example of Use

Set the desired width and height
Click on an empty maze field to generate
Select the start point with the next mouse click
Then also select the end point
The next click will clear the field from the solution
