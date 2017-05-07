# Multiobjective Set Packing Problems (SPP)

	
## Definition
The set Packing problem with two objectives is defined as follow:

    Max sum{j=1,…,n} c1(j) x(j)
    Max sum{j=1,…,n} c2(j) x(j)
    s/t sum{j=1,…,n} t(i,j) x(j) <= 1   for i=1,…,m
        x(j) = 0 or 1                   for j=1,…,n

## Description
There are currently 120 data files.

They correspond to 20 bi-objective set packing problems.

For each problem, 6 variants are given: class A, B, C, D, E and F.

+ A: the costs are uniformly generated
+ B: created from A by replacing the second vector of costs by the first one in reverse order
+ C: vector of costs generated with plateaus of values
+ D: created from C by replacing the second vector of costs by the first one in reverse order
+ E: one unicost objective and one randomly generated objective
+ F: one unicost objective and one randomly generated objective with plateaus of values

## Format
The format is originally from the OR library extended for handling multiple objectives.

The format of all of these data files is:

    number of rows (m), number of columns (n)
    the cost of each column for objective 1 c1(j),j=1,…,n
    the cost of each column for objective 2 c2(j),j=1,…,n
    for each row i (i=1,…,m): the number of columns which cover row i followed by a list of the columns which cover row i

## Files
Link to [data files](http://www.emse.fr/%7Edelorme/SetPacking.html#BOSPP).


## Misc
Files contain data from
> Xavier Gandibleux, Fabien Degoutin and Xavier Delorme
 A first feedback on set packing problems with two objectives
 Workshop "Multiple Objective Metaheuristics"
 November 04-05, 2002, Carré des Sciences, Paris, France.