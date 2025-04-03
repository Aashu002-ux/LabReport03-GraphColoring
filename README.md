# LabReport03-GraphColoring
# Graph Coloring using Backtracking

## Overview
This project implements the **Graph Coloring Problem** using the **backtracking algorithm**. The program determines whether a given graph can be colored with a specified number of colors while ensuring that no two adjacent vertices share the same color.

## Features
- Takes input for the number of vertices, edges, and available colors.
- Uses backtracking to find a valid coloring (if possible).
- Outputs whether the coloring is possible and provides the color assignment.
- Demonstrates recursive problem-solving techniques.

## How It Works
1. The user inputs the number of vertices (N), edges (M), and colors (K).
2. The graph is represented as an adjacency list.
3. The algorithm attempts to assign colors to each vertex while ensuring no two adjacent vertices have the same color.
4. If a valid coloring exists, it displays the color assignment; otherwise, it reports that coloring is not possible.
