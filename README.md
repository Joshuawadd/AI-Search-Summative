# AI-Search-Summative
Repository for the AI search summative in the Software Methodologies module. The goal was to create algorithms to provide solutions to the travelling salesman problem.

The file AlgAbasic shows a greedy search algorithm.

The file AlgAEnhanced shows an enhanced vesion of the greedy algorithm by changing the method used to break ties. In the basic algorithm, ties are broken by simply using the first node found. In the modified version, the program looks at both nodes and sees which one has the smallest distance to their next node. If again this is equal, then it will take the first node that it found.

The file AlgBbasic shows an A* search algortihm (with greedy heuristic)
