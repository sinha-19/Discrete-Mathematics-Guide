# 08. Trees and Tree Algorithms

---

## What is a Tree?

A **tree** is a connected acyclic undirected graph. It's a hierarchical structure with a single root and nodes connected by edges, used extensively in computer science.

---

## Basic Terminology

- **Root:** Topmost node.
- **Leaf:** Node with no children.
- **Parent/Child:** Direct relationship.
- **Sibling:** Nodes with the same parent.
- **Ancestor/Descendant:** Indirect relationships.
- **Height/Depth/Level:** Distance from root.
- **Subtree:** Tree formed by a node and its descendants.

---

## Properties of Trees

- For n nodes, a tree has n−1 edges.
- Only one path exists between any two nodes.
- Removing any edge disconnects the tree.

---

## Types of Trees

- **Binary Tree:** Each node has ≤2 children.
- **Full Binary Tree:** Every node has 0 or 2 children.
- **Complete Binary Tree:** All levels full except possibly last, filled left to right.
- **Perfect Binary Tree:** All levels fully filled.
- **Binary Search Tree (BST):** Left child < parent < right child.
- **AVL Tree:** Self-balancing BST.
- **B-Tree:** Multi-way search tree (used in databases).
- **Trie:** Prefix tree (used in string algorithms).

---

## Tree Traversals

- **Preorder:** Visit root, left, right.
- **Inorder:** Visit left, root, right.
- **Postorder:** Visit left, right, root.
- **Level-order:** Visit nodes level by level (BFS).

---

## Applications

- Hierarchical data (file systems, organization charts)
- Expression trees (parsing arithmetic expressions)
- Search and sorting (BST, heaps)
- Huffman encoding (data compression)
- Decision trees (AI, ML)

---

## Tree Algorithms

- **Insertion, Deletion:** In BSTs, maintain ordering.
- **Balancing:** AVL and Red-Black trees.
- **Heap Operations:** Insert, delete-min/max for priority queues.
- **Lowest Common Ancestor (LCA):** Find ancestor of two nodes.
- **Tree Diameter:** Longest path between any two nodes.

---

## Spanning Trees

- **Spanning Tree:** A subgraph that is a tree and includes all vertices.
- **Minimum Spanning Tree (MST):** Spanning tree with minimum total edge weight.
- **Algorithms:** Kruskal’s, Prim’s

---

## Interview Patterns

- Traverse a tree in different orders.
- Implement BST insert/delete.
- Find tree height/leaf count.
- Build Huffman tree from frequencies.

---

## Exercises

1. Draw a BST for the sequence [7, 3, 9, 2, 5, 8].
2. Traverse a tree in preorder, inorder, postorder.
3. Balance a tree after insertion.
4. Construct a Huffman tree for given frequencies.
5. Find height and number of leaves in a binary tree.

---

## Key Interview Questions

- What is the difference between tree and graph?
- Explain tree traversals with examples.
- How does AVL tree maintain balance?
- Where are tries used?

---

## References

- [Rosen, Discrete Mathematics, Ch. 11](https://www.mheducation.com/highered/product/discrete-mathematics-its-applications-rosen/M9780073383095.html)
- [GeeksforGeeks - Tree Data Structure](https://www.geeksforgeeks.org/binary-tree-data-structure/)
- [Brilliant - Trees](https://brilliant.org/wiki/trees/)
- [MIT OCW 6.042J Trees](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-fall-2010/resources/lecture-notes/MIT6_042JF10_lec18.pdf)
- [Wikipedia: Tree (Data Structure)](https://en.wikipedia.org/wiki/Tree_(data_structure))

---
