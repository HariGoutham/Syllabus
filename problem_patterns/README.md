# 🚀 LeetCode Problem-Solving Patterns

Welcome to the **LeetCode Problem-Solving Patterns** repository! This guide provides a comprehensive list of common patterns and techniques for tackling problems on LeetCode and similar competitive programming platforms. Mastering these patterns can significantly enhance your problem-solving skills and efficiency. Let's dive in! 🌊

---

## 📚 Patterns for LeetCode Problems

### 1. Two-Pointer Technique
- **Description**: Used for problems involving arrays and linked lists, especially for finding pairs or subarrays.
- **Example Problems**: 
  - [15. 3Sum](https://leetcode.com/problems/3sum/)
  - [11. Container With Most Water](https://leetcode.com/problems/container-with-most-water/)

---

### 2. Sliding Window Technique
- **Description**: Useful for problems involving contiguous subarrays or substrings, particularly for finding the maximum/minimum or counting elements.
- **Example Problems**: 
  - [3. Longest Substring Without Repeating Characters](https://leetcode.com/problems/longest-substring-without-repeating-characters/)
  - [76. Minimum Window Substring](https://leetcode.com/problems/minimum-window-substring/)

---

### 3. Fast and Slow Pointer
- **Description**: Cycle detection method with O(1) space efficiency, commonly used in linked list problems.
- **Example Problems**: 
  - [142. Linked List Cycle II](https://leetcode.com/problems/linked-list-cycle-ii/)

---

### 4. Depth-First Search (DFS)
- **Description**: Commonly used in tree and graph traversal problems, as well as for problems that require exploring all possibilities (e.g., backtracking).
- **Example Problems**: 
  - [104. Maximum Depth of Binary Tree](https://leetcode.com/problems/maximum-depth-of-binary-tree/)
  - [200. Number of Islands](https://leetcode.com/problems/number-of-islands/)

---

### 5. Breadth-First Search (BFS)
- **Description**: Often applied in shortest path problems in graphs, level-order traversal in trees, and problems requiring exploration of all nodes at the present depth prior to moving on to nodes at the next depth level.
- **Example Problems**: 
  - [102. Binary Tree Level Order Traversal](https://leetcode.com/problems/binary-tree-level-order-traversal/)
  - [542. 01 Matrix](https://leetcode.com/problems/01-matrix/)

---

### 6. Backtracking
- **Description**: Used for problems involving permutations, combinations, and subsets, as well as constraint satisfaction problems (e.g., N-Queens, Sudoku).
- **Example Problems**: 
  - [46. Permutations](https://leetcode.com/problems/permutations/)
  - [51. N-Queens](https://leetcode.com/problems/n-queens/)

---

### 7. Dynamic Programming (DP)
- **Description**: Key for optimization problems, especially those that can be broken down into overlapping subproblems.
  - **Types**:
    - **1D DP** (e.g., Fibonacci sequence, climbing stairs)
    - **2D DP** (e.g., longest common subsequence, knapsack)
    - **DP with Bitmasking** (e.g., traveling salesman problem)
- **Example Problems**: 
  - [70. Climbing Stairs](https://leetcode.com/problems/climbing-stairs/)
  - [300. Longest Increasing Subsequence](https://leetcode.com/problems/longest-increasing-subsequence/)

---

### 8. Greedy Algorithms
- **Description**: Applied in optimization problems where local optimal choices lead to a global optimum (e.g., interval scheduling, coin change).
- **Example Problems**: 
  - [455. Assign Cookies](https://leetcode.com/problems/assign-cookies/)
  - [621. Task Scheduler](https://leetcode.com/problems/task-scheduler/)

---

### 9. Binary Search
- **Description**: Useful for searching in sorted arrays or for problems that can be transformed into a search space (e.g., finding the smallest or largest element that meets a condition).
- **Example Problems**: 
  - [704. Binary Search](https://leetcode.com/problems/binary-search/)
  - [33. Search in Rotated Sorted Array](https://leetcode.com/problems/search-in-rotated-sorted-array/)

---

### 10. Modified Binary Search
- **Description**: Search in variations of binary search problems, such as rotated or specialized arrays.
- **Example Problems**: 
  - [33. Search in Rotated Sorted Array](https://leetcode.com/problems/search-in-rot ated-sorted-array/)

---

### 11. Topological Sort
- **Description**: Used in problems involving directed acyclic graphs (DAGs), particularly for scheduling tasks or resolving dependencies.
- **Example Problems**: 
  - [207. Course Schedule](https://leetcode.com/problems/course-schedule/)
  - [210. Course Schedule II](https://leetcode.com/problems/course-schedule-ii/)

---

### 12. Bit Manipulation
- **Description**: Useful for problems involving subsets, unique numbers, or when optimizing space and time (e.g., finding the single number in an array).
- **Example Problems**: 
  - [136. Single Number](https://leetcode.com/problems/single-number/)
  - [190. Reverse Bits](https://leetcode.com/problems/reverse-bits/)

---

### 13. Bitwise XOR
- **Description**: Toggle bits operation, efficient for pairing and finding unique elements.
- **Example Problems**: 
  - [136. Single Number](https://leetcode.com/problems/single-number/)

---

### 14. Mathematical Patterns
- **Description**: Includes techniques for prime number generation (Sieve of Eratosthenes), GCD/LCM calculations, and combinatorial problems.
- **Example Problems**: 
  - [204. Count Primes](https://leetcode.com/problems/count-primes/)
  - [29. Divide Two Integers](https://leetcode.com/problems/divide-two-integers/)

---

### 15. String Manipulation Patterns
- **Description**: Commonly used for substring search problems, anagrams, palindromes, and regular expression matching.
- **Example Problems**: 
  - [5. Longest Palindromic Substring](https://leetcode.com/problems/longest-palindromic-substring/)
  - [49. Group Anagrams](https://leetcode.com/problems/group-anagrams/)

---

### 16. Graph Traversal Patterns
- **Description**: Techniques for exploring graphs, including:
  - **Union-Find** (for connected components)
  - **Dijkstra's Algorithm** (for shortest paths)
  - **Floyd-Warshall** (for all pairs shortest paths)
- **Example Problems**: 
  - [547. Number of Provinces](https://leetcode.com/problems/number-of-provinces/)
  - [787. Cheapest Flights Within K Stops](https://leetcode.com/problems/cheapest-flights-within-k-stops/)

---

### 17. Interval Problems
- **Description**: Patterns for merging intervals, finding overlaps, and scheduling tasks.
- **Example Problems**: 
  - [56. Merge Intervals](https://leetcode.com/problems/merge-intervals/)
  - [57. Insert Interval](https://leetcode.com/problems/insert-interval/)

---

### 18. Matrix Traversal Patterns
- **Description**: Techniques for traversing 2D matrices, such as spiral order traversal or flood fill.
- **Example Problems**: 
  - [54. Spiral Matrix](https://leetcode.com/problems/spiral-matrix/)
  - [733. Flood Fill](https://leetcode.com/problems/flood-fill/)

---

### 19. Islands (Matrix Traversal)
- **Description**: DFS/BFS traversal for connected component detection in 2D grid problems.
- **Example Problems**: 
  - [200. Number of Islands](https://leetcode.com/problems/number-of-islands/)

---

### 20. Two Heaps
- **Description**: Max and min heaps for efficiently tracking the median.
- **Example Problems**: 
  - [295. Find Median from Data Stream](https://leetcode.com/problems/find-median-from-data-stream/)

---

### 21. Cyclic Sort
- **Description**: Sorting in cycles with O(n) time complexity and constant space usage.
- **Example Problems**: 
  - [287. Find the Duplicate Number](https://leetcode.com/problems/find-the-duplicate-number/)

---

### 22. In-place Reversal of Linked List
- **Description**: Reverse a linked list without extra space.
- **Example Problems**: 
  - [206. Reverse Linked List](https://leetcode.com/problems/reverse-linked-list/)

---

### 23. Top 'K' Elements
- **Description**: Use heap or quickselect for efficient selection problems.
- **Example Problems**: 
  - [215. Kth Largest Element in an Array](https://leetcode.com/problems/kth-largest-element-in-an-array/)

---

### 24. K-way Merge
- **Description**: Merge k sorted lists using a min-heap.
- **Example Problems**: 
  - [23. Merge k Sorted Lists](https://leetcode.com/problems/merge -k-sorted-lists/)

---

### 25. 0/1 Knapsack (Dynamic Programming)
- **Description**: Choose or skip items to maximize value selection.
- **Example Problems**: 
  - [416. Partition Equal Subset Sum](https://leetcode.com/problems/partition-equal-subset-sum/)

---

### 26. Unbounded Knapsack (Dynamic Programming)
- **Description**: Unlimited item choices for multiple item selection.
- **Example Problems**: 
  - [322. Coin Change](https://leetcode.com/problems/coin-change/)

---

### 27. Monotonic Stack
- **Description**: Maintain an increasing or decreasing stack for optimized range queries.
- **Example Problems**: 
  - [739. Daily Temperatures](https://leetcode.com/problems/daily-temperatures/)

---

## 🎉 Conclusion

By mastering these patterns, you can improve your problem-solving skills and tackle a wide range of challenges on LeetCode and other competitive programming platforms. Happy coding! 💻✨

--- 

Feel free to customize this README further to match your style or add any additional sections that you think would be beneficial!
