# UKP: class of instances with repeated costs

This series proposes two subclasses of instances namely 1B-C and 1B-D in [1], where the costs are repeated several times in consecutive items for both objectives. 

This kind of instances have been proposed in [1]:

> [1] Fabien Degoutin and Xavier Gandibleux. 
 Un retour d'expérience sur la résolution de problèmes combinatoires bi-objectifs. 
 5e journée du groupe de travail Programmation Mathématique MultiObjectif (PM20), Angers, France, 17 mai 2002. 


+ Generation of instances of class C:

    The length $`l`$ of a plateau is generated following an uniform distribution in {1,...,0.1n} where $`n`$ is the size of the problem. 
A cost is generated following an uniform distribution in {1,...,100} and is repeated $`l`$ times. 
The weights are generated independently following an uniform distribution in {1,...,100}. 
The principle is repeated until both objective costs are generated.

+ Generation of instances of class D:

    The instances of class D are obtained from the instances of class C by replacing the first objective by the second in reverse order.

These instances are denoted by 2KPn-1C.dat or 2KPn-1D.dat where $`n`$  is the size of the problem. 

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

ID : instance's name

[![instance file](./img/icon/dl-instance.png "instance file")](instances/) : instance's file 

[![INFO file](./img/icon/dl-info.png "INFO file")](analyze/) : report about the numerical characteristics

[![Y_N file](./img/icon/dl-z.png "Y_N file")](Y/) : set of non dominated points

[![X_E_M file](./img/icon/dl-x.png "X_E_M file")](X/) : Maximum complete set of efficient solutions


***

**Instances referenced 1B/C** in [1]

There are 10 instances:

| ID            | Available | 
| ------------- | --------- |
| 2KP50-1C.dat  | [![instance file](./img/icon/dl-instance.png "instance file")](instances/1B-C) |
| 2KP100-1C.dat | [![instance file](./img/icon/dl-instance.png "instance file")](instances/1B-C) |
| 2KP150-1C.dat | [![instance file](./img/icon/dl-instance.png "instance file")](instances/1B-C) |
| 2KP200-1C.dat | [![instance file](./img/icon/dl-instance.png "instance file")](instances/1B-C) |
| 2KP250-1C.dat | [![instance file](./img/icon/dl-instance.png "instance file")](instances/1B-C) |
| 2KP300-1C.dat | [![instance file](./img/icon/dl-instance.png "instance file")](instances/1B-C) |
| 2KP350-1C.dat | [![instance file](./img/icon/dl-instance.png "instance file")](instances/1B-C) |
| 2KP400-1C.dat | [![instance file](./img/icon/dl-instance.png "instance file")](instances/1B-C) |
| 2KP450-1C.dat | [![instance file](./img/icon/dl-instance.png "instance file")](instances/1B-C) |
| 2KP500-1C.dat | [![instance file](./img/icon/dl-instance.png "instance file")](instances/1B-C) |

***

**Instances referenced 1B/D** in [1]

There are 10 instances:

| ID            | Available | 
| ------------- | --------- |
| 2KP50-1D.dat  | [![instance file](./img/icon/dl-instance.png "instance file")](instances/1B-D) |
| 2KP100-1D.dat | [![instance file](./img/icon/dl-instance.png "instance file")](instances/1B-D) |
| 2KP150-1D.dat | [![instance file](./img/icon/dl-instance.png "instance file")](instances/1B-D) |
| 2KP200-1D.dat | [![instance file](./img/icon/dl-instance.png "instance file")](instances/1B-D) |
| 2KP250-1D.dat | [![instance file](./img/icon/dl-instance.png "instance file")](instances/1B-D) |
| 2KP300-1D.dat | [![instance file](./img/icon/dl-instance.png "instance file")](instances/1B-D) |
| 2KP350-1D.dat | [![instance file](./img/icon/dl-instance.png "instance file")](instances/1B-D) |
| 2KP400-1D.dat | [![instance file](./img/icon/dl-instance.png "instance file")](instances/1B-D) |
| 2KP450-1D.dat | [![instance file](./img/icon/dl-instance.png "instance file")](instances/1B-D) |
| 2KP500-1D.dat | [![instance file](./img/icon/dl-instance.png "instance file")](instances/1B-D) |


