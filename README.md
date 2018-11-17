# 1. Subroutine problem
Given N points on the plane. Find minimal volume ellipsoid containing these points. This is
the convex problem:
$$ min log det A^{-1}$$

$$||Ax^i +b||^2_2 <= 1, i=1,...,N$$

The volume of the ellipsoid is proportional to $det A^{-1}$

# 2. Major task
Given $\mathcal{N}$ points in $\mathcal{R^n}$, Select k of them such that the volume of ellipsoid covering these particular
selected $\mathcal{k}$ points is minimal (compare to other ellipsoids covering different subsets of $\mathcal{k}$ points of $\mathcal{N}$).
