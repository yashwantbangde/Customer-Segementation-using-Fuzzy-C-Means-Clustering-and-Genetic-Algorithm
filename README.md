# Customer-Segementation-using-Fuzzy-C-Means-Clustering-and-Genetic-Algorithm

In this implementation, both the fuzziness parameter and the number of clusters are jointly optimized using the Genetic Algorithm (GA). 
The GA parameters, such as population size, number of generations, crossover and mutation probabilities, as well as the minimum and maximum values for the number of clusters and fuzziness, are defined.

The GA parameters, such as population size, number of generations, crossover and mutation probabilities, as well as the minimum and maximum values for the number of clusters and fuzziness, are defined.

The fitness evaluation function (evaluate) performs FCM clustering with the given number of clusters and fuzziness parameter. 
The GA toolbox is configured to generate individuals (chromosomes) consisting of both the number of clusters and the fuzziness parameter. The individuals are initialized with random values within the defined ranges.

The GA optimization process searches for the best combination of the number of clusters and the fuzziness parameter that minimizes the fitness function (in this case, the intra-cluster distance).

After the GA optimization, the best individual is extracted, and FCM clustering is performed using the optimized parameters. Finally, customers are assigned to clusters based on the maximum membership value, and the cluster assignments are printed.
