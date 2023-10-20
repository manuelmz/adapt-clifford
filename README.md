# adapt-clifford

The MaxCut problem asks to partition the set of vertices of an undirected graph into two disjoint subsets as to maximize the sum of the weighted sum of the edges connecting nodes across the partition.

ADAPT-Clifford is a quantum-inspired polynomial time algorithm for this problem. It aims at solving the problem by constructing an stabilizer state which encodes a good approximate cut of the graph under consideration, then a measurement in the computational basis returns a bitstring with the approximate cut.

This new algorithm was introduced in [ref]. In this repository we provide three notebooks solving MaxCut with ADAPT-Clifford on three different type of graph ensembles.

In particular:
- $K$-regular graps
- Erdös-Rény graphs
- weighted complete graphs.


