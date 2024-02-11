# Tower of Hanoi Solver
### Problem Description:

The Tower of Hanoi is a well-known problem in computer science. Given n disks and 3 pegs, the goal is to move all the disks from one peg to another following these rules:

1. Only one disk can be moved at a time.
   
2. A disk can only be placed on top of a larger disk or an empty peg.

In this repository, we explore the Tower of Hanoi challenge. We represent each configuration of disks as a vector, where each position corresponds to a peg. The legal movements between configurations create a graph. Each vertex represents a different configuration, and edges connect configurations that can be reached by moving a single disk.

### Key Features:
* Model the graph of Tower of Hanoi moves for 4 disks using an adjacency matrix.
* Implement the Ford-Moore-Bellman Algorithm to find the shortest path from a given configuration to the final result.
* Assign a value of 1 to each edge in the graph.
  
Feel free to explore the code and contribute to solving this classic puzzle!

![image](https://github.com/Lucaspm5/Hanoi-tower/assets/125845662/9311957d-b816-4357-970f-a47d89ed1891)
