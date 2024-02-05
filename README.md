# Coliny (A Library of COLIN Optimizers)

Coliny provides a collection of optimizers that have been extended to have a COLIN optimization interface. In particular, Coliny includes derivative-free local search and global optimization heuristics.  This software will be used as a subroutine library that is integrated into other application codes.

Coliny is a C++ library that includes implementations of a variety of optimization algorithms. Coliny relies on the COLIN optimization library interface to define the basic framework for defining optimization problems.  Thus Coliny can be viewed as a collection of optimizers, any of which could be used independently.

The optimizers currently supported within Coliny are evolutionary algorithms (genetic algorithms, evolutionary programming, genetic programming and evolutionary pattern search), direct search (Solis-Wets search, simple pattern search), TABU search, multi-start local search, random sampling, DIRECT and GRASP.  Additionally, SGOPT includes interfaces with a variety of third-party optimizers, including APPS (direct search), DOT (nonlinear programming), COBYLA2 (direct search), TCC (global optimization), and GM (global optimization). Many of the optimizers in Coliny are written to exploit implicit parallelism in the execution of function evaluations, and a simple asynchronous master-slave algorithm can be used to use these algorithms in parallel on a wide-range of computing platforms.

SCR# 674

Hart,William Eugene
