# Solving-a-4x4-Letter-Placement-Puzzle-Using-Genetic-Algorithms
A software application that solves a puzzle game similar to Sudoku using genetic algorithms. 
## 1. Introduction
The purpose of this report is to describe and analyse the development of a software application that solves a puzzle game similar to Sudoku using genetic algorithms. The objective of the puzzle is to fill a 4x4 grid with four different letters, ensuring that each column, each row, and each of the four sub-grids of size 2x2 contain each letter only once. The report will discuss the encoding of input and output data, the selection of the fitness function, and the implementation of genetic operators.

## 2. Problem Encoding
To represent the puzzle configuration and solve it using genetic algorithms, an appropriate encoding scheme is required. In this application, we can use a string of length 16 to represent the 4x4 grid. Each character in the string represents a cell in the grid and corresponds to a letter. For example, "ABCDABCDABCDABCD" could represent the initial grid configuration.
![image](https://github.com/drnsmith/Solving-a-4x4-Letter-Placement-Puzzle-Using-Genetic-Algorithms/assets/105845843/5104967a-6c50-4a00-8e7c-245bf734494b)
