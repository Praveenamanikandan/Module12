# Queue using Linked List: Display Front and Rear Elements of a Queue

##  Aim

To write a Python program to:
- Insert elements into a queue.
- Display the element at the **front** of the queue.
- Display the element at the **rear** of the queue.

---

##  Algorithm

1. **Initialize Queue**:
   - Create an empty list called `queue`.

2. **Insert Elements**:
   - Use the `append()` method to add `'a'`, `'b'`, `'c'`, and `'d'` to the queue.

3. **Display Initial Queue**:
   - Print `"Initial Queue:"` followed by the current state of the queue.

4. **Identify Front and Rear**:
   - Set `front = queue[0]` for the front element.
   - Set `rear = queue[-1]` for the rear element.

5. **Print Results**:
   - Display the front and rear elements with appropriate messages.

---
## Program
```
queue = []

queue.append('a')
queue.append('b')
queue.append('c')

# Display all elements inserted
print('Queue after elements are inserted:')
print(queue)

print('Deleting the first element inserted:')
print(queue.pop(0))

# Display queue after deletion
print('Queue after the first elements is deleted:')
print(queue)


```

## Output
<img width="867" height="279" alt="image" src="https://github.com/user-attachments/assets/585ab583-f438-4766-bf65-6267d0022b99" />

## Result
The Program was executed successfully
