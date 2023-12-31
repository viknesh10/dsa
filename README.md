# Data Structures and Algorithms

## Data Structures

### Arrays
#### Pros:
* During lookups
* During push/pop
* Ordered
#### Cons:
* During inserts
* During deletes
* Fixed size arrays

### Hash Tables
#### Pros:
* During lookups - only if hash collision is adjusted for
* Fast inserts
* Flexible keys

#### Cons:
* Ordering - because Hash tables are unordered by default
* Key iteration - because key iteration is very slow

### Linked Lists
#### Pros:
* Fast inserts
* Fast deletes
* Ordered
* Flexible size

#### Cons:
* Slow lookups
* Consumes more memory

### Stacks and Queues
#### Pros:
* Fast operations
* Fast peek
* Ordered

#### Cons:
* Slow lookups

### Binary Search Trees
#### Pros:
* Better than O(n)
* Flexible size
* Ordered

#### Cons:
* No O(1) operations

### Binary Heaps
#### Pros:
* Better than O(n)
* Priority
* Flexible size
* Fast insert

#### Cons:
* Slow lookups

### Graphs
#### Pros:
* Relationships

#### Cons:
* Scaling is hard

## Algorithms

### Recursion
#### Pros:
* DRY (Don't Repeat Yourself) - enable reusability
* Readability

#### Cons:
* Large stack
* Space complexity

### Breadth-first Search (BFS)
#### Pros:
* Shortest path
* Closer nodes

#### Cons:
* Space complexity - takes more memory

### Depth-first Search (BFS)
#### Pros:
* Lesser memory
* Asks a question of "Does the path exist from one node to the other"

#### Cons:
* Time complexity - can get slow