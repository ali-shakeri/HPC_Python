# High Performance Computing in Python

## Part I: Introduction
  - Why Python is slower than C/C++?
  - Why should we use Python?
  - CPU-bounded vs memory-bounded problems
  - Profiling a Python code
  - Profiling memory usage
  - Some problems for benchmarking (Diffusion Eq., Numerical integration, ...)
 
## Exercise session 
  - profile your code
  
## Part II: Data structures in Python
  - lists, tuples, dictionaries, sets, ...
  - Iterators vs Generators
  - Matrix-vector operations
  - Efficient memory allocation
  - numpy and scipy

## Exercise session 
  - Diffusion Eq.: python implementation vs numpy

## Part III: Even faster? Compiling Python
  - Cython
  - Numba
  - PyPy

## Excercise session
  - How statically type informations helps to improve performance?
  
## Part IV: Parallel computing
  - Python threading, GIL
  - Parallelizing with OpenMP
  - mpi4py
  - Running parallel Python programs with SLURM

## Excercise session
  - Parallelize Diffusion Eq.
  - Submit your job with SLURM
