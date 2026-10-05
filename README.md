# Java Projects

A collection of Java projects focused on core programming concepts, recursion, and problem solving.

## Island Finder

`islandFinder.java` generates a two-dimensional grid of land (`1`) and water (`0`), then counts the number of connected islands.

### Concepts Used

- Java 2D arrays
- Recursion
- Grid traversal
- Boundary checking
- Randomized test data

The recursive `check` method visits connected land cells and marks them as water so each island is counted only once.

### Run

```bash
javac islandFinder.java
java islandFinder
```

The program prints a randomly generated 10x10 map followed by the number of islands found.
