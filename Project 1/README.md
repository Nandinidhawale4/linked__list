## Title
Bank Account Management Using Singly Linked List

## Problem statement 

To implement a singly linked list in C++ to maintain bank account records. Each node stores the account number, account holder name, and account balance. The program performs insertion, deletion, searching, and display operations on bank account records using dynamic memory allocation.

## Objective 

To implement a singly linked list in C++.
To store bank account details dynamically.
To perform insertion, deletion, and searching operations.
To display all bank account records.
To understand pointers and dynamic memory allocation.

## AlgorithM

1. Start and initialize "head = NULL".
2. Create a node containing the account number, account holder name, and balance.
3. Insert the new node at the beginning of the linked list.
4. Search for the required account number and delete the node by adjusting links.
5. Traverse the linked list to search for an account number.
6. Display all account records by traversing from "head" to "NULL".
7. Repeat operations according to the user's choice.
8. Stop.

## time complexity
Operation	
Time Complexity 

Insertion (at Beginning)       O(1)	
Insertion (at End)	           O(N)
Deletion	                     O(N)
Searching	                     O(N)
Display All	                   O(N)	

## conclusion

By implementing the Bank Account Management System using a singly linked list in C++, the fundamental concepts of dynamic memory allocation and pointer manipulation are successfully applied to a real-world scenario. Unlike static arrays, the linked list structure allows bank records to be added or removed dynamically without wasting memory or requiring predefined limits. Developing core operations such as insertion, deletion, searching, and display provides a practical understanding of linear data structures, algorithm efficiency, and sequential data traversal, establishing a solid foundation for managing more complex dynamic databases.
