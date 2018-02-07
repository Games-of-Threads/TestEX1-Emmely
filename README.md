# TestEX1-Emmely Lundberg cph-el69

## Test Cases Successful/Unsuccessfull

Input     |  Expected Output  |   Actual Output   |  Outcome (Pass or fail)
--------- | ----------------- | ----------------- | -----------------------
1, 1, 1   | Equilateral       | N/A               | N/A
4, 4, 4   | Equilateral       | N/A               | N/A
4, 1, 1   | Isoceles          | N/A               | N/A
1, 3, 3   | Isoceles         | N/A               | N/A
10000, 10000, 10000   | Equilateral       | N/A               | N/A
0, 1, 1   | Error (Ilegal input: 0)       | N/A               | N/A
3, -3, 3   | Error (Ilegal input: -1)       | N/A               | N/A
3, 2, 1   | Scalene       | N/A               | N/A
2147483648, 1147483647, 200000   | Error (Out of bounds)       | N/A               | N/A
1.5, 3.8, 2.5 | Error (Ilegal input: floats/doubles) | N/A | N/A
67, 67, 32   | Isoceles       | N/A               | N/A
1994, 1994, 1994   | Equilateral       | N/A               | N/A
1, 1, 1, 0   | Error       | N/A               | N/A
1, 1   | Error       | N/A               | N/A
"One", "Two", "Three"   | Error       | N/A               | N/A
