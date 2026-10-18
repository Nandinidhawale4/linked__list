## problem statement

To implement a Bank Account Management System using stack and queue with dynamic memory allocation in C++. The system stores bank account details such as account number, account holder name, and balance using dynamically allocated linked nodes.
A stack is used to manage account operations in Last In, First Out (LIFO) order, while a queue is used to manage account operations in First In, First Out (FIFO) order. The system supports insertion, deletion, searching, and displaying account details. Dynamic memory allocation allows memory to be allocated and released as required.

## Approach 

 1 Start the program and initialize an empty stack and queue.
 
 2 Display a menu containing account management operations.
 
 3 Create dynamically allocated nodes to store account number, account holder name, and balance.

 4 Use stack operations such as push, pop, and display to manage accounts in LIFO order.
 
 5 Use queue operations such as enqueue, dequeue, and display to manage accounts in FIFO order.
 
 6 Search for an account using its account number.
 
 7 Display the available account details.
 
 8 Release dynamically allocated memory when nodes are deleted or the program ends.
 
 9 Repeat the menu until the user selects the exit option.

 ## complexity

 Time and Space Complexity
 
 Operation                                      Time Complexity
 
Stack Push                                 :-           O(1)

Stack Pop                                  :-           O(1)

Queue Enqueue                              :-           O(1)

Queue Dequeue                              :-           O(1)

Display Accounts                           :-           O(n)

Search Account                             :-           O(n)

Insert at the beginning of a linked list   :-           O(1)

Space Complexity                           :-           O(n)

## conclusion

The Bank Account Management System demonstrates the practical implementation of stack and queue data structures using dynamic memory allocation in C++. The stack follows the LIFO principle, whereas the queue follows the FIFO principle. The system allows account records to be inserted, deleted, searched, and displayed efficiently.
This project improves understanding of linked lists, dynamic memory allocation, pointers, and basic data structure operations. It also demonstrates how stack and queue concepts can be applied to a simple bank account management application.





