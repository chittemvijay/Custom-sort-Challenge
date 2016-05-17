# custom-sort
Challenge of custom sorting

An array of integers, arr, of size N is defined as {a , a , . . . , a }.
Complete the customSort function declared in your editor. It must take arr as a
parameter, sort its elements in order of ascending frequency, and then print each
element of the sorted array as a new line of output. If 2 or more elements have the
same frequency, this subset of elements should be sorted in non-decreasing order.

Input Format
The locked stub code in the editor handles reading input from stdin, assembling it into
an array of integers (arr), and calling the sort function. The first line of input
contains an integer, N (the number of elements). Each line i of the N subsequent lines
describes array element arr[i].
Constraints
1 ≤ N ≤ 2 × 10
1 ≤ a ≤ 10
Output Format
Your customSort function should print the sorted (in order of ascending frequency)
elements of array arr. If 2 or more elements have the same frequency, this subset
of elements should be sorted in non-decreasing order. Each element must be printed
on a new line.
Sample Input 0
53124
Sample Output 0
1342
Explanation
N = 5, arr = {3, 1, 2, 2, 4}
First, we separate our numbers by frequency. The subset of numbers having
frequency 1 is {3, 1, 4}. The subset of numbers having frequency 2 is {2, 2}.
Our partially sorted data (with respect to and in ascending order of frequency) can be
expressed as {{3, 1, 4}, {2, 2}}.
Then we sort each subset of elements having the same frequency in non-decreasing
order, resulting in {{1, 3, 4}, {2, 2}}.
Finally, we print each element of the sorted array on a new line
