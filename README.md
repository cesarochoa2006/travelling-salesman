Travelling Salesman Solver
=========

A TSP Solver using D3.js that generates random points and implements various heuristics to find a solution. Heuristics include hill climber, simulated annealing, two-opt edge swap, nearest neighbor, nearest insertion, and farthest insertion. Also implements a genetic algorithm with tournament selection, order based crossover, and edge swap mutation. Utilizes d3 transition chaining to visualize edge insertion and swaps.

![](/tsp.png)

##Demo

![](/gifs/tsp_iterative_two_opt.gif)

![](/gifs/tsp_simulated_annealing.gif)

##Status

Heuristics so far:

- Nearest Neighbor
- Nearest Insertion
- Farthest Insertion
- 2-opt edge swap
- Hill Climber
- Simulated Annealing
- Genetic Algorithm

Animation works for NN, insertions, and 2-opt edge swap.
SA and HC also have animations but it currently looks buggy (due to performance issues of animating 5000+ steps). 

To-do:

- Update interface (allow user to adjust number of points, add warning that animation for SA and HC is incredibly slow)
- Implement Ant Colony Optimization
- Add animation for Genetic Algorithm
- Add indicator for loading
- Split into smaller files
- Possibly refactor into Tour object