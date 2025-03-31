# EMERGENCY-NAVIGATION-SYSTEM


## Overview
The **Emergency Navigation System** is designed to efficiently determine the shortest time between two nodes in a network of warehouses and hospitals. Using advanced graph algorithms, the system ensures fast and optimized routing for emergency scenarios.

## Features
- **Graph Representation:** The network is represented using an adjacency list.
- **Dijkstra's Algorithm:** Utilized to find the shortest path between two nodes.
- **Heap Data Structure:** Implements a priority queue for efficient pathfinding.
- **Multiple Locations:** Includes 3 warehouses and 8 hospitals.
- **Time Calculation:** Computes the shortest travel time between nodes.
- **Optimized Performance:** Uses efficient data structures to minimize computation time.

## Data Structures Used
- **Graph (Adjacency List):** Represents the network of warehouses and hospitals.
- **Heap (Priority Queue):** Efficiently extracts the node with the shortest distance.
- **Dictionary/HashMap:** Stores distances and previous nodes for backtracking.

## How It Works
1. The system takes an input graph with warehouses and hospitals as nodes.
2. Roads/paths are represented as edges with associated travel times.
3. Dijkstra's algorithm finds the shortest path between a source and a destination.
4. The heap structure ensures efficient selection of the next shortest path.
5. The system outputs the optimal route and estimated travel time.

## Example Use Case
- A medical supply truck needs to travel from a warehouse to the nearest hospital.
- The system quickly computes the shortest and fastest route.
- Reduces response time in emergencies by optimizing navigation.

## Technologies Used
- **Programming Language:** C AND C++
- **Graph Algorithm:** Dijkstra’s Algorithm
- **Data Structures:** Adjacency List, Heap, HashMap

## Future Enhancements
- **Dynamic Traffic Updates:** Incorporate real-time traffic conditions.
- **Multiple Vehicle Support:** Optimize routes for multiple emergency vehicles.
- **GUI Interface:** Develop a visual representation of the navigation system.

## Conclusion
The **Emergency Navigation System** is a highly efficient tool for optimizing emergency response times by leveraging graph-based pathfinding algorithms. Using Dijkstra’s Algorithm and heap-based priority queues ensures rapid and accurate routing decisions, making it invaluable in crisis situations.

