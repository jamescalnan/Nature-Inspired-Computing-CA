# Ant Colony Optimization for the Traveling Salesman Problem

## ECM3412 - Coursework Exercise

This project is an implementation of the Ant Colony Optimization (ACO) algorithm to solve the Traveling Salesman Problem (TSP) with datasets representing city distances in Brazil and Burma. The goal is to optimize travel routes for a company operating in multiple cities by minimizing the total cost of traveling between all cities, represented by a distance matrix.

### Lecturers
- Dr. Ayah Helal (a.helal@exeter.ac.uk)
- Dr. David Walker (d.j.walker2@exeter.ac.uk)

### Deadline
13th December 2023, 12:00 (noon)

### Description
The task involves implementing the ACO algorithm with various parameters, such as the number of ants, pheromone evaporation rate, pheromone importance factor (alpha), heuristic importance factor (beta), and the number of iterations. The goal is to explore different parameter settings and approaches to find the most efficient travel routes.

### Experiments
Experiments include ACO approach variations, evaporation rate, colony size, and heuristic functions.

## Getting Started

### Prerequisites
- Python 3.8 or higher
- Libraries: NetworkX, Matplotlib, Multiprocessing, tqdm

### Installation and Running
Run the Jupyter Notebook `ACO Notebook.ipynb` to execute the code:
```bash
jupyter notebook ACO Notebook.ipynb
```

### File Structure
- `datasets/`: XML files with city data for Brazil and Burma.
- `images/`: Generated graphs and paths from ACO solutions and metrics.
- `results/`: Results of experiments in JSON format.
- `ACO Notebook.ipynb`: Main Jupyter Notebook with implementation and experiments.
- `README.md`: This file.
- `Other results/`: Other good results.

## Results and Analysis
Results of the minimum cost solution are in the `results/` directory. Analysis of the experiments is provided in `Nature_Inspired_Computing_Report.pdf`, addressing questions related to parameter combinations, reasons behind findings, and comparative analysis with other algorithms.

## Questions and Answers
Refer to `Nature_Inspired_Computing_Report.pdf` for detailed answers to the coursework questions, including best parameter combinations, reasons behind findings, and comparative analysis with other nature-inspired algorithms.