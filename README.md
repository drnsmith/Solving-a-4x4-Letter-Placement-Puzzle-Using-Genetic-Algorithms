### Solving a 4x4 Letter Placement Puzzle Using Genetic Algorithms
An application that utilises genetic algorithms (GAs) to solve a 4x4 letter puzzle game similar to Sudoku.

#### Project Overview
This project solves a 4x4 letter placement puzzle using genetic algorithms. The objective is to fill a 4x4 grid with four distinct letters, ensuring each row, column, and each 2x2 sub-grid includes every letter exactly once. Similar to Sudoku, the challenge lies in arranging the letters without repeating them in any row, column, or 2x2 section. This README explains the implementation, fitness functions, genetic operators, and overall approach of the genetic algorithm used.

#### Technologies Used
The following technologies were used in this project:

* **[Python](https://www.python.org/downloads)**: Version 3.11.0, used as the main programming language for implementing the genetic algorithm.
* **[Visual Studio Code](https://visualstudio.microsoft.com/es)**: Version 1.73.v, as the integrated development environment (IDE) for writing and debugging the code.

#### How It Works
- The program uses genetic algorithms to find solutions to the 4x4 puzzle by simulating a population of possible puzzle states and evolving them over generations.
- The genetic algorithm employs selection, crossover, and mutation to improve the solutions, using a fitness function that scores solutions based on how close they are to meeting the puzzle's constraints.
- The goal of the genetic algorithm is to maximise the fitness score, which represents a correctly completed puzzle grid.
- Progress is visualised through each generation, showing how the algorithm converges on valid solutions.


#### Getting Started
To run this project:

```bash
# Clone this repository
git clone [YOUR REPO URL]
```
#### Navigate to the directory
```
cd [YOUR REPO NAME]
```
#### Run the Genetic Algorithm Python script
```
python main.py
```
   
### Usage
To run this program, use the genetic algorithm Python code provided in this project. The project automatically encodes the puzzle configuration and performs the evolutionary process to find a solution.

### Implementation Details
 - **Encoding**: Each grid position in the 4x4 puzzle is encoded, allowing the genetic algorithm to handle it as a chromosome.

 - **Fitness Function**: Measures the number of unique letters in each row, column, and sub-grid, rewarding grids that meet the puzzle constraints.

 - **Genetic Operators:**
 - **Selection**: Chooses the fittest individuals to parent the next generation.
 - **Crossover**: Combines genes from two parents to produce offspring.
 - **Mutation**: Introduces random changes to maintain diversity in the population.

### Contributing
A big thanks to project collaborators Luis Atristain and Tamas Ramazaki for their valuable contributions and insights, which made this project possible.

### License
Distributed under the MIT License. See LICENSE for more information.
