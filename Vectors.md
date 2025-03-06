-----


## Create a vector

Values to create a vector are: **start : step : end**
	-> *start* the value at which the vector starts
	-> *step* how fast the vector's value change, may be omitted
	-> *end* at what value the vector will end
	
v = 2:3:12
v =

     2     5     8    11


## Vectors from matrices

A =
     1     2     3     4
     5     6     7     8
     9     0     1     2
     3     4     5     6
     7     8     9     0


A(1:3,2) rows from 1 to 3 in the column 2
ans =

     2
     6
     0

A(1:2:5,2)

ans =

     2
     0
     8

A(1:3,2:4)

ans =

     2     3     4
     6     7     8
     0     1     2



## Linear Space

**Command**
	linspace(start, end, n)
creates vector with n elements from interval [start; end]
where the distance between consecutive elements is constant


x= linspace(0,10,10)
x =

  Columns 1 through 9

	 0    1.1111    2.2222    3.3333    4.4444    5.5556    6.6667    7.7778    8.8889

  Column 10

`   10.0000 ``
