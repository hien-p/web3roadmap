# Understanding-fractals

## Tokenization and Parsing:
The process begins by decomposing a Solidity script into tokens, which represent the basic elements of the script, such as variables, functions, and control structures. Parsing these tokens involves analyzing the syntactical structure of the Solidity code and organizing the elements into an Abstract Syntax Tree (AST), which depicts the code’s logical and organizational flow.

## Abstract Syntax Tree (AST):
The AST is a tree representation of the syntactic structure of the Solidity code. It details the hierarchy of operations and the interrelations between different code segments, critical for grasping the program’s logic and flow.

## Intermediate Language (IL):
Once the AST is constructed, the code is translated into an Intermediate Language (IL). This IL is a simpler yet detailed representation of the program that bridges the gap between high-level Solidity code and the lower-level instructions needed for execution.

## MoveVM Opcodes:
The IL is then interpreted into operation codes (opcodes) for MoveVM. These opcodes are the fundamental instructions that the virtual machine comprehends and executes, dictating the specific operations MoveVM should perform.

## MoveVM Bytecode:
In the final phase, the opcodes are converted into MoveVM bytecode. This bytecode is the executable binary representation of the program, fully interpreted from the original Solidity script, and prepared to run in the secure and resource-oriented environment of MoveVM.


# References 
- [@article@Movement SDK blog](https://blog.movementlabs.xyz/article/movement-sdk-unifying-the-blockchain-universe-2)