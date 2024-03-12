## Introduction
  -high level code like C/Cpp, Cobal, Fortran, java, Lisp, ML, Perl, Python, VB need to be compiled into binary code to excute.
## General structure of compiler
#### Lexical Analyzer
  -get high level code  
  -return tokens
#### Parser
  -get tokens  
  -build syntax tree with operators as its nodes and identifier as its leaf nodes
#### semantic analyzer
  -get syntax tree  
  -check for errors in syntax tree  
    -like undeclared variables, repeated declarations, whether integer of index, wrong operators ...
  -check the type and convert it if needed
  -
