# A simple console based calculator

## Introduction

This document contains system requirements for a simple console based calculator. The calculator will operate on integers only. The following operations must be supported (remark - division is not supported):

- [Sum] - Adds two integers. Example: 356 + 27 = 383

- [Difference] - Subtracts one integer from another. Example: 485 - 129 = 356

- [Multiply] - Multiplies two integers. Example: 312 * 34 = 10608

During his work, the user will see the following menu:

    'a' - add two integers
    's' - subtract two integers
    'm' - multiply two integers
    'x' - exit the system

## General description

The calculator will be a simple console application, which will operate in a loop. The system will ask the user which operation he wants to perform and will ask him to input the operands. Also a special command is used to exit the loop and close the application.

## Detailed description of operations

### Add two integers

To add two integers the user invokes "add" operation by pressing '**a**' (**a** from **a**dd) key. The system asks for the first and second operand. After receiving both operands the system will perform "addition" on integers.

### Subtract two integers

To subtract two integers the user invokes "subtract" operation by pressing '**s**' (**s** from **s**ubtract) key. The system asks for the first and second operand. The first operand will be *op1* and second one *op2*. After receiving both operands the system will subtract *op2* from *op1*.

### Multiply two integers

To multiply two integers the user invokes "multiply" operation by pressing '**m**' (**m** from **m**ultiply) key. The system asks for the first and second operand. After receiving both operands the system will perform "multiply" operation on integers. 

### Exit the system

By pressing '**x**' (from e**X**it) key, the user will exit from system.

## Errors

Special attention should be given to the data input by user. The system must handle situations when invalid operations or incorrect data types are entered.

Also special attention should be given when the result of an operation is outside the scope of the current data type

## Additional requirements

As additional requirements include the color of the text in console:

 - Standard informative messages and text is : *green* (text by default)
 - Input provided by user : *yellow*
 - Error messages : *red*
