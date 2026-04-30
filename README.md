# Emerging Technologies

A Jupyter notebook implementing quantum algorithms and exploring emerging computational paradigms, from classical cryptographic functions to quantum computing fundamentals.

## Overview

This repository contains solutions to emerging technologies problems that progress from classical boolean functions to quantum algorithm implementations:

- **Problem 1**: Generating Random Boolean Functions (constant and balanced functions with hidden implementations using closures)
- **Problem 2**: Classical Testing for Function Type (determining if functions are constant or balanced classically)
- **Problem 3**: Quantum Oracles (implementing quantum gates for single-input boolean functions)
- **Problem 4**: Deutsch's Algorithm with Qiskit (quantum algorithm for determining function type with a single query)
- **Problem 5**: Scaling to the Deutsch–Jozsa Algorithm (extending the quantum algorithm to four-bit functions with phase kickback)

## Requirements

- Python 3.12+
- Qiskit 2.3.0+
- Qiskit Aer (quantum simulator)
- Matplotlib
- NumPy

## Getting Started

### Using GitHub Codespaces

1. Click the **Code** button on GitHub and select **Open with Codespaces**
2. The dev container will automatically set up the environment with all dependencies
3. Open `problem.ipynb` in VS Code's Jupyter extension


## Running the Code

Open `problem.ipynb` and run the cells sequentially. Each problem section contains:

- Markdown explanations of quantum computing concepts
- Python implementations using Qiskit
- Quantum circuit visualizations
- Test demonstrations validating the implementations

The notebook is designed to be run from top to bottom, as later problems build upon functions and concepts defined in earlier ones.

## Project Structure

```
emerging_technologies/
├── .devcontainer/       # Dev container configuration for Codespaces
│   ├── devcontainer.json
│   └── Dockerfile
├── problems.ipynb       # Main notebook with all implementations
└── README.md
```