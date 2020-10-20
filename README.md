# asSN
Smallish implementation of the as-SN solver.

## Implementation
The notebokook `asSN.ipynb` contains a `python` + `numba` implementation of the artificial scattering SN method using the second order finite volume method with slope limiter. The notebook can be used to reproduce the results that are presented in the corresponding paper ([journal publication](https://doi.org/10.1080/00295639.2020.1730665) / [preprint](https://arxiv.org/abs/1911.08801)). This implementation tries to find a balance between performance, readability, and compactness of the code.
