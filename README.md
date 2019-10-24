A real-world stack allows operations at one end only. For example, 
we can place or remove a card or plate from the top of the stack only. Likewise, 
Stack ADT allows all data operations at one end only. At any given time,
 we can only access the top element of a stack.This feature makes it LIFO data structure. 
 LIFO stands for Last-in-first-out. Here, the element which is placed (inserted or added) last, is accessed first. 
 In stack terminology, insertion operation is called PUSH operation and removal operation is called POP operation.
       Basic operation :
    push() − Pushing (storing) an element on the stack.
    pop() − Removing (accessing) an element from the stack.
When data is PUSHed onto stack.
To use a stack efficiently, we need to check the status of stack as well. For the same purpose, the following functionality is added to stacks −

    peek() − get the top data element of the stack, without removing it.

    isFull() − check if stack is full.

    isEmpty() − check if stack is empty.

