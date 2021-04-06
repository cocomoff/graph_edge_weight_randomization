# Graph Edge Weight Randomization


A simple approach to get K-shortest paths (KSP) from the source vertex s to the sink vertex t on a weighted graph G=(V, E, w).
The procedure tries to

1. Compute a shortest path on G=(V, E, w)
2. For each edge in E, w(e) is updated by some random distribution.
3. Repeat 1. and 2. until k-paths are computed.