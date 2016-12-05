#### Kosaraju-Sharir Algorithm for Finding Strongly Connected Components

There are a two implementation used in traversing a graph:

Depth First Search(DFS): In this case there is an implementation where one can traverse the depth of a tree visiting the child node before the
sibling node.

Based upon when the node is processed one can divide the DFS into 3 categories:

1. Pre Order: Process the node before processing any of it’s children
2. Post Order: Process the node after all of it’s children are processed
3. In Order(Symmetric): Process the node after it’s left sibling has been processed.

Bread First Search(BFS): In this kind of traversal you visit the sibling before visiting the child nodes.

For more information on SCCs and the other classical approaches: https://en.wikipedia.org/wiki/Strongly_connected_component
