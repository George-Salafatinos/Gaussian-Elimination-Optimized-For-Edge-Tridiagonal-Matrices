# A Gaussian Elimination Algorithm Implementation For Edge-Tridiagonal matrices

An Edge-Tridiagonal matrix is a type of sparse matrix that is a tridiagonal matrix except values in the farthest right column are permitted to be nonzero. I assume the given matrix does not need pivoting. I construct an efficient data structure for storing this type of sparse matrix. Then I design and implement a variation on Gaussian Elimination that is optimized for solving systems of equations with matrix representations of this form.
