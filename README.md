# daa-cia-1

Prims algorithm and Kruskals algorithm are used to find the minimum cost to link each node to any one or many of the nodes without forming a cycle
Both algorithms work for this particular graph since all the nodes have atleast 1 as indegree.
There is only one node(S) with indegree 0 which is linked with 2 other nodes, so it will automatically be connected according to the minimum spanning algorithm.

It does not work for many graphs with improper connection. For example, When the direction of E and D was changed from E->D to D->E, the answer was still the same but the connection was not proper.
There was no path from S and E to any other node which is not the correct spanning tree.

Dijkstras algorithm is used to find the shortest path from source node to all other nodes of the graph. 
The Dijkstras algorithm does not work for negative sum of weights. This graph contains negative weights but the sum is not negative.
The shortest path from source (S) to all other nodes are valid for this graph since it also has a proper directed edge which makes a proper path and connection between nodes.
