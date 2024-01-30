# Introduction to Programming: Assignment 4

Individual project

Student: Evgenia Kozi

All the main part of the interpreter has been done.

BONUS:

*Assignment 1 (k-almost primes) in ipl

*Arrays (without the extension of a[b[c[i]]])

*Break - Continue (including the extension break <n>, continue <n> (e.g. continue 2))
  
*Function nl: leaves a blanck line (prints out the character '\n')

Compilation instructions:

gcc -c -o  main.o main.c
  
gcc -c -o parser.o parser.c
  
gcc -c -o interpreter.o interpreter.c
  
gcc -c -o helper.o helper.c

gcc -o ipli main.o parser.o interpreter.o helper.o

Programms written in ipl that can be found on the instructions of Assignment 4:
  
primes.ipl, countdivs.ipl, factorize.ipl, humble.ipl, selectsort.ipl, nqueens.ipl, matrmult.ipl

My programs in ipl: numbers.ipl, kalmpr.ipl

Test Bonus:

*Assignment 1:
  
./ipli kalmpr.ipl

*Arrays:

./ipli selectsort.ipl
 
./ipli nqueens.ipl
  
./ipli matrmult.ipl

*Break - Continue:

./ipl numbers.ipl

*Break - Continue (with the extension <n>):
  
./ipli nqueens.ipl
