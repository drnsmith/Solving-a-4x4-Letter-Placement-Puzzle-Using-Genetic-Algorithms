# Solving-a-4x4-Letter-Placement-Puzzle-Using-Genetic-Algorithms
A software application that solves a puzzle game similar to Sudoku using genetic algorithms. 
## 1. Introduction
The purpose of this code is to develop a software application that solves a puzzle game similar to Sudoku using genetic algorithms. The objective of the puzzle is to fill a 4x4 grid with four different letters, ensuring that each column, each row, and each of the four sub-grids of size 2x2 contain each letter only once. The encoding of input and output data, the selection of the fitness function, and the implementation of genetic operators are discussed in the report.

## 2. Problem Encoding
To represent the puzzle configuration and solve it using genetic algorithms, an appropriate encoding scheme is required. In this application, we can use a string of length 16 to represent the 4x4 grid. Each character in the string represents a cell in the grid and corresponds to a letter. For example, "ABCDABCDABCDABCD" could represent the initial grid configuration.
## 3. Genetic Algorithm Implementation
### 3.1 Fitness Function
The fitness function evaluates the quality of an individual solution and guides the genetic algorithm towards finding better solutions. In this puzzle, the fitness function should reflect adherence to the rules of the game. A suitable fitness function for this problem can be defined as follows:
- Initialise a fitness score to zero.
- For each row, column, and sub-grid, count the number of unique letters.
- Subtract the count of repeated letters from the total possible letters (4).
- Add the counts for each row, column, and sub-grid to the fitness score.
- The fitness score will be higher for solutions that have fewer repeated letters.

