# CS5040: Linear Optimization

Course material for Linear Optimization (CS5040), taught by Prof. Sobhan Babu, CSE Dept, IIT Hyderabad. Offered July–November 2025.

Assignment submissions for CS5040, covering the simplex method and its applications to matching and network flow problems.

## Contents

| # | Topic | Notebook |
|---|-------|----------|
| 1 | Geometric Simplex Algorithm | [Assignment Solutions/Assignment_1_CS25MTECH12009.ipynb](Assignment%20Solutions/Assignment_1_CS25MTECH12009.ipynb) |
| 2 | Geometric Simplex Algorithm (relaxed assumptions) | [Assignment Solutions/Assignment_2_CS25MTECH12009.ipynb](Assignment%20Solutions/Assignment_2_CS25MTECH12009.ipynb) |
| 3 | Geometric Simplex Algorithm (initial feasible point not given) | [Assignment Solutions/Assignment_3_CS25MTECH12009.ipynb](Assignment%20Solutions/Assignment_3_CS25MTECH12009.ipynb) |
| 4 | Primal–Dual Algorithm for Minimum Weight Perfect Matching | [Assignment Solutions/Assignment_4.ipynb](Assignment%20Solutions/Assignment_4.ipynb) |
| 5 | Min-Cost Max-Flow using the Geometric Simplex Method | [Assignment Solutions/Assignment_5.ipynb](Assignment%20Solutions/Assignment_5.ipynb) |

Also included:
- [LO Assignment Questions.pdf](LO%20Assignment%20Questions.pdf) — the shared question sheet describing all five assignments (kept at the repo root, outside the per-assignment folder)
- [Notes/LO.pdf](Notes/LO.pdf), [Notes/LO_1.pdf](Notes/LO_1.pdf) — self-made handwritten lecture notes (may contain errors)

## Summary

- **Assignment 1** implements the Geometric Simplex Algorithm to maximize an objective function, assuming a non-degenerate, bounded polytope, full column rank of A, and a given initial feasible point.
- **Assignment 2** implements the same algorithm with the non-degeneracy, boundedness, and rank assumptions dropped, keeping only a given initial feasible point.
- **Assignment 3** implements the algorithm without a given initial feasible point, requiring one to be computed first.
- **Assignment 4** implements the Primal–Dual Algorithm to find a minimum weight perfect matching in an edge-weighted bipartite graph via augmenting paths.
- **Assignment 5** implements Min-Cost Max-Flow on a directed network by repeatedly solving an LP formulation with the Geometric Simplex Method.

## Authors

Piyush Anand — Assignments 1–3 solo; Assignments 4–5 done together with Darshanraj Pattanaik.
