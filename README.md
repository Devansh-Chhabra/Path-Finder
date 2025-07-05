Pathfinder's Quest
Pathfinder's Quest is a Python application that visualizes different pathfinding algorithms (BFS, DFS, and A*) on a grid with obstacles. The application allows users to compare the performance of these algorithms in terms of time taken, path length, and number of visited nodes.

Features
Interactive visualization of pathfinding algorithms
Three different algorithms implemented:
Breadth-First Search (BFS)
Depth-First Search (DFS)
A* Search Algorithm
Randomly generated grid with obstacles, start, and goal positions
Algorithm comparison feature
Real-time statistics display
Keyboard controls for easy interaction

Installation

Clone this repository:
bash
git clone https://github.com/yourusername/pathfinders-quest.git
cd pathfinders-quest
Install the required dependencies:
bash
pip install -r requirements.txt
Usage

Run the application:

bash
python Path_finder_file.py
Controls

B: Run Breadth-First Search (BFS)
D: Run Depth-First Search (DFS)
A: Run A* Search Algorithm
C: Compare all algorithms
R: Reset the visualization
Algorithms

Breadth-First Search (BFS)

Explores all neighbor nodes at the present depth before moving on to nodes at the next depth level
Guaranteed to find the shortest path in an unweighted grid
Depth-First Search (DFS)

Explores as far as possible along each branch before backtracking
Doesn't guarantee the shortest path but may find a solution faster in some cases
A* Search Algorithm

Uses a heuristic to estimate the cost to the goal from each node
Combines the cost to reach the node and the estimated cost to the goal
Typically more efficient than BFS or DFS when a good heuristic is available
Comparison Metrics

When comparing algorithms, the application evaluates:

Time taken: Execution time in seconds
Path length: Number of steps in the found path
Visited nodes: Number of nodes explored during the search
Customization

You can modify the following parameters in the code:

Grid size (rows and columns)
Number of obstacles
Colors for different elements
Visualization speed
Requirements

Python 3.x
Pygame 2.6.1
Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

License

This project is licensed under the MIT License - see the LICENSE file for details.
