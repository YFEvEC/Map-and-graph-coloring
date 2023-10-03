# Map-and-graph-coloring

# Graph Coloring via Linear Programming

This repository contains our approach to solve the graph coloring problem through linear programming for various constraints, inspired by the Four Color Theorem.

## Introduction

The Four Color Theorem posits that any map can be colored using at most four colors in such a way that no two adjacent regions are of the same color. This project explores this theorem by choosing real-world maps, modeling them as graphs, and using linear programming to derive optimal colorings.

## Contents

- `/maps/` - Contains the maps chosen for this project.
- `/graphs/` - The adjacency graph representation of the chosen maps.
- `/lp-models/` - Linear programming models for the coloring problems.
- `/results/` - Outputs from the LP solver and the resulting colored maps and graphs.
- `/code/` - Source code and scripts.

## Features

1. **Basic Coloring Problem**: Finding the minimum number of colors such that no two adjacent regions share a color.
2. **Advanced Coloring Problem**: A constraint is added such that two regions that border the same region cannot have the same color.
3. **Dual Coloring Problem**: Assigning two colors to each region such that no two adjacent regions share any of the two colors.

## Setup and Execution

1. **Dependencies**:
   - Ensure you have `lpsolve` or an equivalent LP solver installed.
   - Python3 with packages: `[list necessary packages like matplotlib, numpy, etc.]`

2. **Running the Code**:
   ```bash
   # Navigate to the code directory
   cd code/
   
   # Run the main script (modify as per actual filename)
   python3 main_script.py
   ```

3. **View Results**: After execution, check the `/results/` directory for colored maps and graphs.

## Contribution

We welcome contributions to improve the LP formulations, add new map examples, or enhance the efficiency of the code. Please raise an issue or submit a pull request!

## Team

- **[Name 1]** - Role/Email
- **[Name 2]** - Role/Email

## References

- Appel, K., & Haken, W. (1976). Every Planar Map is Four Colorable.

## License

This project is licensed under the MIT License - see the `LICENSE.md` file for details.

---
