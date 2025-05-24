# AI-lab-
# Description
# Code 1 
This repository contains a two Python scripts in screen recording video form first code demonstrates two popular informed search algorithms — Greedy Best-First Search and A* — on a directed graph. Each node in the graph represents a state, and edges represent the cost to move between nodes. A heuristic function is also defined to guide the search. The goal of both algorithms is to find the optimal or near-optimal path from a start node (S) to a goal node (G), based on the provided heuristic and graph structure. A screen recording videos are included in this repository. I explain the Python code step-by-step, including
1. Greedy Best-First Search
This algorithm uses only the heuristic value to choose the next node.
At each step, it selects the node with the lowest heuristic value.
It does not guarantee the shortest path, but is often faster than exhaustive methods.
2. A* Search
This algorithm combines:
g(n): the actual cost from start to current node
h(n): the heuristic estimate to the goal
It selects the node with the lowest f(n) = g(n) + h(n).
A* guarantees the shortest path if the heuristic is admissible (never overestimates the true cost).
# Code 2
Second code visualizes the marks obtained by a student named Aiman Shabbir in three assessments: Quiz, Assignment, and Mid Term using matplotlib. The script displays a single student name on the x-axis and the corresponding marks on the y-axis with clear labeling and color differentiation. In screen recording video I explain the Python code step-by-step, including how the bar chart was plotted using matplotlib, how data points were positioned and labeled, and how I ensured only one student name appears on the x-axis while showing multiple bars for different assessment types.
