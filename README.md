## **_DESIGN AND ANALYSIS OF ALGORITH LAB_** 

This repository provides implementations of various algorithms across multiple domains—sorting, matrix multiplication, dynamic programming, graph algorithms, and more. Each implementation demonstrates different computational techniques, allowing for in-depth comparison of performance and efficiency across several approaches to the same or similar problems.

## **_LAB-1: Implement the insertion inside iterative and recursive Binary Search Tree (BST) and compare their performance._** 

- **GOAL**: Implementation of both iterative and recursive approaches to inserting elements into a Binary Search Tree. The performance comparison highlights the differences between these two methods.
  
- **ANALYSIS**:Expect similar time complexities but slightly different run times due to function call overhead in recursion.

## **_LAB-2:Implement divide and conquer-based Merge Sort and Quick Sort algorithms and compare their performance for the same set of elements._** 

- **GOAL**: Focuses on two important sorting algorithms: Merge Sort and Quick Sort. By implementing both, we compare their performance when applied to the same dataset.

- **ANALYSIS**:Merge sort is stable and has 𝑂(𝑛log𝑛) worst-case performance, while quick sort is usually faster but can degrade to 𝑂(𝑛2)O(n2) in the worst case.
  
## **_LAB-3:Compare the performance of Strassen's method of matrix multiplication with the traditional way of matrix multiplication._** 

- **GOAL**: Matrix multiplication using Strassen's method and the traditional method, comparing their efficiency for different matrix sizes.

- **ANALYSIS**:Strassen's method is asymptotically faster but might not outperform the traditional approach for smaller matrices due to overhead.

## **_LAB-4: Implement the activity selection problem to get a clear understanding of the greedy approach._** 

- **GOAL**: The activity selection problem is implemented to showcase the greedy algorithm approach, which helps in selecting the maximum number of activities without overlapping.

- **ANALYSIS**:The greedy approach is optimal for this problem and should demonstrate an efficient selection process with O(nlogn) complexity after sorting.

## **_LAB-5: Get a detailed insight of dynamic programming approach by the implementation of Matrix Chain Multiplication problem and see the impact of parenthesis positioning on time requirements for matrix multiplication._**

- **GOAL**:Use dynamic programming to minimize matrix chain multiplication costs by optimal parenthesis placement.Implement matrix chain multiplication using a DP table to store optimal costs.

- **ANALYSIS**:Dynamic programming will significantly reduce redundant computations, showing a clear benefit over naive methods.

## **_LAB-6: Compare the performance of Dijkstra and Bellman ford algorithm for the single source shortest path problem._**

- **GOAL**:Compare Dijkstra and Bellman-Ford algorithms for finding the shortest path from a source vertex by Implementing Dijkstra’s and Bellman-Ford algorithms.

- **ANALYSIS**:Dijkstra’s algorithm is faster for non-negative weights, while Bellman-Ford supports negative weights but with a higher computational cost.

## **_LAB-7: Through 0/1 Knapsack problem, analyze the greedy and dynamic programming approach for the same dataset._**

- **GOAL**:Analyze greedy and DP approaches on the 0/1 Knapsack problem.Implement both greedy and dynamic programming solutions.Compare results and runtime.

- **ANALYSIS**:Greedy may not yield an optimal solution for 0/1 Knapsack, while DP will provide an optimal solution but with higher time complexity.

## **_LAB-8:Implement the sum of subset_**

- **GOAL**: Implement the sum of subset problem to find subsets that meet a target sum.

- **ANALYSIS**:This showcases subset-sum dynamics, ideal for understanding recursive subset generation.

## **_LAB-9:Compare the Backtracking and Branch & Bound Approach by the implementation of 0/1 Knapsack problem. Also compare the performance with dynamic programming approach_**

- **GOAL**:Compare backtracking, branch & bound, and DP approaches for the 0/1 Knapsack problem.

- **ANALYSIS**:DP is typically faster but memory-intensive; branch & bound provides a good balance between speed and optimality.

## **_LAB-10:Compare the performance of Rabin-Karp, Knuth-Morris-Pratt and naive stringmatching algorithms._**

- **GOAL**: Compare Rabin-Karp, Knuth-Morris-Pratt (KMP), and naive string-matching algorithms.Implement all three algorithms and Measures time for each to find patterns in large text samples.

- **ANALYSIS**:KMP generally outperforms naive, and Rabin-Karp is efficient when hashing is effective but may slow down due to hash collisions.
