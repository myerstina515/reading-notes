# Trees

## Vocabulary
  1. Node - individual piece of data that when put together makes up all the data of the binary tree.
  2. Root - The top or first node in the tree.
  3. Left Child - Node that is to the left of the root.
  4. Right Child - Node that is to the right of the root.
  5. Edge - the link that is in between the parent and child nodes.
  6. Leaf - a node row that does not have any children.
  7. Height - number of layers of nodes from root to leaf.
  8. Traversal - 
    - Depth first - has three different ways to traverse the depth (or height) of the tree. First method starts with the Root node, then moves to the left child and it's children, followed by the right child and it's susequent children. The second method goes from left to right regardless of layer of the nodes. It could start with the grandchildren, then move to a child, then to a parent, then to a grandchild (on the right), followed by a child. Third method goes bottom to top, so it begins with the grandchildren, followed by the child and then the parent. In all of these methods, we focus on one child node at a time along with their child nodes, before moving to the right child node and all of it's child nodes. One note, depth first traversal relies on *stacks* to store the nodes for callback.
    - Breadth first - Goes in order by levels of nodes. It would begin with the parent (root) node, followed by it's direct descendants (left child, right child), then followed again by the Leaf nodes (grandchild nodes). Breadth first makes use of *queues* for node storage and traversal. 
    
## Binary Trees
  1. Trees can use any number of child nodes from the root, but binary trees specifically limit the number of child nodes to two so there is a left and a right. One strategy for adding new nodes to a binary tree is to go from the top down, looking for the first node that does not have both child spots full, and place the new node in that place. 
  2. "Perfect" binary tree is a binary tree where each node has exactly two child nodes. Big O for adding a new node is time complexity of O(n), while the space complexity refers to how wide or how tall the tree is. For width, it would be O(W), while for height it would be O(2^h-1), since every height level has 2 children.
  
## Binary Search Tree
  1. In a BST, there is some structure to how nodes are placed, with all values being compared to the value of the Root. Values smaller than the Root value are placed to the left, while all larger values are placed to the right, so the final tree goes from smallest to largest when looking from left to right.
  2. Searching a BST is easy, it is inequality comparisons to find a node. If the given value is smaller than the root, it moves to the left, where it is compared to the that node. If larger, it will go to the right of the left child, and so on until it finds it's place.
  3. Big O for time complexity is O(n) since at the worst it could require searching throught the entire tree, while the space complexity is O(1) because it does not require additional space.












