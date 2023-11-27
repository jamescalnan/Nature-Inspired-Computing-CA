# Ant Colony Optimization for the Traveling Salesman Problem

## ECM3412 - Coursework Exercise

This project contains the implementation of the Ant Colony Optimization (ACO) algorithm to solve the Traveling Salesman Problem (TSP) with datasets representing city distances in Brazil and Burma.

### Lecturers
- Dr. Ayah Helal (a.helal@exeter.ac.uk)
- Dr. David Walker (d.j.walker2@exeter.ac.uk)

### Deadline
13th December 2023, 12:00 (noon)

### Description
The task is to optimize travel routes for a company operating in multiple cities. The ACO algorithm is implemented to minimize the total cost of traveling between all cities, represented by a distance matrix.

### Algorithm Parameters
The algorithm's parameters include the number of ants, pheromone evaporation rate, pheromone importance factor (alpha), heuristic importance factor (beta), and the number of iterations.

### Experiments
Experiments were conducted by varying one parameter at a time while keeping others constant to observe the impact on the algorithm’s performance. The parameters explored include variations in ACO approach, evaporation rate, colony size, and heuristic functions.

## Getting Started

### Prerequisites
- Python 3.8 or higher
- NetworkX library
- Matplotlib library (for plotting)
- Multiprocessing library (for parallel execution)
- tqdm library (for progress bars)

### Installation
Clone the repository to your local machine:
```bash
git clone https://github.com/jamescalnan/Nature-Inspired-Computing-CA
```

## Results
Results of the experiments, including tables and graphs, are included in the results directory. The best parameter combination and answers to the questions are provided in the analysis.pdf file.

## Questions and Answers
Q1: Best parameter combination.
Q2: Reasons for the findings.
Q3: Influence of each parameter setting.
Q4: Additional local heuristic function.
Q5: Variations to improve results.
Q6: Comparison with other nature-inspired algorithms.