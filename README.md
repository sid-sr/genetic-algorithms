# Genetic Algorithm for Shortest Path:
---
Genetic algorithm to find the shortest path between 2 nodes in a graph.
The solution below (second image) was obtained over 400 iterations on a 100 node graph with a population size of 30 and 5% mutation rate. The optimal solution is found using Dijkstra's algorithm (first image). Different random initialisations for the GA led to different results, as expected.

Run using ```ShortestPathGA/testing.py``` and visualised using [NetworkX](https://networkx.github.io/) and [Gephi](https://gephi.org/). <br>
Optimal shortest path (by Dijkstra) Cost: 1.156  <br>
Genetic Algorithm Cost: 1.562

<p align="middle">
  <img src="./images/dijkstra-sp.svg" width="400" height="500">
  <img src="./images/genetic-sp.svg" width="400" height="500">
</p>
<h5 align="center">Dijkstra vs. Genetic Algorithm</h5>

## Usage:
---
1. Run ```pip install requirements.txt```
2. Run ```main()``` in the testing.py files with the required hyperparameters.

