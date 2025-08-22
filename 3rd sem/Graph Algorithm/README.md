# Project: Spanning Tree for Utility Grid Design

**Course:** MA2105: Graph Algorithm \
**Institution:** Mahindra University \

**[>> View the Full Project Report (PDF) <<](report.pdf)**

---

## Abstract / Summary

This project addresses the fundamental problem of designing and optimizing utility grids by modeling them as weighted graphs. The primary objective is to design an efficient power distribution network for a small town by applying Minimum Spanning Tree (MST) algorithms. We implement and evaluate two cornerstone MST algorithms, Prim's and Kruskal's, to identify the minimum-cost configuration that connects all nodes (houses) while ensuring full connectivity. The report details the methodology, implementation, and a comparative performance analysis of both algorithms.

---

## Team Members

* Amithi Shangari
* Madhav Basur
* Netan Reddy

---

## Key Concepts Covered

* Graph Theory & Weighted Undirected Graphs
* Minimum Spanning Tree 
* Prim's(Greedy, node-based approach) and Kruskal's Algorithm(Greedy, edge-based approach)
* Union-Find Data Structure (for cycle detection)
* Time Complexity Analysis (Dense vs. Sparse Graphs)
* Algorithm Design & Performance Evaluation

---

## Tools & Methods 

* Python: Used for the implementation of Prim's and Kruskal's algorithms and for generating random graphs to assess scalability
* Typst: Used for writing the report

---

## Outcomes & Learnings 

* A key finding from the performance analysis is the trade-off between the two algorithms: Prim's algorithm is more efficient for **dense graphs** (where the number of edges is close to the maximum possible), while Kruskal's algorithm performs better for **sparse graphs**.
* This highlights that the choice of the optimal MST algorithm is highly dependent on the specific structure of the network being designed.

---

## References 

* https://www.researchgate.net/publication/221926621_Power_Restoration_in_Distribution_Network_Using_MST_Algorithms
* https://ebooks.inflibnet.ac.in/csp01/chapter/minimum-spanning-trees-prims-algorithm/
* https://byjus.com/gate/difference-between-prims-and-kruskal-algorithum/
* https://cp-algorithms.com/graph/mst_prim.html
* https://www.javatpoint.com/which-minimum-spanning-tree-algorithm-is-better
