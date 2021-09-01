# collatz

## Progression and Regression Patterns

Where k is a positive integer:

The progression pattern is always symmetric from [0, 2^k-2].

The regressive pattern is always symmetric from [1, 2^k-1].

Progression is the number of consecutive times (x*3+1)/2 results in an odd integer and only applies to odd integers.

Regression is the number of consecutive times x/2 results in an even integer and only applies to even integers.

| \# | p | r | yield|
| -- | -- | -------- | ---------- |
| 0  | \- | infinity | unyielding |
| 1  | 0  | \-       | 2          |
| 2  | \- | 0        | 1          |
| 3  | 1  | \-       | 8          |
| 4  | \- | 1        | 1          |
| 5  | 0  | \-       | 4          |
| 6  | \- | 0        | 3          |
| 7  | 2  | \-       | 26         |
| 8  | \- | 2        | 1          |
| 9  | 0  | \-       | 14         |
| 10 | \- | 0        | 5          |
| 11 | 1  | \-       | 26         |
| 12 | \- | 1        | 3          |
| 13 | 0  | \-       | 26         |
| 14 | \- | 0        | 7          |
| 15 | 3  | \-       | 80         |
| 16 | \- | 3        | 1          |
| 17 | 0  | \-       | 26         |
| 18 | \- | 0        | 9          |
| 19 | 1  | \-       | 44         |
| 20 | \- | 1        | 5          |
| 21 | 0  | \-       | 32         |
| 22 | \- | 0        | 11         |
| 23 | 2  | \-       | 80         |
| 24 | \- | 2        | 3          |
| 25 | 0  | \-       | 38         |
| 26 | \- | 0        | 13         |
| 27 | 1  | \-       | 62         |
| 28 | \- | 1        | 7          |
| 29 | 0  | \-       | 44         |
| 30 | \- | 0        | 15         |
| 31 | 4  | \-       | 242        |
| 32 | \- | 4        | 1          |
| 33 | 0  | \-       | 50         |
| 34 | \- | 0        | 17         |
| 35 | 1  | \-       | 80         |
| 36 | \- | 1        | 9          |
