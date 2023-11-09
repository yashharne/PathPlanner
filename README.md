# PathPlanner

PathPlanner is a Machine Learning Mini-project that helps find the most optimal path based on the Traveling Salesman problem. It uses a Machine Learning Linear Regression Model to calculate costs and determine the best route for travel.

Made by: \
Yash Harne ([@yashharne](https://github.com/yashharne)) \
Kanishka Bansode ([@kb-0311](https://github.com/kb-0311)) \
Sushrut Lachure ([@Sushrut22](https://github.com/Sushrut22))

## Table of Contents

- [Cost Finder](#cost-finder)
- [Path Finder](#path-finder)
- [Path Visualizer](#path-visualizer)
- [Getting Started](#getting-started)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Contributing](#contributing)
- [Collaborators](#collaborators)

## 1. Cost Finder

The Cost Finder calculates the total monetary cost, which includes the cost of each item that the user wants to buy, along with the traveling cost from the source to the destination. It uses Linear Regression to calculate the travel cost based on vehicle features like vehicle type, mileage, horsepower, acceleration, displacement, etc.

## 2. Path Finder

The Path Finder solves the scenario as a Traveling Salesman Problem (TSP) using Bitmask Dynamic Programming (DP) to find the most optimal path.

## 3. Path Visualizer

The Path Visualizer maps the coordinates of the most optimal route found by the Path Finder on the map using the Folium library. It can also be done by making the URL for Google Maps, as we already know the source, intermediate stops, and the destination.

# Getting Started

To get started with the project, clone the repository and install the necessary dependencies.

# Prerequisites

- Python 3.x
- Libraries: sklearn, pandas, numpy, folium

# Installation

1. Clone the repo

```sh
git clone https://github.com/yashharne/PathPlanner.git
```

2. Install Python packages

```sh
pip install -r requirements.txt
```

# Contributing

Any contributions you make are greatly appreciated.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

# Collaborators

Yash Harne ([@yashharne](https://github.com/yashharne)) \
Kanishka Bansode ([@kb-0311](https://github.com/kb-0311)) \
Sushrut Lachure ([@Sushrut22](https://github.com/Sushrut22))

