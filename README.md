# OBC - Simple C Compiler
This project implements a compiler for a simplified version of C (only has 2 data types (int,void) does not support recursion, etc)
using python and the Lark library


## Prerequisites

* python 3.7 (3.5 won't work, some source files have literal string interpolation)
* pip

## Installing

Install all dependecies described in `requirements.txt` using pip

```bash
pip3 install -r requirements.txt
```
## Usage
cd to the src directory 

```bash
cd src
```

and call the compiler on some source file

```bash
./obc.py [SOURCE FILE PATH]
```