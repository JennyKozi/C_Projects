# Parser and Interpreter for ipl Language

ipl is a programming language with its own syntax that was created for this project.

This program takes as input programs written in ipl, uses a parser to read the code (for syntax errors) and then an interpreter to execute the commands.

The language supports commands such as while, if, else, break, continue,...

Programms written in ipl can be found in the folder programs.

Use the Makefile to compile, run and clean using the following commands:

## Compile Program
```bash
make
```

## Run Program
Use the interpreter to execute different programs written in ipl language:

```bash
./ipli kalmpr.ipl
```
```bash
./ipli selectsort.ipl
```
```bash
./ipli nqueens.ipl
```
```bash
./ipli matrmult.ipl
```
```bash
./ipl numbers.ipl
```

## Clean After Execution
```bash
make clean
```