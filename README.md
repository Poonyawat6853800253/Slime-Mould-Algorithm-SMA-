# Slime-Mould-Algorithm-SMA-
This project demonstrates the Slime Mould Algorithm (SMA) on a 2D Sphere optimization problem. It shows how agents explore and exploit the search space, track the best fitness over iterations, and visualize convergence behavior. Created for learning bio-inspired optimization and metaheuristic search.

# Slime Mould Algorithm (SMA)

This project demonstrates the Slime Mould Algorithm (SMA), a bio-inspired metaheuristic optimization method, on a simple 2D Sphere function. The notebook shows how a population of agents searches for the global minimum and how the algorithm balances exploration and exploitation over multiple iterations.

## Purpose
This notebook was created to study how the Slime Mould Algorithm works in practice. It helps explain the main SMA concepts, including population initialization, fitness ranking, adaptive weights, position updates, and convergence toward an optimal solution.

## What the project does
- Defines a simple objective function: Sphere function
- Initializes a population of search agents in 2D space
- Evaluates fitness values for all agents
- Updates positions using SMA-inspired rules
- Balances exploration and exploitation during the search
- Tracks the best fitness over iterations
- Visualizes the convergence curve
- Visualizes agent positions at the start, middle, and end of optimization

## Why this project is useful
This project is useful for:
- learning the basics of metaheuristic optimization
- understanding how SMA updates candidate solutions
- visualizing search behavior in a 2D optimization space
- comparing bio-inspired algorithms with other optimizers
- serving as a foundation for solving more complex optimization problems

## Key Concepts Covered
- Objective function optimization
- Population-based search
- Fitness sorting and ranking
- Adaptive weight calculation
- Exploration vs exploitation
- Convergence analysis

## Technologies Used
- Python
- NumPy
- Matplotlib

## Objective Function
The notebook uses the **Sphere Function**:

f(x) = sum(x^2)

Its global minimum is at:
- **x = (0, 0)**
- **f(x) = 0**

## Outputs
The notebook generates:
- **Convergence Curve:** best fitness value over iterations
- **Search Space Visualization:** agent distributions at different stages of the search process

## Future Improvements
Possible extensions include:
- applying SMA to higher-dimensional problems
- testing on benchmark functions such as Rastrigin, Rosenbrock, or Ackley
- comparing SMA with PSO, GA, or DE
- tuning SMA parameters for better performance
