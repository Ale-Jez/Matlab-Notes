-----


## Columns

**A (:, [1 3 2 4])** changes the order of columns

A =

     1     2     3     4
     5     6     7     8
     9     0     1     2
     3     4     5     6
     7     8     9     0

A (:, [1 3 2 4])

ans =

     1     3     2     4
     5     7     6     8
     9     1     0     2
     3     5     4     6
     7     9     8     0



## Mirroring the matrix

**fliplr(A)** gets the mirror image of the matrix with the mirror set **vertically**

ans =

     4     3     2     1
     8     7     6     5
     2     1     0     9
     6     5     4     3
     0     9     8     7




**flipud(A)** gets the mirror image of the matrix with the mirror set **horizontally**

ans =

     7     8     9     0
     3     4     5     6
     9     0     1     2
     5     6     7     8
     1     2     3     4



## Rows
**A([1 3 2 4 5],:)** swaps the second and the third row

A =

     1     2     3     4
     5     6     7     8
     9     0     1     2
     3     4     5     6
     7     8     9     0

A([1 3 2 4 5],:)

ans =

     1     2     3     4
     9     0     1     2
     5     6     7     8
     3     4     5     6
     7     8     9     0
