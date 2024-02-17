## Artificial Intelligence Algorithm Implementations

This repository contains various algorithms and problem-solving techniques commonly used in the field of Artificial Intelligence, implemented in python programming languages.

## Contents

1. **Search Algorithms**
   - [Breadth-First Search (BFS)](https://github.com/madulika-prabu/Artificial-intelligence/blob/main/1_BFS.ipynb)
       - It has applications in various domains including pathfinding and puzzle solving.
       - Time complexity : O(V + E)
       - Space complexity : O(V)
   - [Depth-First Search (DFS)](https://github.com/madulika-prabu/Artificial-intelligence/blob/main/2_DFS.ipynb)
       - It has applications in maze solving, cycle detection, and graph connectivity.
       - Time complexity : O(V + E) space complexity of O(V)
       - Space complexity : O(V)
   - [Uniform Cost Search (UCS)](https://github.com/madulika-prabu/Artificial-intelligence/blob/main/3_UCS.ipynb)
       - It is efficient for finding the shortest path in scenarios where edge weights represent distances or costs.
       - Time complexity : O((V + E) * log(V)) 
       - Space complexity : O(V)
   - [Greedy Best-First Search (GBFS)](https://github.com/madulika-prabu/Artificial-intelligence/blob/main/4_GBFS.ipynb)
       - Time complexity that depends on the quality of the heuristic function.
       - Space complexity of O(V)
   - [A* Search Algorithm](https://github.com/madulika-prabu/Artificial-intelligence/blob/main/5_A_star_search.ipynb)
       - The algorithm is complete and optimal when using an admissible heuristic.
       - Time complexity : O(b^d)
       - Space complexity : O(b^d)
   - [Iterative Deepening A* (IDA*)](https://github.com/madulika-prabu/Artificial-intelligence/blob/main/6_IDA_star.ipynb)
       - Time complexity : O(b^d)
       - Space complexity : O(d)
2. **Game Playing Algorithms**
   - [Minimax Algorithm](https://github.com/madulika-prabu/Artificial-intelligence/blob/main/7_minmax.ipynb)
       - Time complexity : O(b^d)
   - [Alpha-Beta Pruning](https://github.com/madulika-prabu/Artificial-intelligence/blob/main/8_alpha_beta_pruning.ipynb)

3. **Constraint Satisfaction**
   - [Constraint Satisfaction Problem Solver](https://github.com/madulika-prabu/Artificial-intelligence/blob/main/9_constraint_satisfaction.ipynb)

4. **Logic Inference**
   - [DPLL Algorithm](https://github.com/madulika-prabu/Artificial-intelligence/blob/main/10_dpll_algo.ipynb)
        -DPLL algorithm is mostly used to understand if a logical proposition is unsatisfiable or not. DPLL algorithm makes our calculations a lot faster, with helping us reduce the total number of cases we need to check.With DPLL algorithm, we try to check the most likely model for the proposition via setting some propositions true or false.
   - [Forward Chaining](https://github.com/madulika-prabu/Artificial-intelligence/blob/main/11_forward_chaining.ipynb)
   - [Backward Chaining](https://github.com/madulika-prabu/Artificial-intelligence/blob/main/12_backward_chaining.ipynb)

5. **Machine Learning**
   - [Naive Bayes Classifier](https://github.com/madulika-prabu/Artificial-intelligence/blob/main/13_naive_bayes.ipynb)
         - The Naive Bayes classifier is a probabilistic machine learning algorithm used for classification tasks, with a time complexity that depends on the size of the training data and the number of features.
         - It calculates the posterior probability of each class given the input features and selects the class with the highest probability as the predicted class label.
   - [Naive Bayes Multi-Class Classifier](https://github.com/madulika-prabu/Artificial-intelligence/blob/main/18_naive_bayes_multi.ipynb)
   - [Bayesian Network](https://github.com/madulika-prabu/Artificial-intelligence/blob/main/14_Bayesian%20_network.ipynb)

6. **Problem Solving**
   - [N-Queens Problem Solver](https://github.com/madulika-prabu/Artificial-intelligence/blob/main/15_N_Queens.ipynb)
           - An N-Queens Problem Solver is an algorithmic solution to the classic problem of placing N queens on an NxN chessboard without any queen attacking another, with a time complexity that depends on the solving technique and the size of the board.
           - The efficiency of N-Queens Problem Solvers depends on factors such as the size of the board, the search strategy employed, and the presence of constraints or symmetry in the problem.
   - [8-Puzzle Problem Solver](https://github.com/madulika-prabu/Artificial-intelligence/blob/main/16_8-puzzle_prob.ipynb)
           - An 8-Puzzle Problem Solver is an algorithmic solution to the classic sliding puzzle problem, where a 3x3 grid of numbered tiles is shuffled, and the objective is to rearrange the tiles into a specific goal state, with a time complexity that depends on the solving technique and the complexity of the puzzle.
   - [Cryptarithmetic Solver](https://github.com/madulika-prabu/Artificial-intelligence/blob/main/17_cryptarithmetic.ipynb)
           - A Cryptarithmetic Solver is an algorithmic solution to cryptarithmetic puzzles, where letters represent digits, and the goal is to find the correct assignment of digits to letters to make a valid arithmetic equation, with a time complexity that depends on the solving technique and the complexity of the puzzle.
     
## Usage

Each algorithm or problem-solving technique is implemented in its respective file. You can navigate to the corresponding directory and find the implementation along with usage instructions in the comments.
