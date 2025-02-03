Problem Statement:
You are given an array of integers and need to answer multiple range sum queries efficiently. Implement a solution using Square Root Decomposition.

Input Format:
The first line contains two integers n (size of the array) and q (number of queries).
The second line contains n integers representing the elements of the array.
The next q lines contain queries, which can be of two types:
- UPDATE index value: Update the element at position index to value.
- QUERY L R: Calculate the sum of elements in the range [L,R].

Output Format:
For each QUERY operation, output the sum of the elements in the specified range.


Example:
Input:
8 6
1 2 3 4 5 6 7 8
QUERY 2 5
UPDATE 3 10
QUERY 2 5
QUERY 1 8
UPDATE 8 15
QUERY 5 8

Output:
14
21
43
33
