# Queue
***

## Properties of a Queue
- Last in First out

## Queue O(n)
| Common Queue Operation | Description | Performance |
| --- | --- | --- |
| enqueue(value) | Adds "value" to the back of the queue | 	O(1) - Performance of adding to the end of the dynamic array |
| dequeue() | Two approaches: Remove and return the item from the front of the queue; or pop off index 0 | O(n) - Performance of obtaining and removing from the beginning of the dynamic array |
| size() | Return the size of the queue | 	O(1) - Performance of returning the size of the dynamic array |
| empty() | Returns true if the length of the queue is zero. | O(1) - Performance of checking the size of the dynamic array |