# DataStructures

A Python implementation of common data structures including linked lists, doubly linked lists, stacks, and queues.

## Implemented Data Structures

### Linked List (`linkedlist.py`)
A singly linked list implementation with basic operations.

### Doubly Linked List (`doublyLinkedList.py`)
A doubly linked list implementation supporting traversal in both directions.

### Stack (`stack.py`)
A Last-In-First-Out (LIFO) stack implementation.

### Queue (`queue.py`)
A First-In-First-Out (FIFO) queue implementation with the following operations:
- **enqueue(value)**: Adds an element to the back of the queue
- **dequeue()**: Removes and returns the element from the front of the queue
- **print_queue()**: Prints all elements in the queue in order

## Usage

```python
from queue import Queue

# Create a queue and add elements
my_queue = Queue(1)
my_queue.enqueue(2)
my_queue.enqueue(3)

# Print queue contents
my_queue.print_queue()  # Output: 1 2 3

# Remove from queue
node = my_queue.dequeue()
print(node.value)  # Output: 1
```

## Project Structure

Each data structure is implemented as a standalone module with its own Node and container class. All implementations use linked node architecture for dynamic memory allocation.