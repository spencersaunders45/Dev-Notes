# Maps
***

## Properties
-

| Common Map Operation | Description | Performance |
| --- | --- | --- |
| put(key, value) | Adds (or replaces) a row in the map with the specified key and value. | O(1) - Performance of hashing the key (assuming good conflict resolution) and assigning the value |
| get(key) | Gets the value for the specified key. | O(1) - Performance of hashing the key (assuming good conflict resolution) and getting the associated value |
| remove(key) | Removes the row from the map containing the specified key. | O(1) - Performance of hashing the key (assuming good conflict resolution) and removing the associated value |
| member(key) | Determines if "key" is in the map. | O(1) - Performance of hashing the key (assuming good conflict resolution) |
| size() | Returns the number of items in the map. | O(1) - Performance of returning the size of the map |