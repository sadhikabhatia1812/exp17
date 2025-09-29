Aim
To study and implement Linked List in C++.

Theory
A Linked List is a linear data structure in which elements, called nodes, are stored in memory dynamically and are connected using pointers. Unlike arrays, linked lists do not require contiguous memory locations, making insertion and deletion operations more efficient.

Each node in a linked list consists of two parts:
Data → Stores the actual information.
Pointer (next) → Stores the address of the next node.

The first node of a linked list is called the head. If the list is empty, the head is NULL. The last node points to NULL, marking the end of the list.

Types of Linked Lists
Singly Linked List → Each node points to the next node only.
Doubly Linked List → Each node points to both the next and previous nodes.
Circular Linked List → The last node points back to the first node.

Advantages of Linked List
Dynamic memory allocation (size can grow/shrink during runtime).
Efficient insertion and deletion compared to arrays.

Disadvantages
Extra memory is required for storing pointers.
Traversing is slower (no direct indexing like arrays).

Applications:
Used in memory management.
Implementation of stacks, queues, and graphs.
Efficient for dynamic data structures.

ALGORITHM:-
Program 1: Creating a Single Node
Define a Node structure with data and next.
Dynamically create a new node.
Assign data = 10 and next = NULL.
Display the node data.

Program 2: Insertion at the Beginning
Define a Node structure.
Create a function insertStart() that inserts a new node at the beginning:
Create a new node with given value.
Point its next to the current head.
Update head to the new node.
Create a function display() to traverse and print the list.
Insert multiple nodes at the start and display.

Program 3: Insertion at the End
Define a Node structure.
Create a function insertEnd() that inserts a new node at the end:
Create a new node with given value.
If the list is empty, make it the head.
Otherwise, traverse till the last node and attach the new node.
Create a display() function to traverse and print the list.
Insert multiple nodes at the end and display.

CONCLUSION:-
A linked list is a dynamic data structure where nodes are connected using pointers.
We successfully implemented:
Creation of a single node.
Insertion of nodes at the beginning.
Insertion of nodes at the end.
The programs demonstrated how linked lists are more flexible than arrays in terms of dynamic memory usage.
Thus, the concept of Linked List in C++ has been successfully studied and implemented.
