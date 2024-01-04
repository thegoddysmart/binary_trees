# 0x1D. C - Binary trees

## What is a Binary Tree?
A binary tree is a hierarchical data structure in which each node has at most two children, referred to as the left child and the right child. Nodes in a binary tree represent elements, and the structure allows for efficient searching, insertion, and deletion operations. The nodes in a binary tree have a parent-child relationship, and each node can have zero, one, or two children.

## Difference between a Binary Tree and a Binary Search Tree (BST):
A Binary Search Tree (BST) is a specific type of binary tree that follows a particular ordering property. In a BST, for each node `n`, all nodes in its left subtree have values less than `n`, and all nodes in its right subtree have values greater than `n`. This ordering property facilitates efficient search operations.

## Time Complexity Gain Compared to Linked Lists:
In terms of time complexity, Binary Search Trees (BSTs) offer significant advantages over linked lists for search operations. The average time complexity for search, insert, and delete operations in a balanced BST is O(log n), where n is the number of nodes. In contrast, linked lists typically have linear time complexity O(n) for these operations. However, it's essential to note that the efficiency of a BST depends on its balance, and in the worst case (an unbalanced tree), the time complexity can degrade to O(n).

## Depth, Height, and Size of a Binary Tree:
- Depth: The depth of a node in a binary tree is the length of the path from the root to that node. The depth of the root is 0.

- Height (or Depth): The height of a binary tree is the length of the longest path from the root to a leaf. Alternatively, it is the maximum depth of any node in the tree.

- Size: The size of a binary tree is the total number of nodes in the tree.

## Traversal Methods in a Binary Tree:
- In-order traversal: Visit the left subtree, then the root, and finally the right subtree.
- Pre-order traversal: Visit the root, then the left subtree, and finally the right subtree.
-Post-order traversal: Visit the left subtree, then the right subtree, and finally the root.

## Types of Binary Trees:
- Complete Binary Tree: A binary tree in which every level, except possibly the last, is completely filled, and all nodes are as left as possible.

- Full Binary Tree: A binary tree in which each node has either 0 or 2 children.

- Perfect Binary Tree: A binary tree that is both full and complete, meaning all leaf nodes are at the same level.

- Balanced Binary Tree: A binary tree is considered balanced if the height of the left and right subtrees of any node differ by no more than one. Balancing ensures that the search operations maintain their O(log n) efficiency.
