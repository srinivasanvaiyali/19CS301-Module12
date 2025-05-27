12E EX: Get 3 inputs from the user and insert in the stack
## AIM:
Type a python code to get 3 inputs from the user and insert in the stack. Print the 3 elements along with the respective index values.

## ALGORITHM:
Step 1:Start Step 2:Define a node structure with data, prev, and next. Step 3:Create a class for the Doubly Linked List (DLL) with a head pointer. Step 4:Define a method insert_at_beginning(data): Create a new node with the given data. Set the next of the new node to current head. If the list is not empty, set prev of current head to the new node. Set head to the new node. Step 5:Optional: Define a method to display the list. Step 6:Call the function and test insertion. Step 7:End

## Program:
```
stack = []
print("Insert the first element:")
stack.append(input())
print("Insert the second element:")
stack.append(input())
print("Insert the third element:")
stack.append(input())

print('Initial stack: ' + str(stack))
for i in range(len(stack)):
    print(i,stack[i])
```
OUTPUT:
![image](https://github.com/user-attachments/assets/b2039f38-fabe-4800-897a-481fd941d5c2)


RESULT:
Thus, the given program is implemented and executed successfully .
