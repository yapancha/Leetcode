# Data Structures and Algorithms Reference Guide

## Data Structures

1. **Array:**
   - **Usage Scenarios:** 
     - Need for contiguous block of memory for storing elements.
     - Constant-time access to elements using indices.
     - Known or dynamically changing size of the collection.

2. **Linked List:**
   - **Usage Scenarios:** 
     - Dynamic data structure for efficient insertion and deletion.
     - Avoidance of resizing arrays and shifting elements.
     - Simple implementation of stacks, queues, or other ADTs.

3. **Stack:**
   - **Usage Scenarios:** 
     - Implementation of last-in-first-out (LIFO) behavior.
     - Tracking function calls, nested structures, or depth-first traversal.
     - Balancing parentheses, evaluating postfix expressions, or undo-redo functionality.

4. **Queue:**
   - **Usage Scenarios:** 
     - Implementation of first-in-first-out (FIFO) behavior.
     - Modeling real-world scenarios like task scheduling or breadth-first traversal.
     - Maintaining a strict insertion and removal order.

5. **Binary Tree:**
   - **Usage Scenarios:** 
     - Representation of hierarchical relationships between elements.
     - Efficient search, insertion, deletion, and traversal operations.
     - Implementation of binary search trees or expression trees.

6. **Binary Search Tree (BST):**
   - **Usage Scenarios:** 
     - Dynamic data structure for efficient searching, insertion, and deletion.
     - Maintenance of elements in sorted order and performing range queries.
     - Implementation of sets, maps, or priority queues.

7. **Heap (Priority Queue):**
   - **Usage Scenarios:** 
     - Efficient retrieval of the maximum or minimum element from a collection.
     - Maintenance of a partially sorted data structure.
     - Implementation of priority queues or scheduling algorithms.

8. **Hash Table (HashMap, HashSet):**
   - **Usage Scenarios:** 
     - Fast insertion, deletion, and lookup operations with constant-time complexity on average.
     - Storage of key-value pairs or maintenance of a set of unique elements.
     - Implementation of caches, frequency counters, or duplicate checking.

9. **Trie:**
   - **Usage Scenarios:** 
     - Efficient storage and retrieval of a large collection of strings.
     - Prefix-based searches or autocomplete functionality.
     - Implementation of dictionaries, spell checkers, or IP routing tables.

## Algorithms

1. **Sorting Algorithms:**
   - **Usage Scenarios:** 
     - Arranging elements in a specific order.
     - Finding the k-th smallest/largest element in an array.
     - Identifying maximum or minimum elements in a collection.

2. **Searching Algorithms:**
   - **Usage Scenarios:** 
     - Finding a specific element or value within a collection.
     - Locating elements in sorted arrays or lists.
     - Determining presence or absence of an element in a data structure.

3. **Tree and Graph Algorithms:**
   - **Usage Scenarios:** 
     - Hierarchical or interconnected data structures.
     - Traversal of trees or graphs to search for specific nodes or paths.
     - Analyzing relationships between entities represented by nodes and edges.

4. **Dynamic Programming:**
   - **Usage Scenarios:** 
     - Optimization problems with overlapping subproblems.
     - Solving problems by combining solutions to smaller subproblems.
     - Avoiding redundant computation in recursive structures.

5. **Greedy Algorithms:**
   - **Usage Scenarios:** 
     - Problems exhibiting greedy choice property.
     - Series of locally optimal choices leading to globally optimal solutions.
     - Finding approximate solutions close enough for practical purposes.

6. **Backtracking:**
   - **Usage Scenarios:** 
     - Exploring all possible solutions in a search space.
     - Systematically generating and testing candidate solutions.
     - Reducing problems to sequences of choices made in a recursive manner.

7. **String Algorithms:**
   - **Usage Scenarios:** 
     - Manipulation or analysis of strings of characters.
     - Searching for patterns or substrings within a larger string.
     - Comparing or aligning two strings based on specific criteria.

8. **Graph Algorithms:**
   - **Usage Scenarios:** 
     - Modeling relationships between entities using nodes and edges.
     - Analyzing networks, transportation systems, or social graphs.
     - Finding paths, cycles, or connectivity properties within a graph.

9. **Miscellaneous Algorithms:**
   - **Usage Scenarios:** 
     - Breaking down complex tasks into simpler operations.
     - Performing low-level operations on binary representations of data.
     - Mathematical calculations or computations required for problem-solving.

## Decision Patterns

- **If the question asks for efficient insertion and deletion operations:**
  - Use Linked List.

- **If the question requires last-in-first-out (LIFO) behavior:**
  - Use Stack.

- **If the question involves first-in-first-out (FIFO) behavior:**
  - Use Queue.

- **If the question involves searching for specific elements:**
  - Use Binary Search Tree (BST).

- **If the question involves retrieving the maximum or minimum element:**
  - Use Heap (Priority Queue).

- **If the question requires constant-time insertion, deletion, and lookup operations:**
  - Use Hash Table (HashMap, HashSet).

- **If the question involves storing and retrieving a large collection of strings:**
  - Use Trie.

- **If the question involves arranging elements in a specific order:**
  - Use Sorting Algorithms.

- **If the question involves searching for specific elements within a collection:**
  - Use Searching Algorithms.

- **If the question involves analyzing hierarchical or interconnected data structures:**
  - Use Tree and Graph Algorithms.

- **If the question involves optimization problems with overlapping subproblems:**
  - Use Dynamic Programming.

- **If the question involves making locally optimal choices leading to a globally optimal solution:**
  - Use Greedy Algorithms.

- **If the question involves exploring all possible solutions in a search space:**
  - Use Backtracking.

- **If the question involves manipulating or analyzing strings of characters:**
  - Use String Algorithms.

- **If the question involves modeling relationships between entities using nodes and edges:**
  - Use Graph Algorithms.

- **If the question involves performing low-level operations on binary representations of data:**
  - Use Miscellaneous Algorithms.


### Problem Solving with Data Structures and Algorithms

This repository provides a systematic approach to solving problems using data structures and algorithms. By following the guidelines outlined below, you can efficiently tackle various problem categories and implement robust solutions.

#### 1. Identify Problem Category

Determine the category of the problem, such as sorting, searching, graph traversal, or dynamic programming.

#### 2. Choose Relevant Data Structure

Based on the problem requirements, select the appropriate data structure(s) that best fit the problem scenario. Here's a suggested hierarchy:

- **Linear Data Structures:**
  - Array
  - Linked List
  - Stack
  - Queue
- **Non-linear Data Structures:**
  - Tree
  - Binary Tree
  - Binary Search Tree (BST)
  - Heap (Priority Queue)
  - Trie
  - Hash Table (HashMap, HashSet)
- **Graph Data Structures:**
  - Graph (Directed or Undirected)
  - Graph Adjacency List
  - Graph Adjacency Matrix

#### 3. Apply Relevant Algorithm(s)

Once the appropriate data structure(s) are chosen, apply the relevant algorithm(s) to solve the problem efficiently. Here's a suggested hierarchy:

- **Sorting Algorithms:**
  - Bubble Sort
  - Selection Sort
  - Insertion Sort
  - Merge Sort
  - Quick Sort
  - Heap Sort
  - Radix Sort
- **Searching Algorithms:**
  - Linear Search
  - Binary Search
- **Tree and Graph Algorithms:**
  - Tree Traversal (Inorder, Preorder, Postorder)
  - Binary Search Tree Operations (Insertion, Deletion, Search)
  - Minimum Spanning Tree (Prim's, Kruskal's)
  - Shortest Path Algorithms (Dijkstra's, Bellman-Ford)
  - Topological Sorting
  - Graph Coloring
  - Depth-First Search (DFS)
  - Breadth-First Search (BFS)
- **Dynamic Programming:**
  - Longest Common Subsequence (LCS)
  - Knapsack Problem
  - Matrix Chain Multiplication
  - Coin Change Problem
  - Edit Distance
  - Fibonacci Series
- **Greedy Algorithms:**
  - Activity Selection
  - Fractional Knapsack
  - Huffman Coding
  - Job Sequencing with Deadlines
  - Minimum Spanning Tree (Prim's, Kruskal's)
  - Shortest Path Algorithms (Dijkstra's)
- **Backtracking:**
  - N-Queens Problem
  - Sudoku Solver
  - Hamiltonian Cycle
  - Subset Sum Problem
  - Knight's Tour Problem
- **String Algorithms:**
  - String Matching (Naive, Rabin-Karp, KMP)
  - Longest Palindromic Substring
  - Longest Common Subsequence (LCS)
  - Edit Distance
  - Pattern Searching (Trie, Aho-Corasick)
- **Miscellaneous Algorithms:**
  - Bit Manipulation
  - Prime Number Generation
  - Power Set Generation
  - Tower of Hanoi
  - Sieve of Eratosthenes

#### 4. Implement and Test

- Implement the chosen data structure(s) and algorithm(s) to solve the problem.
- Test the solution with sample inputs and edge cases to ensure correctness and efficiency.

#### 5. Optimize (if needed)

- Analyze the time and space complexity of the solution.
- Optimize the solution if necessary by refining algorithms or data structures to improve performance.

By following this hierarchy, you can systematically approach and solve a wide range of problems efficiently using appropriate data structures and algorithms.

---
This repository is maintained by [Your Name]. Feel free to contribute or suggest improvements.
