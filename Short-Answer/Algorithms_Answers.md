#### Please add your answers to the **_Analysis of Algorithms_** exercises here.

## Exercise I

a)O(log n^3)

b)O(n^2)

c)0(n-1)

## Exercise II

Start at f = 0. Drop an egg to see if it breaks. If not, drop and egg from position n to see if it breaks. If not, move to f = n - f / 2 (the middle). If an egg breaks go to the spot between n and f, if not,go to the spot between f and 0. Repeat until the correct f is found. This uses a binary search so n should be log(n)
