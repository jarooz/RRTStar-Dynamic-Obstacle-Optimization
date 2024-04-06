# Optimizing the Performance of RRT* in Dynamic Environments

## Project Overview
This project focuses on enhancing the Rapidly-exploring Random Tree (RRT*) algorithm for motion planning in dynamic environments, specifically aiming to improve performance in scenarios with moving obstacles. Our goal is to provide a robust solution that efficiently recalculates paths in real-time as obstacles move, thereby facilitating smoother and more reliable navigation for autonomous robots.

## Table of Contents
- [Project Overview](#project-overview)
- [Features](#features)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Running the Demo](#running-the-demo)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)

## Features
- **Dynamic Obstacle Avoidance**: Implements an enhanced RRT* algorithm that adapts to obstacles changing positions within the environment.
- **Path Optimization**: Continuously seeks the most efficient path to the goal, taking into account the dynamic nature of the obstacles.
- **Customizable Environments**: Includes tools for creating and testing in various simulated environments with different obstacle configurations.
- **Performance Benchmarks**: Offers benchmarking tools to compare the performance and efficiency of the optimized RRT* algorithm against standard implementations.

## Getting Started

### Prerequisites
- Python 3.8 or later
- NumPy
- Matplotlib (for visualization)

### Installation
1. Clone the repository:
git clone https://github.com/yourusername/RRTStar-Dynamic-Obstacle-Optimization.git
2. Install the required Python packages:
pip install numpy matplotlib

### Running the Demo
To run a demo of the project, navigate to the project directory and execute:
python dynamic_path_planning_map1.py
This will launch a simulation using `map1` as the environment, showcasing the algorithm's ability to navigate around moving obstacles.

## Usage
For a simple test run, use the following command:
python RRT.py

You can modify the simulation parameters within the script files `dynamic_path_planning_map1.py` and `dynamic_path_planning_map2.py` to experiment with different environments or obstacle behaviors.

## Contributing
Contributions to improve the project are welcome. Please follow these steps to contribute:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature/AmazingFeature`).
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`).
4. Push to the branch (`git push origin feature/AmazingFeature`).
5. Open a Pull Request.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments
- Dr. Chinwe Ekenna, for guidance and invaluable insights into the project development.
- The University at Albany, College of Engineering and Applied Science for providing the resources necessary to complete this work.
- All contributors and users of the project.
