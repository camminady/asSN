# asSN
Smallish implementation of the as-SN solver.

## Implementation
The notebokook `asSN.ipynb` contains a `python` + `numba` implementation of the artificial scattering SN method using the second order finite volume method with slope limiter. The notebook can be used to reproduce the results that are presented in the corresponding paper ([journal publication](https://doi.org/10.1080/00295639.2020.1730665) / [preprint](https://arxiv.org/abs/1911.08801)). This implementation tries to find a balance between performance, readability, and compactness of the code.

## Run the code
You can either download this repository and run the code locally, or you can use Google Colab and simply click on the badge below.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/camminady/asSN/blob/main/asSN.ipynb)
