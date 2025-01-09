Vehicle Routing Problem (VRP) Solver

This project provides a solution to the Vehicle Routing Problem (VRP), utilizing evolutionary algorithms for optimization. The implementation is contained in a Jupyter Notebook, allowing for interactive exploration and visualization of the problem and solution.
Features

    Generates random locations and a depot for the VRP.
    Simulates the use of multiple vehicles for route optimization.
    Employs the DEAP library for evolutionary algorithm-based optimization.
    Visualizes the routes and results.

Prerequisites

Before running the notebook, ensure you have the following Python libraries installed:

    matplotlib
    deap
    numpy

You can install the required packages using pip:

pip install matplotlib deap numpy

How to Use

    Clone this repository to your local machine.
    Open the Vehicle_Routing_Problem.ipynb file in Jupyter Notebook or JupyterLab.
    Run the cells sequentially to:
        Generate random locations and define the problem.
        Configure and run the optimization algorithm.
        Visualize the optimized routes.

Problem Overview

The VRP is a combinatorial optimization problem where the goal is to determine the optimal routes for a fleet of vehicles to deliver goods to a set of locations, starting and ending at a central depot. This implementation addresses:

    Minimizing the total distance traveled.
    Assigning locations to vehicles efficiently.

Key Components

    Location Generation: Randomly creates a set of locations within a specified area.
    Evolutionary Algorithm: Implements optimization using the DEAP library.
    Visualization: Uses matplotlib to display routes and depot.
