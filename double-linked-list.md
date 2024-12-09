# Implementation of a double linked list

## Introduction

This document is nearly identical to [this document](simple-linked-list.md). 

The key difference is that each element in the list must be doubly linked. This means each node must include a pointer to both the previous and the next node. The first node will have a `null` value for its previous node, while the last node will have a `null` value for its next node. Each node is a data structure with the following fields:

- **id** - the identifier of the node
- **data** - some data, usually a string field
- **next** - the pointer to the next node
- **prev** - the pointer to the previous node

All operations remain the same as those described in [this document](simple-linked-list.md).
