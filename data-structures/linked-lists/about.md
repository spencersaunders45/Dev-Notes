# Linked Lists
***

## Properties
- 

## Linked List O(n)
| Common Linked List Operation | Description | Performance |
| --- | --- | --- |
| insert_head(value) | Adds "value" before the head | O(1) - Just need to adjust the pointers near the head. |
| insert_tail(value) | Adds "value" after the tail | O(1) - Just need to adjust the pointers near the tail. |
| insert(i, value) | Adds "value" after node "i". | O(n) - It's not complicated to adjust the pointers to insert, but it takes a loop to find the node to insert after. |
| remove_head() | Removes the first item (the head) | O(1) - Just need to adjust the pointers near the head. |
| remove_tail(index) | Removes the last item (the tail) | O(1) - Just need to adjust the pointers near the head. |
| remove(i) | Removes node "i". | O(n) - It's not complicated to adjust the pointers to remove, but it takes a loop to find the node to remove. |
| size() | 	Return the size of the linked list | O(1) - The size is maintained within the linked list class. |
| empty() | Returns true if the length of the linked list is zero. | O(1) - The comparison of the length with 0 is all that is needed. |