# Deque

## Introduction
It allows insertion and deletion from both ends. It doesn't follow the FIFO rule. It's also known as double-ended queue.

Operations - 
1. push_front()
2. push_back()
3. pop_front()
4. pop_back()
5. front()
6. back()
7. empty()
8. size()

All these are performed in O(1).

### Applications

1. Can be used as both stack and queue
2. It supports clockwise and anticlockwise operations in O(1) time which can be useful in certain applications
3. The problems where elements need to be removed and or added to both ends can be efficiently solved using Deque. For example see the Maximum of all subarrays of size k problem., 0-1 BFS, and Find the first circular tour that visits all petrol pumps
4. Storing a web browser's history - recently visited URLs are added to the front of the deque and the URL at the back of the deque is removed after some specified number of operations of insertions at the front.
5. Undo redo app
6. Job scheduling algorithm
7. Palindrome Checking - Deques can be used to check if a word or phrase is a palindrome. By inserting each character of the word or phrase into a deque, it is possible to check if the word or phrase is a palindrome by comparing the first and last characters, the second and second-to-last characters, and so on.
8. Graph traversal: Deques can be used to implement Breadth-First Search (BFS) on a graph. BFS uses a queue to keep track of the vertices to be visited next, and a deque can be used as an alternative to a queue in this case.
9. Task scheduler: Deques can be used to implement a task scheduler that keeps track of tasks to be executed. Tasks can be added to the back of the deque, and the scheduler can remove tasks from the front of the deque and execute them.


### Language Support
C++ implements it as std::deque