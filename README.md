# Ant Colony Network Optimisation

This repository implements a network routing optimisation algorithm inspired by **Ant Colony Optimization (ACO)**, a nature-inspired heuristic algorithm that mimics the foraging behavior of ants to solve complex optimization problems.

## Overview of Ant Colony Optimization (ACO)
Ant Colony Optimization (ACO) is a probabilistic technique used to find optimized solutions by simulating the behavior of ants. Ants deposit **pheromones** on their paths while foraging, which influences the movement of other ants. Over time, the stronger pheromone trails attract more ants, resulting in the discovery of shorter and more efficient paths.

In network routing, ACO is used to find optimal or near-optimal paths for data packets by simulating ants traversing the network nodes, leaving pheromones on successful paths.

## Features
- Implements ACO for optimising routing in networks.
- Simulates ants moving through network nodes and updating pheromones to discover optimal paths.
- Supports adjustable parameters such as the number of ants, pheromone evaporation rate, and search space.
- Configurable network topology.

## Requirements
- Python 3.x or higher.
- No external libraries or dependencies are required.

## Installation
Clone this repository:


You can modify the script to experiment with network configurations and ACO parameters.

## Project Structure
- `network_config`: Configuration function for defining network parameters.
- `RIP and OSPF`: DVR Protocols for baseline results
- `AntColonyOptimisation`: Main script that implements the ACO algorithm for network optimisation.
- `Results`: Calculation and plotting of metrics for Comparison

