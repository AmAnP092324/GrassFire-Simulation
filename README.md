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
- [License](#license)
- [Acknowledgements](#acknowledgements)

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
git clone https://github.com/yourusername/grassfire-sfml.git
```

2. Build the project using CMake:

```bash
cd grassfire-sfml
mkdir build && cd build
cmake ..
make
```
