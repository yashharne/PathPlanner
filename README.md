# PathPlanner

PathPlanner is a project that leverages a Linear Regression model to determine the cost factor of transportation based on the mode of travel. It also employs optimization techniques to find the most cost-efficient route for purchasing items, minimizing the overall monetary cost.

Made by: \
Yash Harne ([@yashharne](https://github.com/yashharne)) \
Kanishka Bansode ([@kb-0311](https://github.com/kb-0311)) \
Sushrut Lachure ([@Sushrut22](https://github.com/Sushrut22))

## Table of Contents

- [Cost Finder](#1-cost-finder)
- [Path Finder](#2-path-finder)
- [Path Visualizer](#3-path-visualizer)
- [Getting Started](#getting-started)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Contributing](#contributing)
- [Collaborators](#collaborators)

## 1. Cost Finder

The Cost Finder section employs a Linear Regression model to determine the miles per gallon value based on input features such as vehicle type, mileage, horsepower, acceleration, displacement, and more. This miles per gallon value is then used to calculate the cost of travel per kilometer, which serves as the cost factor of travel.

## 2. Path Finder

The Path Finder section utilizes the Haversine formula to calculate the distance between two points, taking into account the curvature of the Earth. It employs the total cost as a heuristic, which includes the cost of the item in each shop added to the cost of traveling to that particular shop. The latter is the product of Haversine distance and cost factor.

This heuristic-driven approach utilizes the Traveling Salesman Problem (TSP) and optimization techniques to identify the optimal path that minimizes the combined monetary cost of both transportation and procurement.

## 3. Path Visualizer

The Path Visualizer maps the coordinates of the most optimal route found by the Path Finder on the map using the Folium library.It generates Google Maps URLs, allowing users to navigate to designated locations using provided coordinates.

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

