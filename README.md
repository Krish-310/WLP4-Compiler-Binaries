# WLP4-Compiler-Binaries

This repository contains the binaries for the WLP4 Compiler developed as part of the CS241 Course at the University of Waterloo. The source code is not public, but 

The specifications for the WLP4 Language can be found here - It is a subset of the C Programming Language

## Usage of each binary file

asm - An assembler that converts basic MIPS code into binary

smm - An implementation of Simplified Maximal Munch used in a scanner

wlp4scan - A scanner for the WLP4 Language that uses Simplified Maximal Munch in its implementation

wlp4parse - A parser for the WLP4 Langauge that takes in the tokenized output from 'wlp4scan' and returns a parse tree for the given code

wlp4type - This binary performs type checking on the parse tree generated from 'wlp4parse' and assigns types of each variable in the parse tree

wlp4gen - A code generator that takes in the 'typed' parse tree from 'wlp4type' and generates MIPS code for given code, which can then be assembled into a binary
