# Multiobjective Uncapacitated Facility Location Problems (UFLP)


## Definition (0/1 case)
The 0/1 uncapacitated facility location problem with p objectives is defined as follow:

    Min  z^k(x,s) = sum{i=1,...,nI; j=1,…,nJ} c^k(i,j) x(i,j) + sum{j=1,…,nJ} r^k(j) s(j)    for k=1,…,p
    s/t sum{j=1,…,nJ} x(i,j) = 1     for i=1,…,nI
        x(i,j) <= s(j)               for i=1,…,nI; j=1,…,nJ
        x(i,j) = 0 or 1              for i=1,…,nI; j=1,…,nJ
        s(j) = 0 or 1                for j=1,…,nJ  

## Definition (Mixed integer case)
The mixed integer uncapacitated facility location problem with p objectives is defined as follow:

    Min  z^k(x,s) = sum{i=1,...,nI; j=1,…,nJ} c^k(i,j) x(i,j) + sum{j=1,…,nJ} r^k(j) s(j)    for k=1,…,p
    s/t sum{j=1,…,nJ} x(i,j) = 1     for i=1,…,nI
        x(i,j) <= s(j)               for i=1,…,nI; j=1,…,nJ
        x(i,j) >= 0                  for i=1,…,nI; j=1,…,nJ
        s(j) = 0 or 1                for j=1,…,nJ                


## Datasets

+ **0/1 case with p=2 objectives:**

    - [dataDidactic](data2012.md)  
    - [dataFernandez](data2012.md)  
    - [dataHarris](data2012.md)
    - [dataBeasley](data2012.md)

+ **Mixed integer case with p=2 objectives:**

    - [Gadegaard](data2012.md) 
    - [Delmaire](data2012.md)  
    - [FernandezEasy](data2012.md) 
    - [FernandezHard](data2012.md)   
    - [Real](data2012.md)    
