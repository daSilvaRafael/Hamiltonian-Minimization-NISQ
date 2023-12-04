# Hamiltonian Minimization in the NISQ Era

This repository has the jupyter notebook with the results discussed on the author’s paper _Hamiltonian Minimization in the NISQ Era_. The paper outlines the use of noisy intermediate-scale quantum (NISQ) computers for Hamiltonian minimization problems. We delve into the mathematical formulation of Variational Quantum Eigensolver (VQE), Quantum Annealing (QA), and Quantum Approximation Optimization Algorithm (QAOA), with computational results for a 3-qubit minimization problem and its extension to 6-qubit, 13-qubit and 140-qubit problem run on central processor unit (CPU), quantum simulator (QS) and quantum processor unit (QPU). We show how different initial parameters leads to optimal, less accurate, or no satisfactory solutions using the considered versions of VQE and QAOA, a well known challenge. For all problems, the optimal solution was found using QA and hybrid solvers. This work serves as a hands-on approach to understand quantum annealing, variational quantum
algorithms, quantum hardware limitations and current landscape.


## Accounts

The reader needs to create an account on the following clouds:

 [Dwave Leap](https://cloud.dwavesys.com/leap/login/?next=/leap/)

 [IBM Quantum](https://quantum.ibm.com/)

 [Quafu](https://quafu.baqis.ac.cn/#/home)

and save the api token on the corresponding notebook in order to run them. For Dwave's API token set up see [_Set Up Your Environment_](https://docs.ocean.dwavesys.com/en/latest/overview/install.html).


## Installation

Install requirements locally (ideally, in a virtual environment):

    pip install -r requirements.txt


## References

R. Pereira da Silva (2023), _Hamiltonian Minimization in the NISQ Era_, SSRN Electronic Journal

## License

Released under the Apache License 2.0. See LICENSE file.
