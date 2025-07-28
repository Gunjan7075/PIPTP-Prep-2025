What will be the output of the following pseudocode of fun(w, x) for w = 40 and x = 4?

1.  void fun( Integer w, Integer x)
2.      Integer y
3.      Set y = 0
4.      if (x mod w EQUALS 0) || (w mod x EQUALS 0)
5.          y = y + 1
6.      Else
7.          y = y + 10
8.      End if
9.      Print y
10. End function fun()

the answer of this question is -------------

(x mod w == 0) || (w mod x == 0)
(4 mod 40 == 0) || (40 mod 4 == 0)
Evaluate:

4 mod 40 = 4 ⇒ not 0

40 mod 4 = 0 ⇒ yes, equals 0

So:

Therefore, the condition is true, and the code goes into the if block.

y = y + 1 = 0 + 1 = 1
so the given output of this problem is 1
