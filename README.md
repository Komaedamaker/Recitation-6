# Queue and Stack Implementation with Linked Lists

This project demonstrates the implementation of a queue and a stack using linked lists in C++. It includes functionalities for enqueueing, dequeueing, pushing, popping, and validating balanced parentheses.

---

## File Overview

### `QueueLL.hpp` and `QueueLL.cpp`
**Implements a queue with linked list nodes.**
- `QueueLL()`, `~QueueLL()`: Constructor and destructor.
- `isEmpty()`: Checks if the queue is empty.
- `enqueue(int key)`: Adds an element to the queue.
- `dequeue()`: Removes the front element.
- `peek()`: Returns the front element.

---

### `StackLL.hpp` and `StackLL.cpp`
**Implements a stack with linked list nodes.**
- `StackLL()`, `~StackLL()`: Constructor and destructor.
- `isEmpty()`: Checks if the stack is empty.
- `push(char key)`: Adds an element to the stack.
- `pop()`: Removes the top element.
- `peek()`: Returns the top element.

---

### `DriverQueue.cpp`
**Tests queue functionality:**
1. Verifies if the queue is empty initially.
2. Enqueues elements (1, 2, 3).
3. Tests `peek` and `dequeue` operations.

---

### `DriverStack.cpp`
**Tests stack functionality:**
1. Implements `isValid(string input)` to check for balanced parentheses (`{}`, `()`, `[]`).
2. Accepts user input to validate parentheses and prints results.

---

## Usage

### Compile
```bash
g++ QueueLL.cpp DriverQueue.cpp -o queue
g++ StackLL.cpp DriverStack.cpp -o stack
