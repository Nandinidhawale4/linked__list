## Problem Statement

Write a C++ program to construct a tree and identify its root node, leaf nodes, internal nodes, and degree of each node. Display the parent and children of each node, calculate the depth of each node, and determine the height of the tree.

## Approach

To implement this program in C++, a binary tree using linked nodes is a standard and effective choice:
1. Node Structure: Define a Node structure or class containing a data value, a pointer to the left child, and a pointer to the right child.
  
2. Tree Construction: Build the tree dynamically using pointer allocations (either manually or via level-order insertion).
   
3. Properties Identification:
   
	• Root Node: The top-most node of the tree (entry point).

	• Leaf Nodes: Nodes with no children (left == nullptr and right == nullptr).

	• Internal Nodes: All nodes that are neither the root nor a leaf node (or simply nodes with at least one child, excluding the root depending on strict definitions).

	• Degree: The number of children a node has (ranges from 0 to 2 for a binary tree).

	• Parent & Children: For any node, reference its parent during traversal, and read its immediate left and right child pointers.

	• Depth: The number of edges from the root to the node. Traversed using a top-down approach passing depth + 1 to recursive calls.

	• Height: The maximum depth of any node in the tree. Calculated bottom-up using max(height(left), height(right)) + 1.

## Complexity Analysis

Metric	Complexity    

Time Complexity	O(N)

Space Complexity	O(N)

## Conclusion

This analysis provides a structured way to implement fundamental tree terminologies and properties in C++. By traversing the tree recursively, we can efficiently compute properties like depth, height, and node degrees in linear time, solidifying foundational data structure concepts.
