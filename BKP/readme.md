# Multiobjective 01 bidimensional knapsack problem (BKP)
	
## Definition

The 01 bidimensional knapsack problem with two linear objectives is defined as follow:

    Max sum{j=1,…,n} c1_j x_j      
    Max sum{j=1,…,n} c2_j x_j        
    s/t sum{j=1,…,n} w1_j x_j <= W1
        sum{j=1,…,n} w2_j x_j <= W2    
        x_j = 0 or 1                for j = 1,…,n