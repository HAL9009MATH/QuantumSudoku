# 🧩 2x2 Binary Sudoku Solver using Grover's Algorithm

This repository implements a **quantum algorithm** to solve a simple 2x2 binary Sudoku puzzle using **Grover's search algorithm**.

## 📖 Problem Description

In this notebook, we solve a **2x2 binary Sudoku Puzzle**. If a solution exists, we find it with high probability using Grover's algorithm.

A Sudoku has two simple rules:

- No row may contain the same value twice  
- No column may contain the same value twice

A 2x2 Sudoku grid can be represented as:
$$
\begin{pmatrix}
s_0 & s_1 \\
s_2 & s_3
\end{pmatrix}
$$
where each `s_i` is in {0,1}, and thus the grid is a vector in $\mathbb{Z}_2^4$.

There are 16 possible 2x2 binary grids, but only two valid solutions:
$$
\begin{pmatrix}
1 & 0 \\
0 & 1
\end{pmatrix}
$$
