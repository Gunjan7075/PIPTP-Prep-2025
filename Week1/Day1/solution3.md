What will be the output of the following pseudocode.

1.  Integer a, b, c
2.  Set a = 2, b = 4, c = 2
3.  if(b - a)
4.      b = a ^ b
5.      a = c
6.      if(b)
7.          a = a ^ b
8.      End if
9.      b = b - 1
10. End if
11. if(c)
12.     a = b
13. End if
14. Print a + b + c


---------solution----------

Initial Values
a = 2
b = 4
c = 2

if(b - a)
b - a = 4 - 2 = 2, which is non-zero ⇒ true

b = a ^ b

a = 2 = 010 (binary)
b = 4 = 100 (binary)
a ^ b = 010 ^ 100 = 110 = 6
So, b = 6

Line 5:  a = c
Now a = 2 (since c = 2)

Line 6:  if(b)
b = 6, non-zero ⇒ true

Line 7: a = a ^ b
a = 2 = 010
b = 6 = 110
a ^ b = 010 ^ 110 = 100 = 4
Now, a = 4

Line 9: b = b - 1 = 6 - 1 = 5
Now values are:
a = 4
b = 5
c = 2
Line 11: if(c)
c = 2, which is true ⇒ go inside

Line 12: a = b
a = 5

Final Values:
a = 5
b = 5
c = 2

Print a + b + c
5 + 5 + 2 = 12

Final Output: 12







