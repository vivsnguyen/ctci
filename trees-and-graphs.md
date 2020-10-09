# Trees and Graphs

## Types of Trees
* A tree is a data structure composed of nodes
* Each tree has a root node
* The root node has zero or more child nodes
* Each child node has zero or more child nodes, etc.
* Trees are hierarchical
* Trees are similar to Graphs, except that a cycle cannot exist in a Tree - they are *acyclic*
	* always exactly *one* path between nodes
* A node is called a "leaf" node if it has no children

Simple class definition for Node:

```python3
class Node(object):
    def __init__(self, data):
        self.data = data
        self.children = []
```

## Trees vs. Binary Trees
* A **binary tree** is a tree in which each node has **up to two** children
* Not all trees are binary trees

## Binary Tree vs. Binary Search Tree

## Balanced vs. Unbalanced
* A binary tree is height-balanced if, for each node in the tree, the difference between the height of the right subtree and the left subtree is at most one

```
∣Height(LeftSubTree)−Height(RightSubTree)∣<=1
```

