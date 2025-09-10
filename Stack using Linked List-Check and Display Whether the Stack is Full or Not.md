# #  Stack using Linked List: Check and Display Whether the Stack is Full or Not

This Python program demonstrates how to check if a stack (using `LifoQueue` from the `queue` module) is full or not. It uses the `full()` method to determine the stack's status and then displays the appropriate message.

##  Aim

To write a Python program that:
- Creates a stack with a fixed size.
- Adds elements to the stack.
- Checks if the stack is full.
- Displays a message indicating whether the stack is full or not.

##  Algorithm

1. **Import the LifoQueue class**:
   - Import `LifoQueue` from the `queue` module to create the stack.

2. **Create a Stack**:
   - Instantiate a `LifoQueue` with a maximum size (e.g., 4).

3. **Add Elements to the Stack**:
   - Add elements (e.g., 'a', 'b', and 'c') to the stack using the `put()` method.

4. **Check if the Stack is Full**:
   - Use the `full()` method of `LifoQueue` to check if the stack has reached its maximum capacity.

5. **Display the Status**:
   - Print "Stack is full" if the stack is full.
   - Otherwise, print "Stack is not full".

##  Program
```
from queue import LifoQueue
max_val = maxsize=10
stack = LifoQueue(max_val)
stack.put('S1')
stack.put('S4')
stack.put('S6')
print("** Check how many seats are occupied **")
print("Number of seats occupied are ", stack.qsize())
print("Number of seats available are ", maxsize - stack.qsize())

if stack.full():
    print("Seats are full")
else:
    print("Seats are not full")

```
## Sample Input & Output
<img width="781" height="218" alt="image" src="https://github.com/user-attachments/assets/ea48d736-70df-4ee2-b912-b8806d82b5b9" />

## Result
The Program was executed successfully
