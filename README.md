# K Shortest Hyperpaths in Hypergraphs

The implementation for finding the K shortest path in hypergraphs is done by implementing an algorithm called "SBT"[1] to find a single shortest hyperpath, and an algorithm called "Yen"[2]. The two algorithms is implemented in two different ways; one that minimizes the number of objects by storing the information of the hypergraph in arrays, and one that uses objects by storing the information in the objects. The two implementations can be found within one of the folders in this repository.
It should be noted that we are working on B-Hypergraphs, meaning that each hyperedge only has exactly one head as vertex, thus chose to modify the "SBT" algorithm and the overall structure for our code so that it only works for B-hypergraphs[1, page 179].

This project was made in collaboration with two other students. 

[1]: Gallo, G., Longo, G., Pallottino, S., and Nguyen, S. (1993). Directed hypergraphs and applications. 42:178,180,192.

[2]: Nielsen, L. R., Andersen, K. A., and Pretolani, D. (2005). Finding the k shortest hyperpaths. pages 1483–1465.
