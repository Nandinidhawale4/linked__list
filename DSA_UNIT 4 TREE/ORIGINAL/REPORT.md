## Problem Statement

Write a C++ program to construct a tree and identify its root node, leaf nodes, internal nodes, degree of each node, and height of the tree.

## Approach

To implement this problem in C++, we use a linked representation of a general tree where each node contains data and a list/vector of pointers to its child nodes.

1. Node Structure: Define a Node structure or class containing:

	• int data (or any data type).

	• std::vector<Node*> children to store dynamically added child nodes (making it a general tree).

2. Tree Construction: Establish the Root pointer. Insert nodes dynamically by linking parent nodes to child nodes.
 
3. Terminology Identification:

	• Root Node: The top-most node of the tree with no parent (the entry point).

	• Leaf Nodes: Nodes that have zero children (children.size() == 0).

	• Internal Nodes: Nodes that have at least one child and are not the root node.

	• Degree of a Node: The total number of direct children connected to that node (children.size()).

	• Height of the Tree: The maximum number of edges from the root node to a leaf node. This is calculated recursively:

    \(\max(\text{height of children}) + 1\).

 ##  Complexity Analysis

Operation :-  	Time Complexity     :-    	Space Complexity	

Tree Construction:-	O(N):-   O(N).

Identifying Root:-	O(1) :-O(1)

Finding Leaf/Internal Nodes	:-O(N):- O(N)

Calculating Degree	:-O(1):- O(1)

Finding Tree Height:-	O(N):- O(H)

## Conclusion

By implementing this program, we successfully simulated a hierarchical non-linear data structure using C++ pointers and vectors. This exercise helps in understanding foundational tree terminologies such as root, leaf nodes, internal nodes, degrees, and height, which form the building blocks for working with advanced data structures like Binary Search Trees (BST), AVL trees, and Heaps.
