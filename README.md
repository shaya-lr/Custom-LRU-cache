# Custom-LRU-cache
This project implements a Least Recently Used (LRU) Cache using a doubly linked list and a hash map for efficient caching operations.

### Key Features:
1. **Capacity Management**: The cache holds a fixed number of elements and evicts the least recently used items when the capacity is exceeded.
2. **Get/Put Operations**: 
   - `get(key)`: Retrieves the value of the key if it exists, or returns `-1`.
   - `put(key, value)`: Inserts/updates the key-value pair and manages eviction when necessary.

### Usage:
Initialize with `LRUCache(capacity)` and use `put()` and `get()` for cache operations.
