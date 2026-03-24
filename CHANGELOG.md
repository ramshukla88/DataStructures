## [19cb479] - 2024-05-17
### Create hashTable.py

Added a new HashTable data structure implementation with support for basic hash table operations. The implementation features a simple polynomial rolling hash function with a default capacity of 7 buckets. Collision handling is implemented using chaining, where collisions are resolved by storing multiple key-value pairs in a list at each hash bucket. The class provides methods to set items, get items by key, retrieve all keys, and print the internal table structure for debugging purposes.

## [ebcd533] - 2024-05-15
### Create queue.py
Implemented a Queue (FIFO) data structure with Node class supporting enqueue, dequeue, and print_queue operations. The queue maintains references to first and last nodes for efficient front and back operations.
