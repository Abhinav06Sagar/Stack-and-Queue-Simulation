Introduction
In this project, I implemented the Stack and Queue data structures in Python. These are fundamental data structures in computer science that help organize and manage data in different ways.

A Stack follows the Last In, First Out (LIFO) principle.
A Queue follows the First In, First Out (FIFO) principle.
Stack
A Stack is a linear data structure that follows the LIFO principle.

Operations:
Push(item) - Adds an item to the top of the stack.
Pop() - Removes and returns the top item.
Peek() - Returns the top item without removing it.
Is_Empty() - Checks if the stack is empty.
Size() - Returns the stack size.
Real-world Applications:
Undo/Redo functionality in software.
Function call management in programming.
Expression evaluation in compilers.
Queue
A Queue follows the FIFO principle.

Operations:
Enqueue(item) - Adds an item to the end of the queue.
Dequeue() - Removes and returns the front item.
Front() - Returns the front item.
Is_Empty() - Checks if the queue is empty.
Size() - Returns the queue size.
Real-world Applications:
Task scheduling in operating systems.
Print queues for document printing.
Breadth-First Search (BFS) in graph traversal.
Example Usage:
# Stack example
stack = Stack()
stack.push(10)
stack.push(20)
print(stack.pop())  # Outputs: 20
print(stack.peek())  # Outputs: 10

# Queue example
queue = Queue()
queue.enqueue(10)
queue.enqueue(20)
print(queue.dequeue())  # Outputs: 10
print(queue.front())  # Outputs: 20