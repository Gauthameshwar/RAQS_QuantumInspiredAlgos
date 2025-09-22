# RAQS Quantum-Inspired Algorithms

## Randomised SVD and Data compression into Tensor Trains

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Gauthameshwar/RAQS_QuantumInspiredAlgos/blob/master/notebooks/RSVDnDataCompression.ipynb)

**Further reading (RSVD, TT/TT-SVD, and MPS)**

- **Randomized SVD (RSVD)** — Halko, Martinsson, Tropp (2011), *SIAM Review*.  
  [Journal page](https://epubs.siam.org/doi/10.1137/090771806) · [arXiv](https://arxiv.org/abs/0909.4061)

- **Monograph on randomized matrix algorithms** — Mahoney (2011), *Foundations & Trends in ML*.  
  [arXiv](https://arxiv.org/abs/1104.5557)

- **Survey: Randomized Numerical Linear Algebra** — Martinsson, Tropp (2020).  
  [PDF](https://users.math.msu.edu/users/iwenmark/teaching/cmse890/NLA_randomized-numerical-linear-algebra-foundations-and-algorithms.pdf)

- **Tensor-Train (TT) Decomposition / TT-SVD** — Oseledets (2011), *SIAM J. Sci. Comput.*  
  [Journal page](https://epubs.siam.org/doi/10.1137/090752286) · [PDF mirror](https://users.math.msu.edu/users/iwenmark/Teaching/CMSE890/TENSOR_oseledets2011.pdf) 

- **TT-Cross (interpolatory) algorithm** — Oseledets & Tyrtyshnikov (2010), *Linear Algebra Appl.*  
  [Journal page](https://www.sciencedirect.com/science/article/pii/S0024379509003747) · [PDF](https://www.sciencedirect.com/science/article/pii/S0024379509003747/pdf) 

- **Block-TT eigenvalue methods** — Dolgov, Khoromskij, Oseledets, Savostyanov (2013).  
  [arXiv](https://arxiv.org/abs/1306.2269)

- **MPS review (quantum-inspired algorithms)** — Schollwöck (2011), *Annals of Physics*.  
  [arXiv](https://arxiv.org/abs/1008.3477) · [Journal page](https://www.sciencedirect.com/science/article/abs/pii/S0003491610001752)

- **Origins of MPS (finitely-correlated states)** — Fannes, Nachtergaele, Werner (1992), *Comm. Math. Phys.*  
  [Free PDF](https://projecteuclid.org/journals/communications-in-mathematical-physics/volume-144/issue-3/Finitely-correlated-states-on-quantum-spin-chains/cmp/1104249404.pdf) 

- **General tensor decompositions survey (CP/Tucker/TT context)** — Kolda & Bader (2009), *SIAM Review*.  
  [PDF](https://www.kolda.net/publication/TensorReview.pdf)

- **Best rank-k approximation (Eckart–Young)** — Eckart & Young (1936).  
  [Springer page](https://link.springer.com/article/10.1007/BF02288367)



## Ground state search in Tensor Trains

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Gauthameshwar/RAQS_QuantumInspiredAlgos/blob/master/notebooks/GroundStateTensorTrains.ipynb)

**Further Reading & References (ITensors.jl, DMRG, Eigensolvers)**

- **DMRG (Density Matrix Renormalization Group)** — Original algorithm and reviews on variational ground-state search in 1D systems.  
  White, S.R. *Density matrix formulation for quantum renormalization groups*, Phys. Rev. Lett. 69, 2863 (1992). [DOI: 10.1103/PhysRevLett.69.2863](https://doi.org/10.1103/PhysRevLett.69.2863)

- **Iterative eigensolvers** — Krylov methods (Lanczos, Davidson) form the backbone of local optimization in DMRG sweeps.  
  Saad, Y. *Iterative Methods for Sparse Linear Systems* (book, SIAM 2003). [SIAM link](https://epubs.siam.org/doi/book/10.1137/1.9780898718003)

- **TensorNetworks.org** — Pedagogical tutorials and interactive demos for tensor networks, canonical forms, and algorithms like DMRG/TEBD.  
  [https://tensornetwork.org](https://tensornetwork.org)

- **ITensors.jl Documentation** — Official Julia ITensor library docs, including examples on MPS/MPO construction and DMRG usage.  
  [https://itensor.github.io/ITensors.jl/latest](https://itensor.github.io/ITensors.jl/latest)

- **General Tensor Network reviews** — Broad overviews of tensor-network methods in condensed matter and quantum information.  
  Orús, R. *A practical introduction to tensor networks: Matrix product states and projected entangled pair states*, Ann. Phys. 349, 117 (2014). [DOI: 10.1016/j.aop.2014.06.013](https://doi.org/10.1016/j.aop.2014.06.013)

- **Tutorial notebooks** — A collection of practical Jupyter/Julia tutorials on tensor networks and DMRG.  
  [https://github.com/ITensor/ITensors.jl/tree/main/examples](https://github.com/ITensor/ITensors.jl/tree/main/examples)
