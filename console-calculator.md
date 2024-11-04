# A simple console based calculator

## Introduction

This document contains system requirements for a simple console based calculator. The calculator will operate on integers only. The following operations must be supported (remark - division is not supported):

- [Sum] - Will add two integers. Example: 356 + 27 = 383

- [Difference] - Will substract two integers. Example: 485 - 129 = 356

- [Multiply] - Will multiply two integers. Example: 312 * 34 = 10608

During his work, the user will see the following menu:

    'a' - add two integers
    'd' - substract two integers
    'm' - multiply two integers
    'x' - exit the system

## General description

The calculator will be a simple console application which will operate in a loop. The system will ask the user which operation he wants to perform and will ask him to input the operands. Also a special command will be used to exit the loop and close the application.

## Detailed description of operations

### Add two integers

In order to add two integers the user will invoke "add" operation by pressing '**a**' key. The system will ask for the first and second operand. After having both operands the system will perform "addition" on integers.

### Substract two integers

In order to substract two integers the user will invoke "substract" operation by pressing '**d**' key. The system will ask for the first and second operand. The first operand will pe *op1* and second one *op2*. After having both operands the system will substract *op2* from *op1*.

### Multiply two integers

In order to multiply two integers the user will invoke "multiply" operation by pressing '**m**' key. The system will ask for the first and second operand. After having both operands the system will perform "multiply" on integers. 

### Exit the system

By pressing '**x**' (from eXit) key, the user will exit from system

## Errors

Special attention must be paid to the data inputed by user. The system must handle situations when wrong operations are invoked or/and wrong data types are entered.

Also special attention must be paid when the result of an operation is outside of scope of the current data type

## Additional requirements

As additional requirements could be the color of the text in console. In the following way:

 - Standard informative messages and text is *green* (text by default)
 - Input provided by user : *yellow*
 - Error messages : *red*