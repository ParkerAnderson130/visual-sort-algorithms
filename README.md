# Visual-Sort-Algorithms

This is a raw JavaScript program that creates nodes and sorts them visually using repaint and sleep functions.

## How does it work?

1. main.js creates randomly sized nodes, renders them in the order they were generated, and adds each size to an array
2. The user selects an algorithm, and an instance of the matching class is instantiated
3. The user starts the sort function, and each time a value is changed in the array the repaint function renders the new order on the window