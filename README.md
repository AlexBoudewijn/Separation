# Separation
Code and supplementary algorithms: material separation problem

The .ipynb file contains all algorithms and experiments reported on in the paper as one Jupyter notebook-file. 

An interactive Google Collab version is also available at https://colab.research.google.com/drive/1DLkdkBAKX9fcCE7Fpwz13RFX4YWTOsW2?usp=sharing (last edited 31/01/2021).

Some additional material is included, namely two heuristics with theoretical considerations and a solution method based on vectorization. The latter requires storage space 
for a large matrix. This matrix is instance-independent and reduces the problem to finding the minimal value in a vector obtained with only matrix-multiplication.

Construction of the matrix is very time-consuming, but it has to be constructed only once, after which it can be stored. While theoretically, the vectorized method has an
exponential running time, it is often very fast in practice.

Feel free to contact me at alexander.boudewijn (at) kuleuve.be for more details.
