# Ex.No 12.b Stack Using Linked List – Push and Index Display

## Aim

To write a Python program to insert 3 elements into a stack and display the index value of each element stored in the stack.

## Algorithm

1. Start  
2. Create a stack  
3. Append elements to the stack  
4. Use a loop to print the index and value of each element in the stack  
5. Print the result  
6. Stop

## Program

```python
stack = []

# Push elements into the stack
stack.append('a')
stack.append('b')
stack.append('c')

# Display the initial stack
print('Initial stack:', stack)

# Print index and element
for i in range(len(stack)):
    print(i, stack[i])
```

## Output

![447845887-179d1ecb-2092-4ed4-84f4-f40621474d49](https://github.com/user-attachments/assets/9601efaa-dba7-4efe-a2e4-207506654246)


## Result

Thus, the given program is implemented and executed successfully.
