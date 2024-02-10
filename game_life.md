Here is a psudocode for the classical game of life algorithm:

```
1. Initialize a 2D grid with random binary values (0 or 1).
2. For each cell in the grid, do the following:
    1. Count the number of live neighbors (cells with value 1).
    2. If the cell is alive (value 1):
        1. If the number of live neighbors is less than 2 or greater than 3, set the cell to dead (value 0).
    3. If the cell is dead (value 0):
        1. If the number of live neighbors is exactly 3, set the cell to alive (value 1).
3. Update the grid with the new cell states.
4. Repeat steps 2-3 for the desired number of generations.
```