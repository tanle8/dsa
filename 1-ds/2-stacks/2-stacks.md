# Basics of Stacks

1. Definition
2. Inserting and deleting elements
3. Features and stacks
4. Operations

    4.1. push(x)
    4.2. pop(x)
    4.3. topElement()
    4.4. isEmpty
    4.5. size()

5. Implementation
6. Application

## 1. Definition

__Stacks__ are _dynamic_ data structures that follow the __Last In, First Out (LIFO)__ principle. The last item to be inserted into a stack is the first one to be deleted from it.

- For example:

    You have a stack of trays on a table. The tray at the top of the stack is the _first_ items to be moved if you require a tray from that stack.

## 2. Inserting and deleting elements

Stacks have restrictions on the insertion and deletion of elements.

Elements can be inserted or deleted only from one end of the stack i.e. from the ___top___.

The element at the top is called the __top__ element. The operations of inserting and deleting elements are called $push()$ and $pop()$ respectively.

When the top element of a stack is deleted, if the stack remains non-empty, then the element just below the previous top element becomes the new top element of the stack.

- For example:

    In the stack of trays, if you take the tray on the top and do not replace it, then the second tray automatically becomes the top element (tray) of that stack.