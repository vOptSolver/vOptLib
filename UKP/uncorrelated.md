# Uncorrelated Instances 
These are classical instances. 
The costs c1(i), c2(i) and the weights w(i) are generated independently following a uniform distribution in a given set. 
There is no correlation neither between the objective costs, nor between any objective cost and the weight.

## Format
All these instances are given here according to a same format :

   * number of variables (n),
   * number of objectives (p = 2),
   * number of constraints (k = 1),
   * Cost of item i for objective 1 (i = 1,...,n),
   * Cost of item i for objective 2 (i = 1,...,n),
   * Weight of item i (i = 1,...,n),
   * Total weight of the knapsack W.

Lines of comments begin by #.

## Papers
The instances provided here have been used for the experiments of the following papers.

[1] Xavier Gandibleux, Arnaud Freville. Tabu Search Based Procedure for Solving the 0-1 MultiObjective Knapsack Problem: the two objective case. Journal of Heuristics, 6 (3) 361-383, 2000.

[2] M. Visée, J. Teghem, M. Pirlot and E. L. Ulungu. Two-phases Method and Branch and Bound Procedures to solve the Bi-objective Knapsack Problem. Journal of Global Optimization 12: 139–155 (1998).

[3] Fabien Degoutin and Xavier Gandibleux. Un retour d'expérience sur la résolution de problèmes combinatoires bi-objectifs. 5e journée du groupe de travail Programmation Mathématique MultiObjectif (PM20), Angers, France, 17 mai 2002.

[4] M. E. Captivo, J. Clímaco, J. Figueira, E. Martins and J. L. Santos. Solving bicriteria 0-1 knapsack problems using a labeling algorithm. Computers & Operations Research 30 (2003) 1865–1886.

With the exception of the instances provided in [1], all instances have a tightness ratio W / (Sum{i=1,...n} w(i)) = 0.5.

The instances from [1] are denoted by 2KPn-c.dat where n is the size of the problem, and 0.c is the tightness ratio. 
The objective costs and the weights are generated according to a uniform distribution respectively in {30,...100} and in {20,...500}. 
These instances are classified 1A in MOCOlib.

The instances from [2] are denoted by 2KPn-1A.dat where n is the size of the problem. 
The objective costs and the weights are generated according to a uniform distribution in [1,...,100]. 
These instances are classified 1B/A in MOCOlib.

The instances from [3] are denoted by 2KPn-1B.dat where n is the size of the problem. 
The first objective cost and the weights are generated according to a uniform distribution in [1,...,100]. 
The second objective is obtained by taking the objective cost of the first one in reverse order. 
These instances are classified 1B/B in MOCOlib.

The objective costs and the weights of the instances from [4] are both generated according to a uniform distribution in [1,...,300] or [1,...,1000]. 
All these instances have the same size n = 50. 
These instances are denoted by F5050Wx.dat (instances generated with numbers in [1,...,300]) or K5050Wx.dat (instances generated with numbers in [1,...,1000]), x denotes the number of the instance. 
These instances are classified 2/UNCOR in MOCOlib.

Additional Informations (provided when available) for these instances in MOCOlib: 
a report about the numerical characteristics, the set of non dominated points, the maximum complete set of solutions. 