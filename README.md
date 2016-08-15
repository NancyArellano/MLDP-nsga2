# MLDP-nsga2
This metaheuristic is based on the NSGA-II procedure reported in 2000 by Deb et al. Our particular implementation generates the initial population by the division of the population into a percentage of random solutions and a percentage generated with the nearest neighboor guided by the objectives of distance and latency.
Our implementation takes as mutation a simple 2-opt movement and each solution has a .15 ratio of mutation.
All this is implemented in c++ and the set of instances used to test it are described in Angel-Bello et al, 2013.
