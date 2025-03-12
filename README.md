# Maze Solver

## Overview
The **Maze Solver** is a Python project that generates and solves mazes using graphical representation. It utilizes object-oriented principles to manage individual maze cells and their walls. The project includes functionality for maze generation and solving using algorithms like depth-first search (DFS) or breadth-first search (BFS).

## Features
- **Maze Generation**: Creates a grid-based maze with randomly placed walls.
- **Cell Representation**: Each cell has attributes for walls (left, right, top, bottom).
- **Graphical Display**: Uses a graphical window to visualize the maze with `tkinter`.
- **Maze Solving**: Implements pathfinding algorithms to find a solution.

## Installation
### Prerequisites
Ensure you have Python installed on your system. You also need `pip` for managing dependencies and the `tkinter` library for GUI visualization.

### Install Dependencies
If `tkinter` is not installed, install it using following command: 

#### For Windows:
```bash
pip install tk
```
#### For Linux:
```bash
sudo apt-get install python3-tk
```
#### For macOS:
```bash
brew install python-tk
```

### Clone the Repository
```bash
git clone https://github.com/sabrek15/Maze-Solver.git
cd Maze-Solver
```

## Usage
### Running the Maze Generator and Solver
Excute the main script using the provided shell script:
```bash
./main.sh
```
### Running Tests
Run the test suite using:
```bash
./test.sh
```

### Customizing the Maze
Modify parameters in `src/main.py` to adjust maze size and complexity:
```bash
num_rows = 10
num_cols = 12
```

## Code Structure
```
Maze-solver/
│── src/
│   │── graphics.py   # Handles graphical rendering
│   │── main.py       # Entry point of the application
│   │── maze.py       # Defines the Maze class and logic
│   │── cell.py       # Defines individual Cell objects
│   │── test.py       # Test cases for the maze solver
│── main.sh           # Script to run the main application
│── test.sh           # Script to run tests
│── README.md         # Project documentation
│── .gitignore        # Git ignore file
```

## Contributing
1. Fork the respository.
2. Create a new branch
    ```bash
    git checkout -b feature-branch
    ```
3. Commit your changes
    ```bash
    git commit -m 'Add new feature'
    ```
4. Push to the branch
    ```bash
    git push origin feature-branch
    ```
5. Open a pull request.