# Pathfinder's Quest 🗺️

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Pygame](https://img.shields.io/badge/pygame-%23FFFFFF.svg?style=for-the-badge&logo=pygame&logoColor=black)

A visual comparison tool for pathfinding algorithms (BFS, DFS, A*) with interactive grid visualization.

## Features ✨

- **Interactive visualization** of pathfinding algorithms
- **Three algorithms** implemented:
  - 🟦 Breadth-First Search (BFS)
  - 🟩 Depth-First Search (DFS)
  - 🟪 A* Search Algorithm
- **Dynamic grid generation** with random obstacles
- **Performance metrics** comparison
- **Keyboard controls** for easy interaction

## Installation ⚙️

1. Clone the repository:

```bash
git clone https://github.com/Devansh-Chhabra/Path-Finder
cd Path-Finder
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

## Usage 🚀

Run the application:
```bash
python Path_finder_file.py
```

## Controls 🎮

Key	Action
- B	Run BFS algorithm
- D	Run DFS algorithm
- A	Run A* algorithm
- C	Compare all algorithms
- R	Reset visualization


## Algorithm Details 🤖

| Algorithm | Guarantees Shortest Path? | Time Complexity | Space Complexity |
|-----------|--------------------------|-----------------|------------------|
| BFS       | ✅ Yes                   | O(V+E)          | O(V)             |
| DFS       | ❌ No                    | O(V+E)          | O(V)             |
| A*        | ✅ Yes (with good heuristic) | O(E)       | O(V)             |

## Customization 🛠️

Modify these parameters in the code:

# Grid settings
rows, cols = 20, 20            # Grid dimensions

obstacles = int(0.3*rows*cols)    # Obstacle density

# Visual settings
VISIT_COLOR = (173,216,230)      # Light blue for visited nodes

PATH_COLOR = (0,0,255)           # Blue for final path


## Contributing 🤝

Contributions welcome! Please:
- Fork the project
- Create your feature branch (git checkout -b feature/AmazingFeature)
- Commit your changes (git commit -m 'Add some amazing feature')
- Push to the branch (git push origin feature/AmazingFeature)
- Open a Pull Request


## License 📜

Distributed under the MIT License. See LICENSE for more information.


## Made with ❤️ and Python 🐍
Key improvements:
- Added badges for Python/Pygame
- Better visual hierarchy with emojis
- Responsive tables for controls/algorithms
- Clear code block formatting
- More professional structure
- Added placeholder for screenshot
- Contribution guidelines
- License information
