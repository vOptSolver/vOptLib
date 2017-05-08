# UKP: uncorrelated bi-objective instances 
These are classical instances. 
The costs c1(i), c2(i) and the weights w(i) are generated independently following a uniform distribution in a given set. 
There is no correlation neither between the objective costs, nor between any objective cost and the weight.

## Format
The format of all of these data files is:

    number of variables (n)
    number of objectives (p = 2)
    number of constraints (k = 1)
    cost of item i for objective 1 (i = 1,...,n)
    cost of item i for objective 2 (i = 1,...,n)
    weight of item i (i = 1,...,n)
    total weight of the knapsack W

Lines of comments begin by #.



## Instances:
 
Legend:
+ ID: instance's name
+ INFO: report about the numerical characteristics
+ Y_N: set of non dominated points 
+ X_E_M: Maximum complete set of efficient solutions


***


**Instances referenced 1A** in [1]

The instances are denoted by 2KPn-c.dat where n is the size of the problem, and 0.c is the tightness ratio. 
The objective costs and the weights are generated according to a uniform distribution respectively in {30,...100} and in {20,...500}. 

| ID            | INFO  | Y_N   | X_E_M | 
| ------------- | ----- | ----- | ----- |
| 2KP50-11.dat  | 
| 2KP50-50.dat  |
| 2KP50-92.dat  |
| 2KP100-50.dat |    
| 2KP500-41.dat |

Files contain data from [1]:

> [1] Xavier Gandibleux, Arnaud Freville. Tabu Search Based Procedure for Solving the 0-1 MultiObjective Knapsack Problem: the two objective case. Journal of Heuristics, 6 (3) 361-383, 2000.


***


**Instances referenced 1B/A** in [2]

The instances are denoted by 2KPn-1A.dat where n is the size of the problem. 
The objective costs and the weights are generated according to a uniform distribution in [1,...,100]. 
All instances have a tightness ratio W / (Sum{i=1,...n} w(i)) = 0.5.

| ID            | INFO  | Y_N   | X_E_M | 
| ------------- | ----- | ----- | ----- |
| 2KP50-1A.dat  |
| 2KP100-1A.dat |
| 2KP150-1A.dat |
| 2KP200-1A.dat |
| 2KP250-1A.dat |
| 2KP300-1A.dat |
| 2KP350-1A.dat |
| 2KP400-1A.dat |
| 2KP450-1A.dat |
| 2KP500-1A.dat |

Files contain data from [2]:

> [2] M. Visée, J. Teghem, M. Pirlot and E. L. Ulungu. Two-phases Method and Branch and Bound Procedures to solve the Bi-objective Knapsack Problem. Journal of Global Optimization 12: 139–155 (1998).


***


**Instances referenced 1B/B** in [3]

The instances are denoted by 2KPn-1B.dat where n is the size of the problem. 
The first objective cost and the weights are generated according to a uniform distribution in [1,...,100]. 
The second objective is obtained by taking the objective cost of the first one in reverse order. 
All instances have a tightness ratio W / (Sum{i=1,...n} w(i)) = 0.5.

| ID            | INFO  | Y_N   | X_E_M | 
| ------------- | ----- | ----- | ----- |
| 2KP50-1B.dat  |    
| 2KP100-1B.dat | 
| 2KP150-1B.dat | 
| 2KP200-1B.dat | 
| 2KP250-1B.dat | 
| 2KP300-1B.dat | 
| 2KP350-1B.dat | 
| 2KP400-1B.dat | 
| 2KP450-1B.dat | 
| 2KP500-1B.dat | 

Files contain data from [3]:

> [3] Fabien Degoutin and Xavier Gandibleux. Un retour d'expérience sur la résolution de problèmes combinatoires bi-objectifs. 5e journée du groupe de travail Programmation Mathématique MultiObjectif (PM20), Angers, France, 17 mai 2002.

    
***


**Instances referenced 2/UNCOR** [4]    

The objective costs and the weights of the instances 2/UNCOR are both generated according to a uniform distribution in [1,...,300] or [1,...,1000]. 
All these instances have the same size n = 50. 
These instances are denoted by F5050Wx.dat (instances generated with numbers in [1,...,300]) or K5050Wx.dat (instances generated with numbers in [1,...,1000]), x denotes the number of the instance. 
All instances have a tightness ratio W / (Sum{i=1,...n} w(i)) = 0.5.

| ID            | INFO  | Y_N   | X_E_M | 
| ------------- | ----- | ----- | ----- |
| F5050W01.dat  | 
| F5050W02.dat  | 
| F5050W03.dat  | 
| F5050W04.dat  | 
| F5050W05.dat  | 
| F5050W06.dat  | 
| F5050W07.dat  | 
| F5050W08.dat  | 
| F5050W09.dat  | 
| F5050W10.dat  | 
|               | 
| K5050W01.dat  | 
| K5050W02.dat  | 
| K5050W03.dat  | 
| K5050W04.dat  | 
| K5050W05.dat  | 
| K5050W06.dat  | 
| K5050W07.dat  | 
| K5050W08.dat  | 
| K5050W09.dat  | 
| K5050W10.dat  | 
    
Files contain data from [4]:

> [4] M. E. Captivo, J. Clímaco, J. Figueira, E. Martins and J. L. Santos. Solving bicriteria 0-1 knapsack problems using a labeling algorithm. Computers & Operations Research 30 (2003) 1865–1886.

