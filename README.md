# PageRank Python implementation

The notebook in this repository provides several algorithmic solutions to the PageRank algorithm for computing importance scores on graphs of varying sizes.

This notebook was a deliverable of a project in the course 'Linear Algebra and Optimization' tought on the Bachelor of Data Science at the IT University of Copenhagen.

The notebook begins with a theoretical exercise detailing the matrix representation of a directed graph.
One can think of the directed graph as a representation of a web with `n` pages (nodes) that link (edges) to other pages.

Following the theoretical exercise, four algorithms to compute the PageRank score on a graph are presented:
* The RandomSurfer algorithm
* A simple PageRank algorithm
* An optimized PageRank algorithm
* A graph representation and PageRank algorithm optimized for large graphs

### Data
Two graphs were given for this exercise and can be found in the graphs zip-folder:
* p2p-Gnutella08-mod.txt - A medium-sized graph consisting of 6301 nodes and 20777 edges
* bigRandom.txt - A large graph consisting of 199999 nodes and 10011343 edges

### Requirements
* Python 3
* networkX Python library
* scipy Python library
