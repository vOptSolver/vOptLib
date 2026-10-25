# Multiobjective Uncapacitated Facility Location Problems (UFLP)


## Definition (0/1 case)
The 0/1 uncapacitated facility location problem with two objectives is defined as follow:

    Min sum{i=1,...,nI;j=1,…,nJ} c1(i,j) x(i,j) + sum{j=1,…,nJ} r1(j) s(j)
    Min sum{i=1,...,nI;j=1,…,nJ} c2(i,j) x(i,j) + sum{j=1,…,nJ} r2(j) s(j)
    s/t sum{j=1,…,nJ} x(i,j) = 1     for i=1,…,nI
        x(i,j) <= s(j)               for i=1,…,nI; j=1,…,nJ
        x(i,j) = 0 or 1              for i=1,…,nI; j=1,…,nJ
        s(j) = 0 or 1                for j=1,…,nJ  

## Definition (Mixed case)
The mixed integer uncapacitated facility location problem with two objectives is defined as follow:

    Min sum{i=1,...,nI;j=1,…,nJ} c1(i,j) x(i,j) + sum{j=1,…,nJ} r1(j) s(j)
    Min sum{i=1,...,nI;j=1,…,nJ} c2(i,j) x(i,j) + sum{j=1,…,nJ} r2(j) s(j)
    s/t sum{j=1,…,nJ} x(i,j) = 1     for i=1,…,nI
        x(i,j) <= s(j)               for i=1,…,nI; j=1,…,nJ
        x(i,j) >= 0                  for i=1,…,nI; j=1,…,nJ
        s(j) = 0 or 1                for j=1,…,nJ                


## Datasets

+ **0/1 case with 2 objectives:**

    - [dataDidactic](data2012.md)  
    - [dataFernandez](data2012.md)  
    - [dataHarris](data2012.md)  

+ **Mixed case with 2 objectives:**

    - [Gadegaard](data2012.md) 
    - [Delmaire](data2012.md)  
    - [FernandezEasy](data2012.md) 
    - [FernandezHard](data2012.md)   
    - [Real](data2012.md)    
