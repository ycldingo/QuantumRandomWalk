# Quantum Random Walk

## Warm-Up
### Non-stochastic quantum random walks
The process of can be non-stochastic with introducing the parameterized coin such as the rotation matrices. 
The coins are characterized by the rotation angles and are vary with the step of the walk or the position of the quantum walker, for example.
The non-stochatic walks lead to diverse probability distributions to the walker's location.


### Lackadaisical quantum random walks
Unlike the standard quantum random walk, the lackadaisical quantum random walk has more choices to the walker: to stay at its current position.
The weighting of the options can be adjust by tunning the number of (coin) components with respect to the required choices.
To construct the part of stays, a self-loop parameterized by the ***laziness coefficient*** is introduced to the shift operator, which corresponds to the staying.
Unlike its classical analogue, the probability distribution of lackadaisical quantum walk spreads faster than the standard quantum random walk, and will not be trapped around its initial start location.
This property may lead to advantages in quantum algorithm such as Grover's search.


## Introduction
### Non-stochastic one-dimensional lackadaisical quantum random walk
Here we combine the above two cases: making the coins of the lackadaisical quantum random walk non-stochastic, that is, depend on some characteristics of the process. We call these coins ***path-dependent coins (DCs)*** (comparing to the commom choice: Grover diffusion operator ($\mathcal{C}_{\text{G}}$)).


