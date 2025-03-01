Download link :https://programming.engineering/product/cpts-591-network-science-assignment-1-solved/

# CptS-591-Network-Science-Assignment-1-Solved
CptS 591 Network Science Assignment 1 Solved
In this assignment you will do basic network analysis on a set of real-world networks and synthetically generated random networks. For the analysis, you will use the software package igraph.

Datasets: the assignment involves three networks from Mark Newman’s collection of Network Data (http://www-personal.umich.edu/~mejn/netdata/). The networks in the collection are given certain descriptive names. The three networks chosen for this assign-ment are called: (1) Political blogs, (2) Neural network, and (3) Internet. Read the brief descriptions there so you get an idea for what the networks are modeling.

Your task: Download the three networks. These data sets are in GML format, which is a format the package igraph understands. \Read” the three networks into igraph. In addition to these three networks, generate three Erdos-Renyi random networks G(n; p) using igraph, the rst with the parameters n = 2000 and p = 0:01, the second with the parameters n = 2000 and p = 0:005, and the third with the parameters n = 2000 and p = 0:0025. Perform and report on the following tasks for all six networks.

Your submission will be one PDF le consisting of your solutions and an appendix describing the procedure you followed (simple listing of your igraph-python/R code).

(40%) Obtain/calculate the information/quantities for each of the six networks needed to complete the following table:

Network Type n m c d l L ccl ccg

where: Type indicates whether the network is directed or undirected; n is the number of nodes; m is the number of links; c is the number of connected components (in the case of a directed network, separately report on the number of strong and weak connected components); d is the maximum degree; l is the average path length; L is the diameter; ccl is the average local clustering coe cient; and ccg is the global clustering coe cient (3 times number of triangles/ number of connected triplets). Note that igraph calculates global clustering coe cient using its transitivity undirected function and the average local clustering coe cient using its transitivity avglocal undirected function.

(25%) Plot the degree distribution of each network. This is a pk vs k plot, where pk

corresponds to the probability that a randomly chosen node has degree k (in other words, pk shows the fraction of nodes having degree k). What observations can you make from the plots?

(25%) Plot the pathlength distribution of each network. This is a pl vs l plot, where pl

corresponds to the probability that two randomly chosen nodes have a shortest path of length l between them (in other words, pl shows the fraction of node-pairs connected by a shortest path of length l.) Hint: see igraph’s function called path length hist. What observations can you make from the plots?


(10%)) Do the analysis described in (1){(3) on your favorite real-world network (of course outside the three described in the dataset for this assignment). This could be a network that your research is related to, or just a network that you are interested in learning something about. Remember to include a brief description of the network you worked with { at a minimum the description should state what the nodes and links are.
