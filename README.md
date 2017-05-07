# VOPTlib: Library of numerical instances for MultiObjective Linear Optimization problems
	
## About 
VOPTlib (short for vector optimization library) is a collection problem instances for benchmarking multi-objective solvers.
It covers a variety of Multiobjective linear optimization problems (multiobjective combinatorial problems, multiobjective integer linear programs, multiobjective mixed integer programs).
The repository is maintained by Xavier.Gandibleux@univ-nantes.fr

## History
Created in 1998 and available online since, the library -originaly named MOCOlib- was dedicated to MultiObjective Combinatorial Optimization problems. 
It is referenced from the [International Society on Multiple Criteria Decision Making](http://www.mcdmsociety.org/), section Digital Library.
Amongst the instances available, the library hosts instances used by us during the following research projects:
+ ANR project 'Guaranteed efficiency for pareto optimal solutions determination in multiobjective combinatorial optimization problems'
+ ANR-DFG project 'Exact efficient solution of mixed integer programming problems with multiple objective functions'

## News
05-May-2017: New repository launched.
 

## Problem Classes
VOPTlib is organized in structured and non-structured problems.
It distinguishes the following problem classes:

+ **Multi-objective structured problems**

    Several linear objectives; feasible region is a polyhedron with a structure; all variables are restricted to be binary.

    - Linear assignment problem (LAP) 

    - 0/1 unidimensional knapsack problem (UKP)     

    - 0/1 bidimensional knapsack problem (BKP)  
    
    - Set covering problem (SCP)    
    
    - [Set packing problem (SPP)](SPP/readme.md)    
    
    - Uncapacited binary facility location problem (UBFLP) 
    
    - Single source capacited facility location problem (SSCFLP)
    
    Several linear objectives; feasible region is a polyhedron with a structure; some but not all of the variables are restricted to be integer.        

    - Uncapacited mixed facility location problem (UMFLP) 
    
    - Capacited facility location problem (CFLP)  


+ **Multi-objective non-structured problems**

    Several linear objectives; feasible region is a polyhedron; all variables are restricted to be integer.
    
    - Integer program (MOIP) 
    
    Several linear objectives; feasible region is a polyhedron; some but not all of the variables are restricted to be integer.

    - Mixed integer program (MOMIP)
    

## Download
The following instances can be downloaded and used for free. 
If you use them for your research, we would appreciate a reference to VOPTlib in your publication. 
