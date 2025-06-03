# 07. Graphs and Graph Theory

---

## What is a Graph?

A **graph** is a mathematical structure consisting of a set of vertices (nodes) and a set of edges (connections) between pairs of vertices. Graphs model networks, relationships, and structures in computer science, math, and real life.

---

## Types of Graphs

- **Undirected Graph:** Edges have no direction.
- **Directed Graph (Digraph):** Edges have direction (arrows).
- **Weighted Graph:** Edges have associated weights (costs, distances).
- **Simple Graph:** No loops or multiple edges.
- **Multigraph:** Multiple edges between same vertices allowed.
- **Complete Graph (Kₙ):** Every pair of distinct vertices is connected.
- **Bipartite Graph:** Vertices can be divided into two sets with edges only between sets.

---

## Basic Terminology

- **Vertex (Node):** Fundamental unit.
- **Edge (Arc):** Connection between two vertices.
- **Degree:** Number of edges incident to a vertex.
- **Path:** Sequence of edges connecting vertices.
- **Cycle:** Path that starts and ends at the same vertex.
- **Connected Graph:** Path exists between every pair of vertices.
- **Component:** Maximal connected subgraph.
- **Subgraph:** A graph formed from a subset of vertices/edges.

---

## Special Graphs

- **Tree:** Connected acyclic undirected graph.
- **Forest:** Disjoint union of trees.
- **Planar Graph:** Can be drawn without crossing edges.
- **Complete Bipartite (Kₘ,ₙ):** Every vertex in one set connects to all in the other.

---

## Representation of Graphs

- **Adjacency Matrix:** 2D array; O(n²) space.
- **Adjacency List:** List for each vertex; efficient for sparse graphs.

---

## Graph Traversals

- **Breadth-First Search (BFS):** Explores neighbors level by level.
- **Depth-First Search (DFS):** Follows a path as deep as possible before backtracking.

---

## Applications

- Social networks (friends graph)
- Web page links (WWW)
- Routing and networking
- Scheduling and dependency resolution
- Game theory and puzzles

---

## Graph Properties

- **Eulerian Path/Circuit:** Visits every edge exactly once.
- **Hamiltonian Path/Circuit:** Visits every vertex exactly once.
- **Connectivity:** Graph is connected if all nodes can be reached.
- **Cut-vertex/bridge:** Removing disconnects the graph.

---

## Graph Algorithms

- **Shortest Path:** Dijkstra’s, Bellman-Ford
- **Minimum Spanning Tree:** Kruskal’s, Prim’s
- **Connected Components:** DFS/BFS
- **Topological Sort:** Order vertices in a DAG (Directed Acyclic Graph)

---

## Coloring and Planarity

- **Graph Coloring:** Assign colors to vertices so that adjacent vertices differ.
- **Planar Graphs:** Kuratowski’s theorem.

---

## Interview Patterns

- Represent a graph by adjacency matrix/list.
- Find connected components.
- Design BFS/DFS traversal.
- Detect cycles, find shortest paths.

---

## Exercises

1. Draw the adjacency matrix and list for a simple undirected graph.
2. Use BFS to traverse a graph and record visit order.
3. Prove that every tree with n vertices has n−1 edges.
4. Implement Dijkstra’s algorithm for shortest path.
5. Show that K₅ is not planar.

---

## Key Interview Questions

- What is the difference between BFS and DFS?
- How is a graph represented in memory?
- What is a spanning tree?
- Define Eulerian and Hamiltonian paths with examples.

---

## References

- [Rosen, Discrete Mathematics, Ch. 10](https://www.mheducation.com/highered/product/discrete-mathematics-its-applications-rosen/M9780073383095.html)
- [GeeksforGeeks - Graph Theory](https://www.geeksforgeeks.org/graph-data-structure-and-algorithms/)
- [Brilliant - Graph Theory](https://brilliant.org/wiki/graph-theory/)
- [MIT OCW 6.042J Graphs](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-fall-2010/resources/lecture-notes/MIT6_042JF10_lec17.pdf)
- [Wikipedia: Graph (Discrete Mathematics)](https://en.wikipedia.org/wiki/Graph_(discrete_mathematics))

---
