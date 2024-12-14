# Metro_App
---
## ⚙️ **How it Works**
1. **Input System**: Users provide the source and destination metro stations.
2. **Path Calculation**: 
  - **BFS** is used to find the shortest path between the stations.
  - **Dijkstra's Algorithm** is used to find the most economical path.
3. **Line Interchange**: The system alerts users when they need to switch metro lines (Blue, Yellow, Red, etc.).
4. **Tourist Mode**: Enter a tourist place to get the closest metro station.
---
## 📚 **Algorithms Used**
- **Breadth-First Search (BFS)**: 
 - Used to compute the shortest path between two stations.
- **Dijkstra's Algorithm**: 
 - Used to compute the most economical path, considering possible costs associated with certain routes.
- **Data Structures**: 
 - **Graph (Adjacency List)**: To store the metro network.
 - **Priority Queue**: Used in Dijkstra's algorithm to ensure optimal pathfinding.
 - **Hash Maps**: Used to map station names to their indices and tourist locations to their nearest stations.
---
## 📦 **Prerequisites**
1. **C++ Compiler**: Required to compile the code (like GCC, MinGW, or Visual Studio).
2. **File Setup**: Ensure the following files are in the project directory:
  - **list.txt**: Contains the names of all the metro stations.
  - **blueline.txt, yellowline.txt, redline.txt, greenline.txt, violetline.txt, orangeline.txt**: Contains connections for respective metro lines.
  - **tourplace.txt**: Contains tourist places and their nearest metro stations.
---
