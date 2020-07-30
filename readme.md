# GHS Minimum Spanning Tree in python

This repository holds a simple simulation of distributed Minimum Spanning Tree using GHS algorithm in python3.

## GHS algorithm

The GHS algorithm of Gallager, Humblet and Spira is one of the best-known algorithms in distributed computing theory. This algorithm can construct the minimum spanning tree in asynchronous Message-passing model.

- The algorithm should run on a connected undirected graph.
- The graph should have distinct finite weights assigned to each edge.

For more details about GHS [click here](https://en.wikipedia.org/wiki/Distributed_minimum_spanning_tree#GHS_algorithm).

## How to run

1. First clone this repository.
2. Put desired graph data in a txt file with the correct format as instructed below
3. Run the program using `Main.py "input file"` (e.g. `Main.py "input.txt"`)

When finished, each node prints it's neighbours that their common edge is a branch in the MST.

## Input format

Each edge have a weight and a delay parameter.

Each line represents one edge of the graph in the following format:

- `<source_nid> <destination_nid> <weight> <delay>`

A sample input is available in "`input.txt`" which it's representation is shown below.
![input graph](https://github.com/amir-ni/GHS-MST/blob/master/input.png?raw=true)
