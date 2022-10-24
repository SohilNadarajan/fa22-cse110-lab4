# DevTools Part 2 Answers

1. The bug was that the type of values being added were strings, so the result was just a concatenation of the two values instead of their sum.
2. I fixed this problem by casting the values to `Number`.