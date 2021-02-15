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
Here we combine the above two cases: making the coins of the lackadaisical quantum random walk non-stochastic, that is, depend on some characteristics of the process. We call these coins ***path-dependent coins (DCs)*** $\mathcal{C}_{\text{DCs}}$ (comparing to the commom choice: Grover diffusion operator $\mathcal{C}_{\text{G}}$).


### Path-dependent coins
In this work, we provide a model requiring a smaller Hilbert subspace for the coin register but spreads faster and more coherent than the standard lackadaisical quantum walks with Grover coin.
By adjusting the parameter in the coin operator, we can achieve to diverge probability distributions easily.


### Walks' patterns
We study several quantities that help us describe the pattern of the walks for DCs cases.
The results suggest different usage of DCs, which may be benefical to different technology applications.


### Detail of our work
The work is accepted by [2021 Annual Meeting of the Physical Society of Taiwan](https://tps2021.conf.tw/site/page.aspx?pid=901&sid=1352&lang=en).
For further content, please see:
- [abstract](https://github.com/ycldingo/QuantumRandomWalk/blob/main/abstract_Non-stochastic%20one-dimensional%20lackadaisical%20quantum%20random%20walks.pdf)
- [detail](https://github.com/ycldingo/QuantumRandomWalk/blob/main/TPS2021_v2.pdf)

