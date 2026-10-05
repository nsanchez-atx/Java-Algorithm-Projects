# Java Algorithm Projects

A collection of Java projects focused on algorithms, recursion, arrays, and problem solving.

## Island Finder

**File:** `islandFinder.java`

Island Finder generates a two-dimensional grid containing land (`1`) and water (`0`) and determines how many separate islands exist in the grid.

Connected land cells are treated as part of the same island.

## How It Works

The program:

1. Generates a random 2D map of land and water
2. Searches the grid for land cells
3. Counts a new island when an unvisited land cell is found
4. Uses recursion to visit all connected land cells
5. Marks visited land cells so the same island is not counted twice

## Concepts Used

- Java
- 2D Arrays
- Recursion
- Grid Traversal
- Boundary Checking
- Algorithm Design
- Randomized Test Data

## Example

A generated map may look like:

```text
1 0 0 1 1
1 0 0 0 1
0 0 1 0 0
0 1 1 0 1
```

The program recursively explores connected land cells and returns the total number of separate islands.

## Build and Run

Compile:

```bash
javac islandFinder.java
```

Run:

```bash
java islandFinder
```

## Purpose

This project was created to practice recursion and 2D array traversal while solving a connected-region problem.
