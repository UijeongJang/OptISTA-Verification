# OptISTA_Verification
This repository verifies the convergence rate of [OptISTA](https://arxiv.org/abs/2305.15704)

## `OptISTA_PEPit_Code_verification.ipynb`

This python jupyter notebook verifies the convergence rate of OptISTA by using [PEPit](https://pepit.readthedocs.io/en/latest/index.html) library. 
The result is consistent with Theorem 1.

### Dependencies

Please install following python packages 

  ```python
pip install pepit numpy
  ```

## `Optista_SDP.ipynb`

This julia jupyter notebook verifies the convergence rate of OptISTA by substituting OptTISA stepsizes into the inner maximization problem  $(\mathcal{O}^{\text{inner}})$ in Section 3. The result is consistent with Theorem 1.

### Dependencies

Please install following Julia packages 

  ```julia
add Mosek, JuMP, OffsetArrays, LinearAlgebra , MosekTools, Ipopt, Printf
  ```


