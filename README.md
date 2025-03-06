# Readme
This repository is meant as supplementary Material for the Workshop on Tensor Network techniques for computational fluid dynamics on the 5th and 6th of march 2025 at the TU Munich.

## Repository Content

#### Notebooks
* [MPS_operations](notebooks/MPS_operations.ipynb) offers some implementations of basic operations on MPS.
* [2D_compression](notebooks/2D_compression.ipynb) gives an example of the compression capabilities that MPS offer, if the underlying data is suitably structured.
* [transport_eqs](notebooks/transport_eqs.ipynb) provides a simple numerical solution to the transport equations using MPS.

#### Other
* [utils](notebooks/utils/) contains utility functions.
* [examples](notebooks/utils/) contains intermediate results of a simulation of the temporally decaying jets. This data is used in the 2D compression demonstration.

## Useful Resources and Literature
* low level entry to tensor networks: [tensornetwork.org](https://tensornetwork.org)
* extensive review of MPS methods including DMRG: [The density-matrix renormalization group in the age of matrix product states](https://arxiv.org/abs/1008.3477), Schollwöck
* DMRG-based algorithm for INSE: [A quantum-inspired approach to exploit turbulence structures](https://www.nature.com/articles/s43588-021-00181-1), Gourianov et al.
* the above is also available as Gourianov's PHD thesis: [Exploiting the structure of turbulence with tensor networks](https://ora.ox.ac.uk/objects/uuid:9e3f4786-ad68-4913-9a0d-e9b1e108128f), Gourianov
* GPU-accelarated version of the algorithm: [Quantum-Inspired Fluid Simulation of 2D Turbulence with GPU Acceleration](https://arxiv.org/abs/2406.17823), Hoelscher et al.
* different algorithm with lid driven cavity: [Tensor network reduced order models for wall-bounded flows](https://arxiv.org/abs/2303.03010), Kiffner et al.
* different algorithm, again, flow around a sphere: [Quantum-inspired framework for computational fluid dynamics](https://www.nature.com/articles/s42005-024-01623-8), Peddinti et al.
