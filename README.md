# Background knowledge
Quantum random walk is the classical analogue of classical random walk, which in some problems, provides exponential speedup over classical algorithms.
Its randomness arises from 
1. superposition of (coin) states
2. unitary evolution (non-random, illustrates by coin and shift operators)
3. wavefunction collapse (due to measurements)

## Elements of the quantum random walks
The quantum random walks have two essential elements: coin $\mathcal{C}$ and shift $\mathcal{S}$ operators.
That is, there are two Hilbert subspaces: coin and position, storing the information of the coin state (sometimes we call it the internal state of the walker) and the walker's position: $\mathcal{H} = \mathcal{H}_c \otimes \mathcal{H}_p$.
These two operators play an important role on the walks' behaviors, and determine the propagator 
$$
\mathcal{U} = \mathcal{S} \mathcal{C}
$$
of the each step of the process.

### Running on a quantum computer
We provide some [examples](https://github.com/ycldingo/QuantumRandomWalk/tree/main/IBMQ) for [IBM's qiskit platform](https://quantum-computing.ibm.com/).
These codes simulate the standard 1D quantum random walks.


## Non-stochastic quantum random walks
The process of can be non-stochastic with introducing the parameterized coin. 
$\mathcal{C}$ are characterized by some parameters and are vary with the step of the walk or the position of the quantum walker, for example.
The non-stochatic walks lead to diverse probability distributions to the walker's location.
***(The word "non-stochastic" here means we cam somehow have some controllability during the walks, but not saying the process non-stochastic)***


## Lackadaisical quantum random walks
Unlike the standard quantum random walk, the lackadaisical quantum random walk has more choices to the walker: 
 - moving forward
 - going backward
 - ***staying at its current position***
 
The weighting of the options can be adjust by tunning the number of (coin) components, i.e., the dimension of the coin subspace, with respect to the required choices.
To construct the part of stays, a self-loop parameterized by the ***laziness coefficient*** is introduced to the shift operator, which corresponds to the staying opetion.
Unlike its classical analogue, the probability distribution of lackadaisical quantum walk spreads faster than the standard quantum random walk, and will not be trapped around its initial start location.
This property may lead to advantages in quantum algorithm such as Grover's search.


# Introduction to our work
## Non-stochastic one-dimensional lackadaisical quantum random walk
Here we combine the above two cases: making the coins of the lackadaisical quantum random walk non-stochastic, that is, depend on some characteristics of the process. We call these coins ***path-dependent coins (DCs) $\mathcal{C}_{\text{DCs}}$***
(comparing to the commom choice: Grover diffusion operator $\mathcal{C}_{\text{G}}$).


## Path-dependent coins
In this work, we provide a model requiring a smaller Hilbert subspace for the coin register but spreads faster and more coherent than the standard lackadaisical quantum walks with Grover coin.
By adjusting the parameter in the coin operator, we can achieve to diverse probability distributions easily.


## Walks' patterns
We study several quantities that help us describe the pattern of the walks for DCs cases.
The results suggest different usage of DCs, which may be benefical to different technology applications such as creating coherent resources or speedup the quantum database searching algorithms.



## More detail
The work is accepted by [2021 Annual Meeting of the Physical Society of Taiwan](https://tps2021.conf.tw/site/page.aspx?pid=901&sid=1352&lang=en).
For further content, please visit:
- [abstract](https://github.com/ycldingo/QuantumRandomWalk/blob/main/abstract_Non-stochastic%20one-dimensional%20lackadaisical%20quantum%20random%20walks.pdf)
- [more about the work](https://github.com/ycldingo/QuantumRandomWalk/blob/main/TPS2021_v2.pdf)


### Contributions
- Yun-Chih Liao
  - Graduate Institute of Communication Engineering, National Taiwan University, Taipei, Taiwan 
- Hsi-Sheng Goan
  - Department of Physics and Center for Theoretical Physics, National Taiwan University, Taipei, Taiwan 
  - Center for Quantum Science and Engineering, National Taiwan University, Taipei, Taiwan 
- Hao-Chung Cheng
  - Department of Electrical Engineering, National Taiwan University, Taipei, Taiwan
  - Graduate Institute of Communication Engineering, National Taiwan University, Taipei, Taiwan 

