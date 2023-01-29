# Binary Search Trees
***

## Properties
-


| Common BST Operation | Description | Performance |
| --- | --- | --- |
| insert(value) | Insert a value into the tree. | O(log n) - Recursively search the subtrees to find the next available spot |
| remove(value) | Remove a value from the tree. | O(log n) - Recursively search the subtrees to find the value and then remove it. This will require some cleanup of the adjacent nodes. |
| contains(value) | Determine if a value is in the tree. | O(log n) - Recursively search the subtrees to find the value. |
| traverse_forward | Visit all objects from smallest to largest. | O(n) - Recursively traverse the left subtree and then the right subtree. |
| traverse_reverse | Visit all objects from largest to smallest. | O(n) - Recursively traverse the right subtree and then the left subtree. |
| height(node) | Determine the height of a node. If the height of the tree is needed, the root node is provided.Return the size of the BST. | O(n) - Recursively find the height of the left and right subtrees and then return the maximum height (plus one to account for the root). |
| size() |  Return the size of the BST.| O(1) - The size is maintained within the BST class. |
| empty() | Returns true if the root node is empty. This can also be done by checking the size for 0. | O(1) - The comparison of the root node or the size. |