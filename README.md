VOPTlib: Library of numerical instances for MultiObjective Linear Optimization problems
==
	
About 
-- 
VOPTlib (short for vector optimization library) is a collection problem instances for benchmarking multi-objective solvers.
It covers a variety of Multiobjective linear optimization problems (multiobjective combinatorial, multiobjective integer linear, multiobjective mixed integer programs).

History
--
Created in 1998 and available online since, the library -originaly named MOCOlib- was dedicated to MultiObjective Combinatorial Optimization (MOCO) problems. 
It is referenced from the International Society on Multiple Criteria Decision Making at `http://www.mcdmsociety.org/`, section Digital Library.
The repository is maintained by Xavier Gandibleux.


News
--

05-May-2017: New repository launched.
 

Problem Classes
--
VOPTlib is organized in structured and non-structured problems.
It distinguishes the following problem classes:

+ Multi-objective structured problems

    Several linear objectives; feasible region is a polyhedron with a structure; all variables are restricted to be binary.

    - Linear assignment problem (LAP): 

    - 0/1 unidimensional knapsack problem (01UKP):     

    - 0/1 bidimensional knapsack problem (01BKP):  
    
    - Set covering problem (SCP):      
    
    - Uncapacited discrete facility location problem (UDFLP): 
    
    - Single source capacited facility location problem (SSCFLP):
    
    Several linear objectives; feasible region is a polyhedron with a structure; some but not all of the variables are restricted to be integer.        

    - Uncapacited mixed facility location problem (UMFLP): 
    
    - Capacited facility location problem (CFLP):     


+ Multi-objective non-structured problems

    Several linear objectives; feasible region is a polyhedron; all variables are restricted to be integer.
    
    - Integer program (MOIP): 
    

    Several linear objectives; feasible region is a polyhedron; some but not all of the variables are restricted to be integer.

    - Mixed integer program (MOMIP): 
    

Download
--
The following instances can be downloaded and used for free. 
If you use them for your research, we would appreciate a reference to VOPTlib in your publication. 