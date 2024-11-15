# Algorithms in DP

* [1. <strong>Fibonacci Sequence</strong>](#1-fibonacci-sequence)
* [2. <strong>Knapsack Problems</strong>](#2-knapsack-problems)
* [3. <strong>Longest Increasing Subsequence (LIS)</strong>](#3-longest-increasing-subsequence-lis)
* [4. <strong>Longest Common Subsequence (LCS)</strong>](#4-longest-common-subsequence-lcs)
* [5. <strong>Matrix Chain Multiplication</strong>](#5-matrix-chain-multiplication)
* [6. <strong>Rod Cutting Problem</strong>](#6-rod-cutting-problem)
* [7. <strong>Coin Change Problem</strong>](#7-coin-change-problem)
* [8. <strong>Edit Distance (Levenshtein Distance)</strong>](#8-edit-distance-levenshtein-distance)
* [9. <strong>Subset Sum Problem</strong>](#9-subset-sum-problem)
* [10. <strong>Longest Palindromic Subsequence</strong>](#10-longest-palindromic-subsequence)
* [11. <strong>Palindrome Partitioning</strong>](#11-palindrome-partitioning)
* [12. <strong>String Matching and Pattern Matching</strong>](#12-string-matching-and-pattern-matching)
* [13. <strong>Traveling Salesman Problem (TSP)</strong>](#13-traveling-salesman-problem-tsp)
* [14. <strong>Maximum Subarray Sum (Kadane’s Algorithm)</strong>](#14-maximum-subarray-sum-kadanes-algorithm)
* [15. <strong>Minimum Path Sum in Grid</strong>](#15-minimum-path-sum-in-grid)
* [16. <strong>Unique Paths Problem</strong>](#16-unique-paths-problem)
* [17. <strong>Binomial Coefficients</strong>](#17-binomial-coefficients)
* [18. <strong>Dynamic Programming on Trees</strong>](#18-dynamic-programming-on-trees)
* [19. <strong>KnapSack Problem with Multiple Items</strong>](#19-knapsack-problem-with-multiple-items)
* [20. <strong>Bellman-Ford Algorithm</strong>](#20-bellman-ford-algorithm)
* [21. <strong>Floyd-Warshall Algorithm</strong>](#21-floyd-warshall-algorithm)
* [22. <strong>Weighted Interval Scheduling</strong>](#22-weighted-interval-scheduling)
* [23. <strong>Stock Buy and Sell Problem</strong>](#23-stock-buy-and-sell-problem)
* [24. <strong>House Robber Problem</strong>](#24-house-robber-problem)
* [25. <strong>Word Break Problem</strong>](#25-word-break-problem)
* [26. <strong>Maximum Length of Pair Chain</strong>](#26-maximum-length-of-pair-chain)
* [27. <strong>Subset Partition Problem</strong>](#27-subset-partition-problem)
* [28. <strong>Maximum Product Subarray</strong>](#28-maximum-product-subarray)
* [29. <strong>Count Palindromic Substrings</strong>](#29-count-palindromic-substrings)
* [30. <strong>Word Ladder</strong>](#30-word-ladder)
* [31. <strong>Interval Scheduling Maximization</strong>](#31-interval-scheduling-maximization)
* [32. <strong>Knapsack with Multiple Constraints</strong>](#32-knapsack-with-multiple-constraints)
* [33. <strong>Maximum Flow/Minimum Cut (Ford-Fulkerson)</strong>](#33-maximum-flowminimum-cut-ford-fulkerson)
* [34. <strong>Binary Search with DP (Binary DP)</strong>](#34-binary-search-with-dp-binary-dp)
* [Summary:](#summary)
Here is a comprehensive list of **Dynamic Programming (DP) algorithms** with a brief explanation of each:

### 1. **Fibonacci Sequence**

- **Problem**: Find the nth Fibonacci number.
- **Explanation**: The Fibonacci sequence is a classic DP problem, where each term is the sum of the two preceding ones.
- **Variants**:
    - Fibonacci number using memoization or tabulation.
    - Fibonacci number with space optimization.

### 2. **Knapsack Problems**

- **0/1 Knapsack**: Given weights and values of items, and a knapsack with a capacity, determine the maximum value that can be carried in the knapsack.
- **Unbounded Knapsack**: A variation where items can be chosen multiple times.
- **Subset Sum Problem**: Given a set of integers, find if there is a subset that sums to a specific target.
- **Partition Problem**: Determine if a set can be partitioned into two subsets with equal sum.

### 3. **Longest Increasing Subsequence (LIS)**

- **Problem**: Given an array of integers, find the length of the longest increasing subsequence.
- **Variants**:
    - LIS with binary search for optimization.
    - Find the actual subsequence using backtracking.

### 4. **Longest Common Subsequence (LCS)**

- **Problem**: Given two strings, find the length of the longest subsequence that appears in both strings.
- **Variants**:
    - LCS with three strings.
    - LCS with wildcard characters or regular expressions.

### 5. **Matrix Chain Multiplication**

- **Problem**: Given a sequence of matrices, find the most efficient way to multiply them in terms of scalar multiplications.
- **Explanation**: The goal is to parenthesize the matrix product to minimize the cost.

### 6. **Rod Cutting Problem**

- **Problem**: Given a rod of length `n` and prices for lengths `1` to `n`, find the maximum profit obtainable by cutting the rod into pieces.
- **Explanation**: This is a standard DP problem where you need to decide how to cut the rod to maximize the total revenue.

### 7. **Coin Change Problem**

- **Min Coins Problem**: Given coin denominations and a target sum, find the minimum number of coins needed to make the sum.
- **Number of Ways to Make Change**: Count the number of ways to make the target sum using given coin denominations.

### 8. **Edit Distance (Levenshtein Distance)**

- **Problem**: Given two strings, find the minimum number of insertions, deletions, or substitutions needed to transform one string into the other.

### 9. **Subset Sum Problem**

- **Problem**: Given a set of integers, find if there is a subset of the integers whose sum equals a given target value.

### 10. **Longest Palindromic Subsequence**

- **Problem**: Given a string, find the longest subsequence that is a palindrome.
- **Variants**:
    - Minimum number of deletions to make a string palindrome.

### 11. **Palindrome Partitioning**

- **Problem**: Given a string, partition it into the fewest number of palindromic substrings.
- **Explanation**: The task is to minimize the number of cuts needed to split the string into palindromes.

### 12. **String Matching and Pattern Matching**

- **Knuth-Morris-Pratt (KMP) Algorithm**: Efficient string matching.
- **Z-Algorithm**: Finding substring matches.
- **Rabin-Karp Algorithm**: Hashing-based string matching.

### 13. **Traveling Salesman Problem (TSP)**

- **Problem**: Given a set of cities, find the shortest possible route that visits each city exactly once and returns to the origin city.
- **Variants**:
    - Dynamic Programming approach with bitmasking.

### 14. **Maximum Subarray Sum (Kadane’s Algorithm)**

- **Problem**: Given an array of integers, find the contiguous subarray with the largest sum.
- **Variants**:
    - Maximum sum subsequence with no adjacent elements.

### 15. **Minimum Path Sum in Grid**

- **Problem**: Given a grid with obstacles, find the minimum path sum from the top-left corner to the bottom-right corner, where only right and down moves are allowed.

### 16. **Unique Paths Problem**

- **Problem**: Given a grid, find the number of unique paths from the top-left corner to the bottom-right corner, considering obstacles.

### 17. **Binomial Coefficients**

- **Problem**: Compute the binomial coefficient C(n, k) using DP.

### 18. **Dynamic Programming on Trees**

- **Problem**: DP techniques applied to tree-based problems such as:
    - Diameter of a tree.
    - Counting paths.
    - Maximum weight independent set in a tree.

### 19. **KnapSack Problem with Multiple Items**

- **Problem**: A variant of the 0/1 knapsack where you can use items multiple times but within a limited count.

### 20. **Bellman-Ford Algorithm**

- **Problem**: Used to find the shortest paths from a single source vertex to all other vertices in a graph, especially with negative weight edges.
- **Variants**:
    - Detecting negative weight cycles.

### 21. **Floyd-Warshall Algorithm**

- **Problem**: All pairs shortest path problem in a graph.
- **Explanation**: It calculates the shortest paths between all pairs of nodes in a graph.

### 22. **Weighted Interval Scheduling**

- **Problem**: Given intervals with weights, find the maximum weight subset of non-overlapping intervals.

### 23. **Stock Buy and Sell Problem**

- **Problem**: Given stock prices for `n` days, find the maximum profit that can be obtained by buying and selling the stock.

### 24. **House Robber Problem**

- **Problem**: Given a list of non-negative integers representing the amount of money of each house, determine the maximum amount of money that can be robbed without robbing two adjacent houses.

### 25. **Word Break Problem**

- **Problem**: Given a string and a dictionary of words, determine if the string can be segmented into words from the dictionary.

### 26. **Maximum Length of Pair Chain**

- **Problem**: Given pairs of integers, find the longest chain that can be formed where the second element of a pair is greater than the first element of the next pair.

### 27. **Subset Partition Problem**

- **Problem**: Given a set, determine if it can be partitioned into two subsets with equal sum.

### 28. **Maximum Product Subarray**

- **Problem**: Given an integer array, find the contiguous subarray with the maximum product.

### 29. **Count Palindromic Substrings**

- **Problem**: Given a string, count the number of palindromic substrings.

### 30. **Word Ladder**

- **Problem**: Find the shortest transformation sequence from a start word to an end word, changing only one letter at a time, such that each transformed word must exist in a dictionary.

### 31. **Interval Scheduling Maximization**

- **Problem**: Given a set of intervals with start and end times, find the maximum number of non-overlapping intervals.

### 32. **Knapsack with Multiple Constraints**

- **Problem**: Solve knapsack-like problems that involve multiple constraints such as volume, weight, and value, etc.

### 33. **Maximum Flow/Minimum Cut (Ford-Fulkerson)**

- **Problem**: A network flow algorithm used to find the maximum flow in a flow network.

### 34. **Binary Search with DP (Binary DP)**

- **Problem**: Binary DP is useful when solving problems with optimizable monotonic subproblems that can be solved using binary search.

---

### Summary:

These are the most important dynamic programming algorithms used in competitive programming and interview preparation. Understanding these problems and their variants will greatly improve your problem-solving skills and allow you to tackle complex challenges in a more efficient manner.

The core of DP is recognizing when a problem can be broken down into overlapping subproblems, and using either **top-down** (memoization) or **bottom-up** (tabulation) approaches to solve them efficiently.
