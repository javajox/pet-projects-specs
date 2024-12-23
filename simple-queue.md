# Implement a simple queue

## Introduction

This document contains system requirements for a simple application that implements a queue. The queue is using FIFO strategy. In order to simplify the things, the elements of queue will be simple integers.

## General description

The following operations must be supported:

- **create** - create a new queue
- **destroy** - destroy the given queue
- **peek** - views the front element without removing it
- **get size** - returns the current number of elements
- **enqueue** - adds an element to the rear of the queue
- **dequeue** - removes and returns the element from the front

## Implementation details    

The implementation must be a library, so it can be included in other projects.
 As backend for the queue, a simple linked list can be used