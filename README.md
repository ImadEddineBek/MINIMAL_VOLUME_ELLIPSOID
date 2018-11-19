# Minimum Volume Ellipsoid
M.V.E is a convex problem that given a set of points tries to find the smallest(minimal) ellipsoid that covers all of these points.
# Getting Started
This is a very straight forward implementation using cvxpy and cvxpot in a anaconda envirenement.
## Prerequisites
1. Install anaconda
2. Install CvxPy `conda install -c conda-forge lapack`
 `conda install -c cvxgrp cvxpy`

for more details please visit the [CvxPy official Documentation](https://www.cvxpy.org/install/index.html)
This Code has two major parts:
1. M.V.E over all points

2. Minimum M.V.E over k points from N