# 🐍 Python Algorithms Collection

Welcome to my Python projects repository! This space features implementations of classic algorithms and various projects in Python, focusing on linear and nonlinear optimization, euristic methods and more!.

---

## 🚀 Featured Projects

### 1. 🛣️ Dijkstra Pathfinding
A high-performance implementation of Dijkstra's algorithm to find the shortest path in weighted graphs.
* **Optimization:** Uses `heapq` (Priority Queue) to achieve a time complexity of $O((E + V) \log V)$.
* **Features:** Includes "Lazy Deletion" for efficient queue management and handles directed graphs via adjacency matrices.
* **Visualization:** Generates clear graph plots using `NetworkX` and `Matplotlib`.
* **Notebook:** [Open dijkstra.ipynb on Colab](https://colab.research.google.com/github/Matthew725234/Python-projects/blob/main/dijkstra.ipynb)

### 2. 🧬 Longest Common Subsequence (LCS)
A robust solution to the LCS problem using **Dynamic Programming**.
* **Method:** Recursive top-down approach with a memoization matrix.
* **Backtracking:** Includes the reconstruction logic to extract the actual string sequence.
* **Efficiency:** $O(m \times n)$ time and space complexity.
* **Notebook:** [Open LCS.ipynb on Colab](https://colab.research.google.com/github/Matthew725234/Python-projects/blob/main/LCS.ipynb)

### 3. 🔐 Genetic Vault Cracker

A simple heuristic optimization algorithm (specifically, a variation of *Random Mutation Hill Climbing*) developed in Python. The goal of this program is to "crack" a 10-digit numerical vault combination by simulating the biological mechanisms of mutation and natural selection.

Instead of trying every single possible combination using a brute-force attack (which would take exponentially longer as the number of digits increases), this script uses an evolutionary approach based on three core pillars:

1. **The Fitness Function:** Evaluates each attempt by comparing it to the correct combination. For every digit guessed in the exact correct position, the fitness score (*grade*) increases by 1.
2. **Random Mutation:** In every cycle, the algorithm takes the best attempt found so far, selects a single digit at random (*lock wheel*), and mutates it into a random number from 0 to 9.
3. **Natural Selection:** If the newly mutated combination achieves a higher fitness score than the current best attempt, it is saved as the new "best guess." Otherwise, it is discarded, and the loop tries again.

The cycle continues until the fitness score reaches the maximum possible value, meaning the full combination has been successfully guessed.
* **Notebook:** [Open genetic_algorithm.ipynb on Colab](https://github.com/Matthew725234/Python-projects/blob/main/genetic_algorithm.ipynb)

## 🛠️ Installation & Usage
To run these projects on your local machine:

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/Matthew725234/Python-projects.git](https://github.com/Matthew725234/Python-projects.git)
