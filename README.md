# OptISTA_Verification
This repository verifies the convergence rate of [OptISTA](https://arxiv.org/abs/2305.15704)

## `OptISTA_PEPit_Code_verification.ipynb`

This python jupyter notebook verifies the convergence rate of OptISTA by [PEPit](https://pepit.readthedocs.io/en/latest/index.html) library. 
We find that the results of the PEPit code match Theorem 1. 

### Dependencies

Please install following python packages 

  ```python
pip install pepit numpy
  ```

## `Optista_SDP.ipynb`

This julia jupyter notebook verifies the convergence rate of OptISTA by substituting OptTISA stepsizes into the inner maximization problem  $(\mathcal{O}^{\text{inner}})$ in Section 3. The results of the code are consistent with Theorem 1.

### Dependencies

Please install following Julia packages 

  ```julia
add Mosek, JuMP, OffsetArrays, LinearAlgebra , MosekTools, Ipopt, Printf
  ```


