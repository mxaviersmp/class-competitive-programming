# F - Zeros and Ones

Given a string of 0’s and 1’s up to 1000000 characters long and indices i and j, you are to answer
a question whether all characters between position min(i, j) and position max(i, j) (inclusive) are the
same.

## Input

There are multiple cases on input. The first line of each case gives a string of 0’s and 1’s. The next
line contains a positive integer n giving the number of queries for this case. The next n lines contain
queries, one per line. Each query is given by two non-negative integers, i and j. For each query, you
are to print ‘Yes’ if all characters in the string between position min(i, j) and position max(i, j) are the same, and ‘No’ otherwise.

## Output
Each case on output should start with a heading as in the sample below. The input ends with an empty
string that is a line containing only the new line character, this string should not be processed. The
input may also with end of file. So keep check for both.

## Sample Input

```
0000011111
3
0 5
4 2
5 9
01010101010101010101010101111111111111111111111111111111111110000000000000000
5
4 4
25 60
1 3
62 76
24 62
1
1
0 0
```

## Sample Output

```
Case 1:
No
Yes
Yes
Case 2:
Yes
Yes
No
Yes
No
Case 3:
Yes
```