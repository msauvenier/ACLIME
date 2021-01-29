# ACLIME

## Introduction
This code is an implementation on R of the ACLIME-ADMM estimator.

The ACLIME estimator has been introduced in [[1](https://projecteuclid.org/euclid.aos/1458245724)] to estimate sparse precision matrix (inverse of covariance matrix).

The ADMM program implemented in the cade has been derived in [[2](https://arxiv.org/abs/1709.03891)].

## How-to-use

The code is simple an R function taking into input the matrix containing the observations of the variables whoses precision matrix needs to be computed and gives as output the estimated precision matrix. The parameters rho and delta are needed for the ADMM program, see [2] for details.

### References
[[1](https://projecteuclid.org/euclid.aos/1458245724)] Cai, T. Tony; Liu, Weidong; Zhou, Harrison H. Estimating sparse precision matrix: Optimal rates of convergence and adaptive estimation. Ann. Statist. 44 (2016), no. 2, 455--488. doi:10.1214/13-AOS1171. 

[[2](https://arxiv.org/abs/1709.03891)] J. Golmohammadi, I. Ebert-Uphoff, S. He, Y. Deng and A. Banerjee, "High-Dimensional Dependency Structure Learning for Physical Processes," 2017 IEEE International Conference on Data Mining (ICDM), New Orleans, LA, 2017, pp. 883-888, doi: 10.1109/ICDM.2017.109.
