# AI-Assignment-2
Comparison 

Best First Search (Greedy Search):
- Expands nodes based only on h(n) (Manhattan distance).
- Very fast, since it greedily moves closer to the goal.
- May return suboptimal paths.

A* Search:
- Expands nodes based on f(n) = g(n) + h(n).
- Guarantees the shortest path with Manhattan distance (admissible heuristic).
- Slower than Best First, but always optimal.

Conclusion:
Best First = faster but approximate.
A* = slower but guaranteed shortest path.
