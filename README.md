# Approximation Algorithms

## About the project

*This the repository for the project of the Advanced Algorithms course.*

The main idea of the project was to conduct an experimental evaluation of three different approximation algorithms for computing metrics in very big graphs:
* Average Path Length (APL)
* Betweenness Centrality
* Clustering Coefficient

For the APL, we implemented the Hyperanf approximation algorithm developed by Paolo Boldi, Marco Rosa, and Sebastiano Vigna in "Hyperanf: Approximating the neighbourhood function of very large graphs on a budget", which heavily relies on the well known cardinality estimation technique developed by Flajolet et al in "Hyperloglog: The analysis of a near-optimal cardinality estimation algorithm".

For the Betweenness Centrality, we implemented the (exact) Brandes algorithm and the recent approximation algorithm developed by Matteo Riondato and Evgenios Kornaropoulos in "Fast approximation of betweenness centrality through sampling".

For the Clustering Coefficient, we implemented the (obvious) O(N^3)** algorithm and the algorithms developed by Siddharth Bhatia in "Approximate triangle count and clustering coefficient".


### Note
We assumed the graphs are undirected and are read from stdin according to the following format:
N 2*M
u v
v u
N: number of vertex
M: number of edges

## Contributors
This is joint work with my friends Miguel Sena, Joana Alves, and Tomás Vieira.
