What will be the output of the following pseudocode?

1.  Integer a, b, c
2.  Set a = 2, b = 3
3.  for (each c from 4 to 6)
4.      a = a + b
5.      if(a > 4)
6.          a = 0
7.      End if
8.      if(a + 2)
9.          b = a + 10
10.     Else
11.         Jump out of the loop
12.     End if
13.     b = a + 1
14. End for
15. Print a + b

 --------SOLUTION----------

17. Loop Simulation (c = 4 to 6)

18. Iteration 1 (c = 4)
19. 
Line 4: a = a + b = 2 + 3 = 5

Line 5: if(a > 4) → 5 > 4 → true → a = 0

Line 8: if(a + 2) → 0 + 2 = 2, true → Line 9: b = a + 10 = 0 + 10 = 10

Line 13: b = a + 1 = 0 + 1 = 1


Iteration 2 (c = 5)

Line 4: a = a + b = 0 + 1 = 1

Line 5: a = 1, not > 4 → skip

Line 8: a + 2 = 1 + 2 = 3 → true → Line 9: b = 1 + 10 = 11

Line 13: b = a + 1 = 1 + 1 = 2

Iteration 3 (c = 6)
Line 4: a = a + b = 1 + 2 = 3

Line 5: 3 > 4 → false → skip

Line 8: a + 2 = 3 + 2 = 5 → true → Line 9: b = 3 + 10 = 13

Line 13: b = a + 1 = 3 + 1 = 4

Final Values:
a = 3
b = 4
Final Output (Line 15): a + b = 3 + 4 = 7



