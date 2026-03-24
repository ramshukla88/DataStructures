## [19cb479] - 2024-05-17
### Create hashTable.py

Added a new HashTable data structure implementation with support for basic hash table operations. The implementation features a simple polynomial rolling hash function with a default capacity of 7 buckets. Collision handling is implemented using chaining, where collisions are resolved by storing multiple key-value pairs in a list at each hash bucket. The class provides methods to set items, get items by key, retrieve all keys, and print the internal table structure for debugging purposes.

## [ebcd533] - 2024-05-15
### Create queue.py
Implemented a Queue (FIFO) data structure with Node class supporting enqueue, dequeue, and print_queue operations. The queue maintains references to first and last nodes for efficient front and back operations.

## [df40d18] - 2024-05-14
### dll and stack completed

Added two new core data structure implementations to the project:

**DoublyLinkedList** - A bidirectional linked list implementation with comprehensive node manipulation capabilities. Features optimized `get()` method that searches from the nearest end (head or tail) based on the target index position, improving performance for operations on list elements. Supports append, prepend, pop, pop_first, insert, remove, and value updates at arbitrary indices.

**Stack** - A LIFO (Last-In-First-Out) data structure built on a node-based architecture. Implements standard stack operations including push, pop, and utility methods for visualization. Maintains a height counter for O(1) size queries.

These implementations complement the existing LinkedList and recently added Queue, Tree, and HashTable modules, providing a comprehensive toolkit of fundamental data structures for educational purposes.

## [0f6a829] - 2024-05-07

### Initial commit

This is the initial commit of the repository, establishing the foundational project structure. The repository has been initialized as a blank slate, ready for development and project setup.

#### Repository Structure

- Root directory initialized for project files
- No source code files present in this initial commit
- Ready for addition of project-specific configuration files, source code, and documentation

#### Next Steps

This repository is prepared for the following:

- Addition of project source files and directories
- Configuration of development environment and build tools
- Implementation of project-specific functionality
- Addition of testing frameworks and CI/CD pipelines
- Documentation of project requirements and architecture

#### Notes

This initial commit serves as the foundation for the project. Subsequent commits will build upon this base by adding specific technologies, frameworks, and application logic as the project develops.

# Changelog

All notable changes to this project will be documented in this file.
