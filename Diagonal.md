-----

## Diagonal of a vector

**diag(v,k)**

- v vector of length n, k is integer
- returns a square matrix of order n + |k| with elements of v
	- on the diagonal (if k =0)
	- above the diagonal (if k>0)
	- below the diagonal (if k<0)
- diag(v) = diag(v,0)

diag(1)
ans =

     1




## Diagonal of a matrix


**diag(A,k)**

- where A is a matrix, and k is integer
- returns a column vector with elements from
	- the main diagonal (if k = 0)
	- above the diagonal (if k >0)
	- below the diagonal (k<0)
- diag(A) = diag(A,0)

A =

     1     2     3     4
     5     6     7     8
     9     0     1     2
     3     4     5     6


diag(A)

ans =

     1
     6
     1
     6
