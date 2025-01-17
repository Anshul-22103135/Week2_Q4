This project's documentation is of the project taken from [here](https://github.com/afaq-ahmed07/Prim-and-Kruskal)

# Prim and Kruskal's Algorithm Implementation

This project implements Prim's and Kruskal's algorithms for finding the Minimum Spanning Tree (MST) in a graph. It includes basic data structures such as linked lists, queues, and stacks to support the algorithms.

## Contents

- Kruskal.cpp: Implementation of Kruskal's algorithm.
- Prims.cpp: Implementation of Prim's algorithm.
- Linked_List.h: Implementation of a generic linked list.
- Linked_list_prim.h: Linked list implementation tailored for Prim's algorithm.
- Queue.h: Implementation of a queue data structure.
- Stack.h: Implementation of a stack data structure.

## Functions of each file explained

### Kruskal.cpp

Implements Kruskal's algorithm for finding the MST in a graph.

- **Edge**: Represents an edge in the graph.
  - `Edge(int u, int v, int weight)`: Constructor to initialize an edge.
- **Graph**: Represents a graph.
  - `Graph(int vertices)`: Constructor to initialize a graph.
  - `void addEdge(int u, int v, int weight)`: Adds an edge to the graph.
  - `int find(int i)`: Find function for the disjoint set.
  - `void union_set(int u, int v)`: Union function for the disjoint set.
  - `void KruskalMST()`: Implements Kruskal's algorithm to find the MST.

### Prims.cpp

Implements Prim's algorithm for finding the MST in a graph.

- **Graph**: Represents a graph.
  - `Graph(int vertices)`: Constructor to initialize a graph.
  - `void addEdge(int u, int v, int weight)`: Adds an edge to the graph.
  - `int minKey(int key[], bool mstSet[])`: Finds the vertex with the minimum key value.
  - `void printMST(int parent[])`: Prints the constructed MST.
  - `void primMST()`: Implements Prim's algorithm to find the MST.

### Linked_List.h

Provides the implementation of a generic linked list data structure.

- **LinkedList**: Represents a linked list.
  - `LinkedList()`: Constructor to initialize a linked list.
  - `void insert(int data)`: Inserts a new node with the given data.
  - `void deleteNode(int key)`: Deletes the first node with the given key.
  - `void printList()`: Prints the linked list.

### Linked_list_prim.h

Linked list implementation specifically for Prim's algorithm.

- **LinkedListPrim**: Represents a linked list tailored for Prim's algorithm.
  - `LinkedListPrim()`: Constructor to initialize a linked list.
  - `void insert(int data)`: Inserts a new node with the given data.
  - `void deleteNode(int key)`: Deletes the first node with the given key.
  - `void printList()`: Prints the linked list.

### Queue.h

Provides the implementation of a queue data structure.

- **Queue**: Represents a queue.
  - `Queue(int size)`: Constructor to initialize a queue with a given size.
  - `void enqueue(int item)`: Adds an item to the queue.
  - `int dequeue()`: Removes and returns the front item from the queue.
  - `bool isEmpty()`: Checks if the queue is empty.
  - `bool isFull()`: Checks if the queue is full.

### Stack.h

Provides the implementation of a stack data structure.

- **Stack**: Represents a stack.
  - `Stack(int size)`: Constructor to initialize a stack with a given size.
  - `void push(int item)`: Adds an item to the stack.
  - `int pop()`: Removes and returns the top item from the stack.
  - `bool isEmpty()`: Checks if the stack is empty.
  - `bool isFull()`: Checks if the stack is full.

