# Red-Black Tree Implementation Using C

## Project Description

Developed a Red-Black Tree data structure using C programming to efficiently store, search, insert, and delete elements while maintaining a self-balancing binary search tree structure.

A Red-Black Tree is a self-balancing Binary Search Tree (BST) in which each node is assigned a colour, either red or black. These colour properties help maintain the balance of the tree and ensure efficient searching, insertion, and deletion operations.

Implemented the Red-Black Tree using dynamically allocated nodes and pointer-based data structures. Each node maintains data, colour information, and left and right child pointers.

Implemented insertion and deletion operations with balancing mechanisms using left rotation, right rotation, and recolouring techniques to maintain Red-Black Tree properties after modifications.

The implementation includes helper functions for checking node colours, identifying red-red violations, performing rotations, and restoring tree balance. Also implemented tree traversal operations to display elements in sorted order.

## Key Features

- Creates a self-balancing Binary Search Tree.
- Supports insertion of new nodes.
- Supports deletion of existing nodes.
- Searches for elements efficiently.
- Maintains Red-Black Tree properties.
- Implements left and right rotations.
- Performs recolouring to restore tree balance.
- Handles different insertion balancing cases.
- Supports tree traversal operations.
- Uses dynamic memory allocation for node creation and deletion.
- Maintains balanced tree height for efficient operations.

## Technologies Used

- Programming Language: C
- Data Structure: Red-Black Tree
- Concepts: Binary Search Tree, Self-Balancing Trees, Dynamic Memory Allocation, Pointers, Structures, Recursion, Tree Rotations, Recolouring.

## C Programming Concepts Implemented

- Structure-based node creation.
- Dynamic memory allocation using `malloc()` and `free()`.
- Pointer manipulation for tree connections.
- Recursive insertion and deletion.
- Left and right tree rotations.
- Node colour management.
- Tree traversal techniques.
- Modular programming using separate helper functions.

## Time Complexity

| Operation | Average/Worst-case |
|---|---|
| Search | O(log n) |
| Insertion | O(log n) |
| Deletion | O(log n) |
| Traversal | O(n) |
| Left Rotation | O(1) |
| Right Rotation | O(1) |

## Learning Outcomes

Gained practical experience in implementing self-balancing tree data structures and understanding the internal working of Red-Black Trees. Improved knowledge of binary search trees, tree rotations, recolouring, recursion, dynamic memory allocation, pointer manipulation, and algorithm optimization. Developed problem-solving skills by implementing insertion and deletion balancing mechanisms in C.
