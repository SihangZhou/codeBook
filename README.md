# codeBook
for fun, forever

codes for poj. all C++ codes.

1. poj3984.cpp: my solution for poj 3984. BFS for shortest path, and recursively trace back the path. I remebered a lot for solving it: how to define mutli-dim vector, how to define queue, how to define struct array, how to define direction, how to write BFS, how to trace path. Note, BFS is not implemented recursively itself (in contrast, DFS is usually implemnted in a recursive way).

2. poj2524.cpp: my solution for poj 2524. Simple application of Union Set. I memorized that time we prepared for ACM/ICPC contest. I re-learned how to implement a Union Set: makeSet, findSet, unionSet. Two keypoints: update root node along the trace path when union for a coming pair by finding operation (压缩路径); combine two subsets according to the rank (按秩合并).
