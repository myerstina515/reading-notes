# Graphs

## Vocabulary:
  1. Vertex: or **node** is a data object that can have zero or more adjacent vertices
  2. Edge: a connection between two nodes or **vertices**
  3. Neighbor: adjacent nodes, connected via an **edge**
  4. Degree: the nubmer of edges connected to the vertex.
  
#### Two kinds of graphs:
  1. Directed: where the edges go in one single direction (like a linked list can only see what's in front of it, never what's behind it)
  2. Undirected: where the edges either don't go in any direction, or go in both directions.
#### Complete vs Connected vs Disconnected
  1. Complete: graph where all nodes are connected to another node
  2. Connected: all verticies/nodes in graph have at least one edge (example: trees)
  3. Disconnected: where some verticies may not have edges. Contains some **islands** which are nodes without any edges/connections
  
#### Acyclic vs Cyclic
  1. Acyclic: a directed graph that doesn't have **cycles** which is when there is a possible path where the node will eventually end up back at itself (like a *tree*)
  2. Cyclic: A graph that has cycles
  
#### Graph representation
  1. Adjacency Matrix: 2 dimensional array. Uses '0' and '1' as the values at the juncture of rows and columns. If there is a connection between the vertices, it will be represented in the matrix by a value of 1, otherwise it will have a 0. *Sparse* graphs have very few connections (1's), while *dense* graphs have many connections.
  2. Adjacency List: collection of linked lists or array that lists all of the other vertices that are connected. Can be depicted by a linked list or by an array of arrays.
#### Wighted Graphs
  1. A graph with numbers assigned to its edges.
  2. In a weight matrix, it would look similar to an adjacency matrix, but instead of 1's, it would contain the number that is assigned to the connection (or edge)
  3. In a weight list, it would look like a linked list or array of arrays, but instead of the node, it would contain the node as well as the weight of the edge.
  
### Traversals:
  * Similar to traversals of trees. 
#### Breadth First:
  1. Similar to breadthFirst traversal of trees, except that it can be cyclic, which could leave you with an infinite loop. 
  2. Use of "flags" to indicate the node has been traversed already to prevent infinite loops.
  3. `BreadthFirst()` uses two methods: `Enqueue` that puts the node into the queue, `Dequeue` that removes the node from the queue.

#### Depth First:
  
  
  
  
  
  
  
  
  
  
  
  
