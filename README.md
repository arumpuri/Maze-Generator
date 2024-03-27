# Maze-Generator
recursive algorithm generates mazes
The algorithm works by visiting a starting space in the maze and then
recursively visiting a neighboring space. The maze’s hallways are “carved
out” of the maze as the algorithm continues to visit neighbors. If the algo-
rithm reaches a dead end that has no neighboring spaces, it backtracks to
earlier spaces until it finds an unvisited neighbor and continues visiting
from there. By the time the algorithm backtracks to the starting space, the
entire maze has been generated.
The recursive backtracking algorithm we’ll use here produces mazes
that tend to have long hallways (the maze spaces that connect branching
intersections) and are fairly simple to solve. However, this algorithm iseasier to implement than many other maze-generation algorithms, such as
Kruskal’s algorithm or Wilson’s algorithm, so it serves as a good introduc-
tion to the topic.
