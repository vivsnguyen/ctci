# Trees and Graphs

## Types of Trees
* A tree is a data structure composed of nodes
* Each tree has a root node
* The root node has zero or more child nodes
* Each child node has zero or more child nodes, etc.
* Trees are hierarchical
* Trees are similar to Graphs, except that a cycle cannot exist in a Tree - they are *acyclic*
	* always exactly *one* path between nodes

Simple class definition for Node:

```python3
class Node(object):
    def __init__(self, data):
        self.data = data
        self.children = []
```

## Trees vs. Binary Trees

