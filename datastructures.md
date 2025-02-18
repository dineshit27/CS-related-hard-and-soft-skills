# Data Structures and Space & Time Complexity

![](https://miro.medium.com/max/10000/1*wv3W3jYq7EHCDiwYVaCXrA.png)

## Array

|         | Access | Search | Insertion | Deletion | Space |
| ------- | ------ | ------ | --------- | -------- | ----- |
| Average | O(1)   | O(n)   | O(n)      | O(n)     |       |
| Worst   | O(1)   | O(n)   | O(n)      | O(n)     | O(n)  |

## Stack

|         | Access | Search | Insertion | Deletion | Space |
| ------- | ------ | ------ | --------- | -------- | ----- |
| Average | O(n)   | O(n)   | O(1)      | O(1)     |       |
| Worst   | O(n)   | O(n)   | O(1)      | O(1)     | O(n)  |

## Queue

|         | Access | Search | Insertion | Deletion | Space |
| ------- | ------ | ------ | --------- | -------- | ----- |
| Average | O(n)   | O(n)   | O(1)      | O(1)     |       |
| Worst   | O(n)   | O(n)   | O(1)      | O(1)     | O(n)  |
| Worst   | O(n)   | O(n)   | O(1)      | O(1)     | O(n)  |

## Singly-Linked List

|         | Access | Search | Insertion | Deletion | Space |
| ------- | ------ | ------ | --------- | -------- | ----- |
| Average | O(n)   | O(n)   | O(1)      | O(1)     |       |
| Worst   | O(n)   | O(n)   | O(1)      | O(1)     | O(n)  |

## Doubly-Linked List

|         | Access | Search | Insertion | Deletion | Space |
| ------- | ------ | ------ | --------- | -------- | ----- |
| Average | O(n)   | O(n)   | O(1)      | O(1)     |       |
| Worst   | O(n)   | O(n)   | O(1)      | O(1)     | O(n)  |

## Hash Table

|         | Access | Search | Insertion | Deletion | Space |
| ------- | ------ | ------ | --------- | -------- | ----- |
| Average | N/A    | O(1)   | O(1)      | O(1)     |       |
| Worst   | N/A    | O(n)   | O(n)      | O(n)     | O(n)  |

## Binary Search Tree

|         | Access    | Search    | Insertion | Deletion  | Space |
| ------- | --------- | --------- | --------- | --------- | ----- |
| Average | O(log(n)) | O(log(n)) | O(log(n)) | O(log(n)) |       |
| Worst   | O(n)      | O(n)      | O(n)      | O(n)      | O(n)  |

## B-Tree

|         | Access    | Search    | Insertion | Deletion  | Space |
| ------- | --------- | --------- | --------- | --------- | ----- |
| Average | O(log(n)) | O(log(n)) | O(log(n)) | O(log(n)) |       |
| Worst   | O(log(n)) | O(log(n)) | O(log(n)) | O(log(n)) | O(n)  |

## Red-Black-Tree

Subset of Binary Search Tree

Properties:
- self-balancing on insert & remove

|         | Access    | Search    | Insertion | Deletion  | Space |
| ------- | --------- | --------- | --------- | --------- | ----- |
| Average | O(log(n)) | O(log(n)) | O(log(n)) | O(log(n)) |       |
| Worst   | O(log(n)) | O(log(n)) | O(log(n)) | O(log(n)) | O(n)  |

Applications:
- Completely Fair Scheduler in Linux
- Computational Geometry
- Functional Programming -> Persistent data structures
- Associative Array (HashSet, Dictionary, Map)