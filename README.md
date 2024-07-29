## BFS implementation using C language

Breadth-First Search (BFS) is an essential algorithm for exploring nodes in a tree or graph layer by layer from a starting point. It uses a queue to manage nodes to visit, ensuring nodes are visited in the order they were discovered. BFS is optimal for finding the shortest path in unweighted graphs and is also used for connectivity analysis and reachability in graphs. Its time complexity is O(V + E), where V is the number of vertices and E is the number of edges, making it efficient for many graph traversal applications.


## Algorithm
1.	Start
2.	SET STATUS =1(ready state) for each node in G
3.	Enqueue the starting node A and set its STATUS =2 (waiting state)
4.	Repeat step 5 to 6 until QUEUE is empty
5.	Dequeue a node N . Process it and set its STATUS=3
6.	Enqueue all neighbours of N that are in ready state (whose STATUS=1) and set their STATUS=2
[End of loop]

7.	Exit
