# OShw-BankersAlgorithm
- Description:
Write a multithreaded program that implements the banker’s algorithm. 
This assignment combines three topics: (1) multithreading (2) preventing race conditions (3) deadlock avoidance.
Create n customer threads that request and release resources from the bank. The customers will continually loop, requesting and then releasing random numbers of resources. The banker will grant a request if it satisfies the safety algorithm.
Since multiple threads will concurrently access shared data, access must be controlled through mutex locks to prevent race conditions.
Iinvoke your program by passing the number of resources of each type on the command line.


- Steps:
1. Compile **Bankers.c** with ```gcc Bankers.c -lpthread -o Bankers.o```
2. Run program with command line ```./Bankers.o numberOfResource1, numberOfResource2, numberOfResource3```

- Output Screenshot:
