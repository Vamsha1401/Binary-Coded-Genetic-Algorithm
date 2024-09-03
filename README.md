# Genetic Algorithm Implementation

This project implements a genetic algorithm to solve optimization problems. The code includes various methods for selection, crossover, and mutation, allowing for a flexible approach to finding solutions.

## Features

- **Selection Methods**: 
  - Canonical Selection
  - Rank-Based Selection
  - Tournament Selection
  - Roulette-Wheel Selection

- **Crossover Methods**:
  - Single Point Crossover
  - Two Point Crossover
  - Multi Point Crossover
  - Uniform Crossover
  - Uniform Crossover with Mask
  - Half Uniform Crossover
  - Three Parent Crossover

- **Mutation Methods**:
  - Mutation Flipping
  - Mutation Interchanging
  - Mutation Reversing
  - Gene Inversion Mutation

## Getting Started

### Prerequisites

- Python 3.x
- Basic knowledge of genetic algorithms

### Installation

Clone the repository:
```sh
git clone https://github.com/your-username/genetic-algorithm.git
cd genetic-algorithm
```
### Usage

1. **Set Up Initial Parameters:**
Before running the algorithm, you need to set up the initial parameters such as population size, crossover rate, mutation rate, and the target string.
2. **Run the Algorithm:**
Execute the script to start the genetic algorithm:
```sh
python main.py
```
4. **Choose Selection, Crossover, and Mutation Methods:**
The script will prompt you to choose the selection, crossover, and mutation methods. You can select from the available options based on your needs.
5. **Observe the Evolution Process:**
The algorithm will run and display the progress of the population towards the target solution, including the number of generations taken to converge.

## Customization

You can customize the algorithm by adjusting the following parameters:

- **Population Size**: Controls the number of individuals in the population.
- **Crossover Rate**: Determines the frequency of crossover operations.
- **Mutation Rate**: Determines the frequency of mutation operations.
- **Selection Method**: Choose among Canonical, Rank-Based, Tournament, or Roulette-Wheel selection.
- **Crossover Method**: Choose among Single Point, Two Point, Multi Point, Uniform, Masked Uniform, Half Uniform, or Three Parent crossover.
- **Mutation Method**: Choose among Flipping, Interchanging, Reversing, or Gene Inversion mutations.

