We are given a recursive pseudocode function and need to evaluate its output when a = 8 and b = 8.

Integer funn(Integer a, Integer b)
    if(a && b && a + b > 0)
        return a + funn(a - 2, b - 2) + b
    End if
    return a ^ b
End function

----------solution-----------

We call: funn(8, 8)

1. funn(8, 8):
a && b && a + b > 0 → true (8 && 8 && 16 > 0)

So, return: 8 + funn(6, 6) + 8

2. funn(6, 6):
true → return 6 + funn(4, 4) + 6

3. funn(4, 4):
true → return 4 + funn(2, 2) + 4

4. funn(2, 2):
true → return 2 + funn(0, 0) + 2

5. funn(0, 0):
Condition fails (0 && 0 == false)

Return 0 ^ 0 = 0


Back to funn(2, 2):
→ 2 + 0 + 2 = 4

Back to funn(4, 4):
→ 4 + 4 + 4 = 12

Back to funn(6, 6):
→ 6 + 12 + 6 = 24

Back to funn(8, 8):
→ 8 + 24 + 8 = 40
