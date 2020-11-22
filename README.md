READ ME for Chandy-Misra-Haas OR Deadlock Detection Algorithm

---Source Code Files----

The file names are as follows - 
->chandy-misra-haas-OR-Model.cpp
->chandy-misra-haas-OR-Model.exe

The files are compiled using DEV C++.

---Execution instructions---

Execute the code directly from Chandy-Misra-Haas-OR-Model.exe file.

Enter the number of proccesses --------------input an integer value greater than 1

Enter the wait graph (enter values only 0 and 1)---------enter input values for the wait for graph(see sample) (n x n, n = no of proccesses)

Enter the proccess initiating the probe (between 1 and no. of proccesses)---------input an integer value

Press any key to exit.

----------Sample Input------------

Enter the number of processes (minimum value greater than 1)
4
Enter the wait graph
0
1
0
0
0
0
1
0
1
0
0
0
0
0
0
0

----------Sample Output------------

The wait-for graph is :

        S1      S2      S3      S4
S1      0       1       0       0<br>
S2      0       0       1       0<br>
S3      1       0       0       0<br>
S4      0       0       0       0<br>

Enter the proccess number intiating the probe (Between 1 and no. of proccesses)
1

Initiating Probe.....

DIRECTION       PROBE
DeadLock detected
