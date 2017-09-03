# vOptLib: Library of numerical instances for MultiObjective Linear Optimization problems
	
## About 
vOptLib (short for vector optimization library) is a collection problem instances for benchmarking multi-objective solvers.
It covers a variety of Multiobjective linear optimization problems (multiobjective combinatorial problems, multiobjective integer linear programs, multiobjective mixed integer programs).
Available online since 1998, and redesigned in 2017, the repository is currently maintained by Xavier.Gandibleux@univ-nantes.fr and Anthony.Przybylski@univ-nantes.fr

## News
	02-Sep-2017: moved from gitlab to here (repository on gitlab will be closed soon)
	05-May-2017: New repository launched.
 

## Problem Classes
vOptLib is organized in structured and non-structured problems.
It distinguishes the following problem classes:

+ **Multi-objective structured problems**

    Several linear objectives; feasible region is a polyhedron with a structure; all variables are restricted to be binary.

    - [Linear assignment problem (LAP)](LAP/readme.md) 

    - [0/1 unidimensional knapsack problem (UKP)](UKP/readme.md)     

    - [0/1 bidimensional knapsack problem (BKP)](BKP/readme.md)  
    
    - [Set covering problem (SCP)](SCP/readme.md)    
    
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
If you use them for your research, we would appreciate a reference to vOptLib in your publication. 


## History
Created in 1998 and available online since, the library -originaly named MCDMlib and later the MOCOlib- was dedicated to MultiObjective Combinatorial Optimization problems. 
It is referenced from: 
+ the [International Society on Multiple Criteria Decision Making](http://www.mcdmsociety.org/), section *Digital Library*
+ the [OR-Library](http://people.brunel.ac.uk/~mastjjb/jeb/info.html), item *Multiobjective optimisation*

Amongst the instances available, the library hosts instances used by us during the following research projects:
+ ANR project [GUEPARD: Guaranteed efficiency for pareto optimal solutions determination in multiobjective combinatorial optimization problems](http://guepard.lip6.fr/)
+ ANR-DFG project [vOpt: Exact efficient solution of mixed integer programming problems with multiple objective functions](https://vopt-anr-dfg.univ-nantes.fr/)

The obsolete (but active) URLs are:
+ [MCDMlib (since 1998)](http://web.archive.org/web/20061205225020/http://www.univ-valenciennes.fr:80/ROAD/MCDM/)
+ [MOCOlib, the MOCO section of the MCDMlib (since 2007)](http://xgandibleux.free.fr/MOCOlib/index.html)

## Others collections
- [Zitzler-Laumanns's instances (since 2001)](http://www.tik.ee.ethz.ch/sop/download/supplementary/testProblemSuite/)
- [Joshua Knowles's instances (since 2002)](http://www.cs.bham.ac.uk/~jdk/mQAP/)
- [Luís Paquete's instances (since 2004)](https://apps.uc.pt/mypage/faculty/uc26679/en/software#BD)
- [GUEPARDlib (since 2010)](http://guepard.lip6.fr/Main/GuepardLib)
- [Gokhan Kirlik's instances (since 2014)](http://home.ku.edu.tr/~moolibrary/)
- [MOPLIB (since 2015)](http://moplib.zib.de/)
- [MOREPO (since 2017)](https://github.com/MCDMSociety/MOrepo)
