Dijkstra's Algorithm is a way of finding the shortest path through a [[Directed Graph]] from a given source.
**This works as long as none of the arc weights are negative.**

This algorithm is useful in finding the shortest distance between 2 points.
## How It Works
We are given a directed, weighted graph G, a source vertex V, and a destination D
Create a [[Priority Queue]] containing only V at first.

We examine all of V's out edges, and add the endpoint of the shortest path length to the queue each time. 

once we reach the destination vertex, we can pop the priority queue in order to get the shortest path from V to D.

This is a case where a [[Greedy Algorithm]] provides an optimal solution to a problem!
