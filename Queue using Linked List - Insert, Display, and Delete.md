#  Queue using Linked List - Insert, Display, and Delete

##  Aim
onsider a sales person selling snacks in a glass jar with maximum capacity of 8 snacks. 

1. The sales person filling the jar with 5 snacks.

2. Check and print whether the jar is full?

3. Check whether the jar is empty after selling 3 snacks.

4. Print how many snacks left after sales.
---

##  Algorithm

1. **Create a Queue**:
   - Initialize an empty list named `queue`.

2. **Insert Elements**:
   - Use the `append()` method to insert elements `'a'`, `'b'`, and `'c'` into the queue.

3. **Display Initial Queue**:
   - Print the message `"Queue after elements are inserted:"` followed by the queue contents.

4. **Delete First Element**:
   - Use `pop(0)` to remove the first inserted element (FIFO - First In First Out).
   - Print the message `"Deleting the first element inserted:"` and the element removed.

5. **Display Updated Queue**:
   - Print the message `"Queue after the first element is deleted:"` followed by the updated queue contents.

---

## Program
```

from queue import LifoQueue

stack = LifoQueue(maxsize=8)

stack.put('Snack_1')
stack.put('Snack_2')
stack.put('Snack_3')
stack.put('Snack_4')
stack.put('Snack_5')

print("Present quantity of snacks in the jar: ",stack.qsize(), end=" Snacks")
print("\nIs the jar full? ", stack.full())

print('\nAfter sales:')
print(stack.get())
print(stack.get())
print(stack.get())

print("\nIs the jar empty? ", stack.empty())
print("Current quantity of snacks in the jar: ", stack.qsize(), end=" Snacks")


```

## Output
<img width="966" height="353" alt="image" src="https://github.com/user-attachments/assets/6128dc29-199c-4087-97f8-2e05eabb5f13" />

## Result
The program was executed successfully
