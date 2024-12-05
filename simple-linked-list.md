# Implementation of a simple linked list

## Introduction

This document contains system requirements for a simple application that implements a linked list. 
In the context of this document a *linked list* is a set of nodes, each node contains a *pointer* to the next node.
There are no loops between nodes. Last node does not contain a pointer to next node (since it is last), also
there is no node that points on the first node. Each node is a *data structure* with the following fields:

- **id** - the identifier of the node
- **data** - some data, usually a string field
- **next** - the pointer to the next node

## General description

The application will operate in a loop. During his work, the user will see the following menu:

- '**a**' - add a new node
- '**r**' - remove a node
- '**u**' - update a node
- '**c**' - count how many nodes are present
- '**e**' - erase the list
- '**s**' - show a specific node (string field)
- '**v**' - view all list
- '**x**' - exit the system

In a pseudo programming language, the node has the following structure:

```
Node {
    id: Integer,
    data: String,
    next: pNode
}
```
where *pNode* is a pointer (special data type) to the node itself. The last node from the list 
will have a special value named NULL for the value of the next field.

## Detailed description of operations

The application will be a simple program that will operate in a loop. 
The system will ask the user which operation he wants to perform. 
Next, the user will enter requested data and the operation will be performed. Also a special command is used to exit the loop and close the application.

### Add a new node

The user will enter the following information

- **id** (the operation will fail if there is already a node with such an id)
- **data**, a string
- **id_after**, the id of the node after which this new one will be added

### Remove a node

The user will enter the id of the node which he wants to remove. The operation will fail if 
such an id does not exit

### Update a node

The user will enter the id of the node he wants to update and new data, which will replace old
data (data field). The operation will fail if there is no such id.

### Count how many nodes are present

The operation will count how many nodes are present in the list and will show the result on the screen. This operation can't fail, if there are no nodes, "0" (zero) will be displayed

### Erase

Will erase all nodes from the list. The memory must be freed. After executing this operation, the operation "count" must show "0". This operation can't fail. If the list is already empty,
the operation must return success.

### Show a specific node

The user will enter the id of the node he wants to see. The field **data** will be shown on the screen. If there is no such id the operation will fail.

### View all list

The content (**data** field) of all nodes will be displayed on the screen. This operation can't fail, if the list is empty, nothing will be shown on the screen.

### Exit the system

The operation is self explanatory.