# Algorithmic Game Theory and Mechanism Design:

This repository contains the work done as part of the WiM DRP project at the University of Waterloo, under the research topic **Algorithmic Game Theory and Mechanism Design**. The primary objective of this research is to develop efficient algorithms for computing Nash Equilibria (NE) in graphical games, focusing specifically on cyclic graph structures.

## Key Achievement

### Nash Equilibrium Computation for Cyclic Graphs

We have developed an **algorithm to compute the Nash Equilibrium (NE) for cyclic graphs in polynomial time**. This is a significant advancement in the field of algorithmic game theory, as computing Nash Equilibria for cyclic structures is generally a computationally challenging problem. Our algorithm ensures that this computation can be done efficiently, even for large-scale cyclic graphs.

### Features of the Algorithm:
- **Input**: The algorithm takes as input a cycle graphical game \( G \), defined on cyclic graph structures.
- **Output**: It computes the Nash Equilibrium \( (a^*, \phi_q) \), where \( a^* \) is the optimal scaling factor and \( \phi_q \) is the corresponding equilibrium strategy.
- **Time Complexity**: The algorithm runs in **polynomial time**, making it applicable to large graphs with a reasonable amount of computational resources.

## Limitations & Future Work

### Current Limitations:
- **Graph Structure**: The algorithm is currently limited to certain types of **cyclic graph structures**. Specifically, it does not handle more complex graph types in the general case.
- **Scalability**: Although polynomial, the algorithm's performance may degrade as the graph size grows beyond certain thresholds, depending on the specifics of the graph structure.

### Future Work:
- **Expansion to Cactus Graphs**: Our goal for future development is to extend this algorithm to compute Nash Equilibria for **cactus graphs** in polynomial time. Cactus graphs are a generalization of trees with cycles, and providing an efficient solution for such graphs would expand the applicability of the algorithm to a broader class of graphical games.
- **Generalization and Optimization**: We aim to optimize the algorithm further for scalability and efficiency, enabling it to handle larger and more diverse types of graph structures.
