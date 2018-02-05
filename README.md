Genetic Algorithm

Genetic Algorithms (GAs) are adaptive heuristic search algorithm based on the evolutionary ideas of natural selection and genetics. As such they represent an intelligent exploitation of a random search used to solve optimization problems. Although randomised, GAs are by no means random, instead they exploit historical information to direct the search into the region of better performance within the search space.

GAs are based on an analogy with the genetic structure and behaviour of chromosomes within a population of individuals using the following foundations:

    •	Individuals in a population compete for resources and mates.
    •	Those Individuals most successful in each 'competition' will produce more offspring than those Individuals that perform poorly.
    •	Genes from 'good' Individuals propagate throughout the population so that two good parents will sometimes produce offspring that are better than either parent.
    •	Thus, each successive Generation will become more suited to their environment.
    
In this particular program, each Organism is randomly generated with a gene sequence. A Generation of the above-mentioned Organisms is created and compared with an Organism considered to be ideal for the specific runtime.

New Generations are generated by selecting Organisms from previous Generation which have a higher fitness number and crossing them to make a child Organism which is part of the generated Generation.

Random mutations are added to the program. With some low probability, a portion of the new Organisms will have random genes input in their sequence. Its purposes to maintain diversity within the population and inhibit premature convergence.

The Algorithm:

    1.Randomly generate a population(x)
    2.Determine fitness of the population(x)
    3.Repeat until organism with highest fitness number is achieved
        a.	Select parents from the population(x)
        b.	Perform crossover and mutation on parents and create population(x+1)
        c.	Determine fitness of population(x+1)
        
The ability of the algorithm to explore and exploit simultaneously, a growing amount of theoretical justification, and successful application to real-world problems strengthens the conclusion that GAs are a powerful, robust optimisation technique.
    
