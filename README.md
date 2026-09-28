# Shortest-Path Algorithms

A Python framework for implementing, comparing, and evaluating shortest-path algorithms on real-world graph datasets.

The project was developed as part of **COMPSCI 2XC3: Algorithms and Software Design** in collaboration with **Yanna Lazarova**, **Oriana Rueckert**, and **Lana Zgonjanin**.

## Overview

This project provides implementations of several shortest-path algorithms and a framework for comparing their performance across graphs of varying size and density.

The analysis considers:

* Runtime performance
* Space complexity
* Solution accuracy
* Algorithmic trade-offs across different graph structures

Real-world London transportation network data is used for the experimental evaluation.

## Algorithms

The framework includes both single-source and all-pairs shortest-path algorithms:

* **Dijkstra's Algorithm**
* **Bellman-Ford**
* **Floyd-Warshall**
* **A*** with configurable heuristic functions

## Software Design

The project uses object-oriented design principles to provide a modular framework for implementing and comparing algorithms.

### Design Patterns

* **Strategy Pattern** — allows different shortest-path algorithms to be used interchangeably.
* **Adapter Pattern** — integrates A* into the common algorithm interface.
* **Composition** — supports modular and extensible system components.

This design makes it possible to experiment with different algorithms while maintaining a consistent interface.

## Technologies

* **Language:** Python
* **Libraries & Modules:** `heapq`, `math`, `typing`, `random`, `timeit`, `csv`, `copy`
* **Visualization:** Matplotlib
* **Concepts:** Graph algorithms, object-oriented programming, algorithm analysis, software design patterns
* **Data:** London transportation network data

## How to Run

### Requirements

* Python 3
* Matplotlib

### Install dependencies

```bash
pip install matplotlib
```

### Run

```bash
python3 main.py
```

The program uses the included London transportation network data to run shortest-path algorithms and perform the associated analysis.

## Results & Analysis

The project includes a detailed report covering:

* Theoretical time and space complexity
* Empirical runtime comparisons
* Accuracy evaluation
* Performance across graphs of different sizes and densities
* Software architecture and design decisions

See [`Report.pdf`](Report.pdf) for the full analysis.

## Technical Concepts

* Graph representations
* Single-source shortest-path algorithms
* All-pairs shortest-path algorithms
* Heuristic search
* Algorithm complexity analysis
* Object-oriented programming
* Strategy and Adapter design patterns
* Empirical performance evaluation
* Real-world graph data
