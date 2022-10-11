#Hash-Function

**In a simple hashing function, a series of numbers becomes a single number.First, the output value is assumed to be equal to an initial value of s, then for each number in the numerical series, the output value is added to that number and multiplied by s.**
**In order not to increase the number too much, after each step, the output value is equal to the remainder of dividing it by M reference number.**

1. = 7
2. = (7 + 2) * 7 = 63 = 6 (mod 19) 
3. = (6 + 4) * 7 = 70 = 13 (mod 19)
4. = (13 + 8) * 7 = 147 = 14 (mod 19)

------------------
7 19   |         |
3      |       14|
2 4 8  |         |
------------------

**this is a git setup on Linux.**
