# OShw-BankersAlgorithm
- Description:
Write a multithreaded program that implements the banker’s algorithm. 
This assignment combines three topics: (1) multithreading (2) preventing race conditions (3) deadlock avoidance.<br />
Create n customer threads that request and release resources from the bank. The customers will continually loop, requesting and then releasing random numbers of resources. The banker will grant a request if it satisfies the safety algorithm.<br />
Since multiple threads will concurrently access shared data, access must be controlled through mutex locks to prevent race conditions.<br />
Iinvoke your program by passing the number of resources of each type on the command line.


- Steps:
1. Compile **Bankers.c** with ```gcc Bankers.c -lpthread -o Bankers.o```
2. Run program with command line ```./Bankers.o numberOfResource1, numberOfResource2, numberOfResource3```

- Output Screenshot:
![1](https://github.com/YCtw/OShw-BankersAlgorithm/assets/85775331/f5f1dd52-7b97-448d-a99f-126814d20421)
![2](https://github.com/YCtw/OShw-BankersAlgorithm/assets/85775331/3c3bc1bc-d900-4083-bdd0-150a13c1a28f)
![3](https://github.com/YCtw/OShw-BankersAlgorithm/assets/85775331/831c0e8f-9051-4dca-b518-30e68e93d264)
![4](https://github.com/YCtw/OShw-BankersAlgorithm/assets/85775331/2b8983f6-370f-44c7-9372-49d81f8eb660)
![5](https://github.com/YCtw/OShw-BankersAlgorithm/assets/85775331/0f3d99df-460f-4efe-ae77-762dcaed68e1)
![6](https://github.com/YCtw/OShw-BankersAlgorithm/assets/85775331/a68e6140-56b7-470d-a881-c7f14bbde757)
![7](https://github.com/YCtw/OShw-BankersAlgorithm/assets/85775331/f9de581b-80c9-4315-a7ab-af394cca2ba0)
![8](https://github.com/YCtw/OShw-BankersAlgorithm/assets/85775331/2a2b2ade-0c2e-465b-a021-ed92396bdb9a)
