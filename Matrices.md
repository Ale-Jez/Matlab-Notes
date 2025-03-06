-----


## Matrix definition
A = [ 1 2 3 4; 5 6 7 8; 9 0 1 2; 3 4 5 6; 7 8 9 0]

A =

     1     2     3     4
     5     6     7     8
     9     0     1     2
     3     4     5     6
     7     8     9     0


## Row or column
Remember that Matlab indexes from **one**, not from zero!

A(3,:)
ans =

     9     0     1     2

A(:,2)
ans =

     2
     6
     0
     4
     8



## Special kinds of matrices
-----

### Zeroes

C = zeros(2)

C =

     0     0
     0     0


### Ones

D = ones (2,3)

D =
     1     1     1
     1     1     1

D = ones (2,3,**4**)
the last parameter prints k time the matrix D (in this case 4 times)

D(:,:,1) =

     1     1     1
     1     1     1


D(:,:,2) =

     1     1     1
     1     1     1


D(:,:,3) =

     1     1     1
     1     1     1


D(:,:,4) =

     1     1     1
     1     1     1


## Identity

E = eye (4)

E =

     1     0     0     0
     0     1     0     0
     0     0     1     0
     0     0     0     1



## Magic

**magic(n)**
returns an `n`-by-`n` matrix constructed from the integers `1` through `n` with equal row and column sums. The order `n` must be a scalar greater than or equal to `3` in order to create a valid magic square

magic(5)
ans =

    17    24     1     8    15
    23     5     7    14    16
     4     6    13    20    22
    10    12    19    21     3
    11    18    25     2     9


## Pascal

**pascal(n)**
 The matrix returned is a symmetric positive definite matrix with integer entries taken from Pascal's triangle. The inverse of `P` has integer entries.

pascal(3)
ans =

     1     1     1
     1     2     3
     1     3     6



