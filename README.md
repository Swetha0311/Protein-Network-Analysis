**Author**: Swetha Yadavalli

**Programming Language**: Python

**Dependencies**:
- networkx
- matplotlib.pyplot
- scipy.stats - ranksums

**Files required**:
- Human-PPI.txt
- protein-list1.txt
- protein-list2.txt

## Description

This Python script performs a comprehensive analysis of a protein-protein interaction (PPI) network. It calculates basic network properties, such as degree and clustering coefficients, and performs a comparison of path lengths between two sets of proteins.

## Execution Steps

1. Load the necessary modules in the python environment 
2. Load a protein-protein interaction network from an edge list.
3. Calculate and print the degree and clustering coefficient for each protein in the network.
3. Compute and display the average clustering coefficient of the entire network.
4. Plot the degree distribution on a log-log scale to help identify scale-free properties.
5. Define functions to calculate shortest path lengths within subgraphs defined by two different sets of proteins and compare these distributions using the Wilcoxon rank-sum test.
6. Load the datasets of the proteins required. 
7. Calculate the path lengths 
8. Print the results of the Wilcoxon Rank-Sum Test Statistic and P-value. 

## Output Files

The final .pynb can be accessed for the coefficient and the path lengths along with the plot of the degree distribution. 
