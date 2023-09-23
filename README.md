# Dijkstra's Algorithm Visualization

This Python project provides a visualization of Dijkstra's algorithm using the Pygame library. Dijkstra's algorithm is a widely used algorithm in graph theory for finding the shortest path between nodes in a weighted graph. This visualization allows you to interactively create a grid, set obstacles, specify the start and target nodes, and observe how Dijkstra's algorithm finds the shortest path.

![Dijkstra's Algorithm Visualization](demo.gif)

## Table of Contents

- [Getting Started](#getting-started)
- [Usage](#usage)
- [Controls](#controls)
- [Features](#features)
- [Contributing](#contributing)
- [License](#license)

## Getting Started

To get started with this visualization tool, you'll need to have Python and the Pygame library installed on your machine.

### Installation

1. **Clone the Repository:** You can clone this repository using Git:

   ```bash
   git clone https://github.com/your-username/dijkstra-visualization.git
   cd dijkstra-visualization
   ```

2. **Install Dependencies:** Make sure you have Pygame installed. If you don't have it, you can install it using pip:

   ```bash
   Copy code
   pip install pygame
   ```

## Usage
   
1. **Run the Application:**

   ```bash
   Copy code
   python main.py
   ```

2. **Creating the Grid:**
   - Left-click on a box to mark it as an obstacle (wall).
   - Right-click on a box to set it as the target node.

3. **Starting the Algorithm:**
   - After setting the target node, press any key to start the Dijkstra's algorithm.

4. **Visualizing the Algorithm:**
   - The algorithm will find the shortest path from the start node (top-left) to the target node (right-clicked).
   - Visited nodes will be shown in green, and the shortest path will be displayed in blue.
   - If there's no path to the target node, a message box will appear.

## Controls
- **Left Mouse Button:** Mark a box as a wall (obstacle).
- **Right Mouse Button:** Set a box as the target node.
- **Any Key:** Start the Dijkstra's algorithm after setting the target node.
- **Close Button (X):** Close the application.

## Features
- **Interactive Visualization:** You can interactively create a grid, set obstacles, and observe the algorithm's progress.
- **Visualization of Shortest Path:** The shortest path from the start node to the target node is displayed in blue.
- **Message Box for No Solution:** If there's no path to the target node, a message box will appear.
- **Customizable Grid:** You can easily change the grid size by modifying the columns and rows variables in the code.

## Contributing
Contributions to this project are welcome! If you'd like to contribute, please follow these steps:

   1. Fork the repository.
   2. Create a new branch for your feature or bug fix.
   3. Make your changes and commit them.
   4. Push your changes to your fork.
   5. Create a pull request to the main repository.

## License
This project is licensed under the MIT License - see the **LICENSE** file for details.

