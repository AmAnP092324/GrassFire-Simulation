# Grassfire Algorithm Visualization with SFML

This project provides a visualization of the Grassfire algorithm, a pathfinding algorithm, using the SFML (Simple and Fast Multimedia Library). The Grassfire algorithm is a simple pathfinding algorithm that explores the grid in a breadth-first manner, similar to a wave expanding from a starting point.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)

## Introduction

This project aims to provide a visual representation of how the Grassfire algorithm works. The user can see how the algorithm explores the grid, marking cells as part of the path, obstacles, start, or end points.

## Features

- Visual representation of the Grassfire algorithm on a grid
- Start and end points can be set by the user
- Obstacles can be added to the grid to demonstrate obstacle avoidance

## Getting Started

### Prerequisites

- C++ compiler
- SFML library installed

### Installation

1. Clone the repository:

```bash
git clone https://github.com/AmAnP092324/GrassFire-Simulation.git
```

2. Build the project using CMake:

```bash
cd grassfire-sfml
mkdir build && cd build
cmake ..
make
```

## Usage

1. Run the executable generated after building the project.
2. The grid will be displayed with the start point (green), end point (red), and obstacles (black) already set.
3. Once the setup is complete, the Grassfire algorithm will start running, and you can observe how it explores the grid.
4. Once the algorithm has finished, the optimal path will be displayed in blue.

## Contributing

Contributions are welcome! If you'd like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch (git checkout -b feature/improvement).
3. Make your changes.
4. Commit your changes (git commit -am 'Add new feature').
5. Push to the branch (git push origin feature/improvement).
6. Create a new Pull Request.

