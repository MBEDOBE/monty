# 0x19.C - Stacks, Queues - LIFO, FIFO

## Description
In this team project we are tasked to create an interpreter for Monty ByteCode files. These files will have commands per line to manipulate the data structure given.

ow to work with git submodules

---

## Files

### [monty.c](./monty.c)
* Contains the main function that takes in the file and runs the parser.

### [monty.h](./monty.h)
* Header file.

### [parse.c](./parse.c)
* Functions that parses the file from main, then parses the lines. While parsing, data is stored into structs to be passed onto other functions.

### [verify.c](./verify.c)
* Contains functions that checks arguments from lines of the file. Checks for if push function is in the file line.

### [match.c](./match.c)
* Our get operations function that matches the aruguments with what opcode function we need to run.

### [funct_1.c](./funct_1.c)
* Contains push, pall, free_stack, and nop.

### [funct_2.c](./funct_2.c)
* Contains pint, pop, swap, pchar, and pstr.

### [funct_3.c](./funct_3.c)
* Contains rotl, rotr, qpush.

### [funct_4.c](./funct_4.c)
* Contains add, sub, div, mul, mod.

### [funct_5.c](./funct_5.c)
* Contains stack and queue.

---

## Tasks

### 0. push, pall
* Implement the push and pall opcodes.
* The opcode push pushes an element to the stack.
* The opcode pall prints all the values on the stack, starting from the top of the stack.

### 1. pint 
* Implement the pint opcode 
* The opcode pint prints the value at the top of the stack, followed by a new line.

### 2. pop
* Implement the pop opcode.
* The opcode pop removes the top element of the stack.

### 3. swap 
* Implement the swap opcode
* The opcode swap swaps the top two elements of the stack.

### 4. add
* Implement the add opcode
* The opcode add adds the top two elements of the stack.

### 5. nop 
* Implement the nop opcode
* The opcode nop doesn't do anything 

## Authors/Collaborators
[D. Mbedobe KUNJI](https://github.com/mbedobe) || [Adowarim Lugu](https://github.com/lugu22)
