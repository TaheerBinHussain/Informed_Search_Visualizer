Overview:-
This project implements a Dynamic Pathfinding Agent capable of navigating a 2D grid environment. The agent uses informed search algorithms to find the optimal route from a fixed start node to a goal node. It features a dynamic mode where obstacles randomly spawn while the agent is in transit, triggering real-time path detection and re-calculation.

Features:-

-> Informed Search Algorithms: Choose between A* Search and Greedy Best-First Search.

-> Heuristics: Toggle between Manhattan Distance and Euclidean Distance.

-> Interactive Map Editor: Manually place or remove walls by clicking and dragging on the grid.

-> Random Map Generation: Instantly generate a maze with a 30% obstacle density.

-> Dynamic Re-planning: The agent moves step-by-step. If a newly spawned obstacle blocks its current path, it immediately calculates a new route from its current position.

-> Real-Time Visualization: Yellow nodes represent the frontier, light blue nodes represent visited/expanded nodes, and the final calculated path is highlighted in green.

-> Metrics Dashboard: Tracks the total nodes expanded, final path cost, and total execution time in milliseconds.

Dependencies
This project is built entirely using Python's standard GUI library (tkinter) and built-in modules (heapq, random, time). No external dependencies or installation commands are required.

How to Run:-

Clone this repository to your local machine.

Ensure you have Python 3.x installed.

Run the main Python script from your terminal: python pathfinding_agent.py

Usage Instructions:-

Set Grid Size: Adjust the Rows and Columns input fields and click "Update Grid".

Setup Map: Use your mouse to draw walls, or click "Random Map (30%)" to generate obstacles.

Configure Search: Select your preferred algorithm and heuristic from the dropdown menus.

Start: Click the "START" button to watch the algorithm calculate the path and the agent begin its movement.
