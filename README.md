# SC2001-Algorithm-Design-and-Analysis
NTU AY2023/2024 Semester 1 | SC2001/CE2101/CZ2101 Algorithm Design and Analysis | Example Classes
All details and specifications of the 3 Example Classes were provided as the assignment released by the NTU AY23/24 SC2001 Coordinator Team.

## Description
This respository consists of 3 Example Classes that explore different topics in Algorithm Design and Analysis. The contents include our code implementations and presentation slides for each example class. Within each example class, we have incorporated supplementary points of interest that emerged during our research. A brief rundown of each example class assignment is given below:

### Example Class 1: Integration of Mergesort & Insertion Sort
This project entails the implementation and analysis of a **hybrid sorting algorithm** that combines **Mergesort** with **Insertion Sort** to enhance efficiency. The idea is to set a small integer `S` as a threshold for the size of subarrays, where the algorithm will switch from **Mergesort** to **Insertion Sort**. We are tasked to: 
+ Implement the algorithm
+ Generate input data of increasing sizes `n`
+ Analyse time complexity and compare empirical results with the theoretical analysis, in these cases
  + fixed value of `S`, vary value of `n`
  + fixed value of `n`, vary value of `S`
  + determine optimal value of `S`
+ Compare **hybrid algorithm** using optimal `S` value with **original MergeSort** with 10 million integers

### Example Class 2: The Dijkstra’s Algorithm
This project entails the implementation and analysis of Dijkstra's algorithm under different graph representations and priority queue implementations. We analyse the time complexity with respect to `|V|` and `|E|` both **theoretically** and **empirically** for both implementations of the Dijkstra's algorithm:
+ Graph stored as an **adjacency matrix** and **array** for priority queue
+ Graph stored as an **adjacency list** and **minimizing heap** for priority queue
We then compare these 2 implementations and identify circumstances where one proves more advantageous than the other.

### Example Class 3:  Dynamic Programming
This problem involves finding the maximum total profit for a knapsack of capacity C and n types of objects, where each object has a weight wi and profit pi. The goal is to determine the largest profit achievable while considering unlimited supplies of each object type. We are tasked to:
+ Give a **recursive definition** of the function P(C)
+ Draw the **subproblem graph** for P(14) where n is 3 with the weights and profits provided
+ Implement a **dynamic programming algorithm** to compute the maximum profit, given a knapsack of capacity C, n types of objects with weights wi and profits pi using the **bottom up approach**.
+ Show the **running results** of P(14) with the 2 sets of weights and profits provided

## How to run
To run the code, simply download the files into your local drive and open them using your preferred IDE (e.g. Jupyter Notebook). Run all the cells and view the results!
### Notes
- If you encounter any issues during the setup or have questions, feel free to reach out for assistance.
- Results may vary from run to run.

## Team Members
We are group 1 of lab group SDAC
| Name | GitHub ID |
| -----|-----------|
| Brandon Jang Jin Tian | @BrandonJang |
| Goh Anna, Ninette | - |
| Keith Lim En Kai | - |
| Tee Qin Tong Bettina | @BettinaTee03 |
