### Solving a 4x4 Letter Placement Puzzle Using Genetic Algorithms
An application that utilises genetic algorithms (GAs) to solve a 4x4 letter puzzle game similar to Sudoku.


#### Overview
This project solves a 4x4 letter placement puzzle using genetic algorithms. The objective is to fill a 4x4 grid with four distinct letters, ensuring each row, column, and each 2x2 sub-grid includes every letter exactly once. Similar to Sudoku, the challenge lies in arranging the letters without repeating them in any row, column, or 2x2 section. Here's how it work:

- The program uses genetic algorithms to find solutions to the 4x4 puzzle by simulating a population of possible puzzle states and evolving them over generations.
- The genetic algorithm employs selection, crossover, and mutation to improve the solutions, using a fitness function that scores solutions based on how close they are to meeting the puzzle's constraints.
- The goal of the genetic algorithm is to maximise the fitness score, which represents a correctly completed puzzle grid.
- Progress is visualised through each generation, showing how the algorithm converges on valid solutions.
---

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

---
### Usage
To run this program, use the genetic algorithm Python code provided in this project. The project automatically encodes the puzzle configuration and performs the evolutionary process to find a solution.

---
### Implementation Details
 - **Encoding**: Each grid position in the 4x4 puzzle is encoded, allowing the genetic algorithm to handle it as a chromosome.

 - **Fitness Function**: Measures the number of unique letters in each row, column, and sub-grid, rewarding grids that meet the puzzle constraints.

 - **Genetic Operators:**
 - **Selection**: Chooses the fittest individuals to parent the next generation.
 - **Crossover**: Combines genes from two parents to produce offspring.
 - **Mutation**: Introduces random changes to maintain diversity in the population.

---
### Contributing
A big thanks to project collaborators Luis Atristain and Tamas Ramazaki for their valuable contributions and insights, which made this project possible.

---
## Repository History Cleaned

As part of preparing this repository for collaboration, its commit history has been cleaned. This action ensures a more streamlined project for contributors and removes outdated or redundant information in the history. 

The current state reflects the latest progress as of 24/01/2025.

For questions regarding prior work or additional details, please contact the author.

---

### License
Distributed under the MIT License. See LICENSE for more information.
