# CMPS 2200 Recitation 10## Answers

**Name:** Nikhil Modayur
**Name:**_________________________


Place all written answers from `recitation-07.md` here for easier grading.



- **2)** Work(reachable) = O(n + m) for the adjacency list. Each node is visited once, each edge examined at most twice.

- **4)** Worst case we call reachable once. One traversal is enough to check connectivity.

- **5)** Work(connected) = O(n + m) due to single reachable call plus O(1) as overhead.

- **7)** Since the adjacency matrix is n x n, scanning neighbors of a node costs O(n) instead of its degree. Total work is thus O(n^2) since we might need to scan the entire row for each node we discover.
