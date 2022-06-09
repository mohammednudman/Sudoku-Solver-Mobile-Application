### Project Motivation

One day I was browsing through Reddit, I came across a project, It was a sudoku solver using video cam stream. The project was cool, but there was the only thing I didn’t like: it used to crop the sudoku image and give a solved sudoku image solution.
So I thought why not project back the solution to the original image to make it look like it's solved in the original image?
Pretty cool right?!

### About Project
The project is simple, take the sudoku image, solve it and project back the solution to the original image, thats all!!
Well, that was my initial plan, but the execution is another thing.
Brief project technology description :

Get the sudoku block in the image — Python OPEN CV
Crop the sudoku image and change perspective — Python OPEN CV
Extract the digits in some ordered manner — Python KNN Model
Solve the sudoku — Using Backtracking Algorithm 
Project back the solution into the original image — Python OPEN CV


