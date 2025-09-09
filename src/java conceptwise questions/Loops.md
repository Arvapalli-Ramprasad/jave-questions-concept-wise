Sum of Natural Numbers
=======================
You are given an integer N. Your task is to output the sum of all natural numbers till N.

Natural numbers are a part of the number system, including all the positive numbers from 1 to infinity.

Input Format
First line is an integer N

Output Format
Print the sum of the first N natural numbers.

Example 1
Input

5
Output

15
Explanation

Here, n = 5, so 1 + 2 + 3 + 4 + 5 = 15

Example 2
Input

1
Output

1
Explanation

Here, n = 1, so sum = 1

Constraints
1 <= N < = 108

Topics
Basics
Math


==============================================================================================================


Check Prime
============
Write a program that inputs a positive integer N. It should then output a message indicating whether the number is a prime number or not.

Input Format
A single line containing the integer N

Output Format
Print a string, either "N is a prime number" or "N is not a prime number" (without quotes), depending on whether N is prime or not.

Example 1
Input

5
Output

5 is a prime number
Explanation

5 is only divisible by itself and 1, hence it's a prime number.

Example 2
Input

10
Output

10 is not a prime number
Explanation

1,2,5 & 10 are factors of 10, hence it is not a prime number.

Constraints
1 <= n <= 10^9

Topics
Math

===================================================================================================================


Odd Numbers
===========
You have to keep taking integers as input until you get an odd number as input. Your output will be N, which represents the number of numbers you had to take as input uptill encountering an odd number.

Input Format
You will be given N-1 even numbers followed by an odd number.

Output Format
For each test case print the value of N in a new line.

Example 1
Input

4
8
6
10
12
13
Output

6
Explanation

The sixth integer was an odd number.

Example 2
Input

8
13212
332
134
4418
909
Output

6
Explanation

The sixth integer was an odd number.

Constraints
1 <= N <= 100000

Topics
Basics
Math

=================================================================================================================

Reverse digits of a Number
==========================
Write a program that prompts the user to input an integer and then outputs the number with the digits reversed.

For example, if the input is 12345, the output should be 54321.

Note: Input number will not have any trailing zeros.

Input Format
The first line of input contains the integer n.

Output Format
The output should be the reverse of n.

Example 1
Input

12345
Output:

54321
Example 2
Input

143323
Output

323341
Constraints
1 <= n <= 10^9

n will not have any trailing zeros.

Topics
Loops
Basics
Companies
MAQ Software
MakeMyTrip

==================================================================================================================


Print Digits
============
Given the number n, print its digits starting from most significant digit to least significant digit.

Input Format
Input consists of single line which has the integer n.

Output Format
print the digits of number one line at a time.

Example 1
Input

1256
Output

1
2
5
6
Explanation

Here, the digits are, 1,2,5,6.

Example 2
Input

12345
Output

1
2
3
4
5
Explanation

Here the digits are 1,2,3,4,5.

Constraints
1 <= n <= 10^9

Topics
Basics
Math

================================================================================================================


Which Case
==========
You are required to take input of a character from the user. The task is to print the following

1, if the character is a uppercase alphabet(A to Z)

0, if the character is a lowercase alphabet(a to z)

-1, if the character is not an alphabet

Input Format
First line contains a character

Output Format
One line output of either 1 or 0 or -1 according to the conditions mentioned in the question

Example 1
Input

B
Output

1
Explanation

'B' is an uppercase alphabet.

Example 2
Input

i
Output

0
Explanation

'i' is a lowercase alphabet.

Constraints
User can input any one character.

Topics
Basics
Companies
Tech Mahindra


===================================================================================================================


Palindrome Checker
==================
Given a number N, you need to check whether the given number is Palindrome or not. A number is said to be Palindrome when it reads the same from backwards as forward.

Note: Input number will not have any trailing zeros.

Input
The line inputs N.

Output
You need to print "true" if the number is palindrome otherwise "false" (without quotes).

Example 1
Input

5
Output

true
Example 2
Input

121
Output

true
Constraints:
1 <= N <= 9999

Topics
2-Pointers
Math
Companies
Samsung
Oracle
Adobe
Zoho

=====================================================================================================================


Factorial with loop
===================
Factorial of any given number n is represented as n! = n * n-1 * n-2 .....* 1. Write a program to calculate the factorial of a given number.

Note: Factorial of 0 is 1.

Input Format
The first line consists of a single integer denoting n.

Output Format
Output is a single line containing factorial of n.

Example 1
Input:

5
Output:

120
Explanation:

5! = 5*4*3*2*1 = 120.
Example 2
Input:

4
Output:

24
Explanation:

4! = 4*3*2*1 = 24.
Constraints
0 <= n <= 20

Topics
Loops
Companies
Wipro


=====================================================================================================================


Number Rotation
===============
Given two numbers n and k, you need to rotate n, k times to the right. If k is negative, rotate n, k times to the left.

Note:

Rotating right means removing rightmost digit from n and adding it to the start.

Rotating left means removing leftmost digit from n and adding it to the end.

Assume that the number of rotations will not result in leading 0's, i.e. n=1203, k =2 such that 0312 is the answer, such test cases will not be given.

k can be bigger than n.

Input Format
First line which has two integer n and k.

Output Format
Print the rotated number in a single line.

Example 1
Input

1256 1
Output

6125
Explanation

since k=1, right rotating the number one time leads to 6125.

Example 2
Input

1256 -1
Output

2561
Explanation

since k=1, left rotating the number one time leads to 2561.

Constraints
1 <= n,k <= 10^9

Topics


==================================================================================================================

Nested Loops
============

==================================================================================================================

Staircase
=========
In this question, you need to write a program that prints a staircase of size N.

This is a staircase of size n=4:

#
##
###
####
Its base and height are both equal to n. It is drawn using # symbols and spaces. The last line is not preceded by any spaces.

Input Format
A single integer, n, denotes the size of the staircase.

Output Format
Print a staircase of size n using # symbols and spaces.

Note: The last line must not have spaces in it.

Example 1
Input

6
Output

#
##
###
####
#####
######
Explanation

The staircase is right-aligned, composed of # symbols and spaces, and has a height and width of n=6.

You might notice, first line has 5 spaces (n-1) followed by 1 # and the last line has 0 spaces (n-n) and 6 # (n)

Example 2
Input

5
Output

#
##
###
####
#####
Explanation

The staircase is right-aligned, composed of # symbols and spaces, and has a height and width of n=5.

You might notice, first line has 4 spaces (n-1) followed by 1 # and the last line has 0 spaces (n-n) and 5 # (n)

Constraints
1 <= n < 100

Topics

========================================================================================================================


Print Continuous Character Pattern
==================================
Given an integer n that denotes the number of rows to be printed, print the pattern in which each row starts with its corresponding alphabet and has a length equal to the row number. (See the examples for a better understanding).

Note: You can take the alphabet to be cyclic. On reaching Z, you will cycle back to A, then B, and so on.

Input Format
First line contains the value n representing the number of rows.

Output Format
Print the pattern.

Example 1
Input

5
Output
A
BC
CDE
DEFG
EFGHI

Constraints
1 <= n <= 26

Topics
Strings - Basics
Strings


================================================================================================================


Print Continuous Character Pattern
==================================
Given an integer n that denotes the number of rows to be printed, print the pattern in which each row starts with its corresponding alphabet and has a length equal to the row number. (See the examples for a better understanding).

Note: You can take the alphabet to be cyclic. On reaching Z, you will cycle back to A, then B, and so on.

Input Format
First line contains the value n representing the number of rows.

Output Format
Print the pattern.

Example 1
Input

5
Output
A
BC
CDE
DEFG
EFGHI

Constraints
1 <= n <= 26

Topics
Strings - Basics
Strings

====================================================================================================================


Print Character Pattern
=======================
You are given a number N. Print a pattern consisting of N rows, where the first row has 1 A, the second row has 2 Bs, and so on for N letters. Check the examples for a better understanding.

Input Format
First line of input contains N, the number of rows for the pattern

Output Format
You need to print the pattern.

Example 1
Input

4
Output:

Pattern Image

Explanation:

For number of rows to be 4 we get this output.

Example 2
Input

5
Output:

Pattern Image

Explanation:

For number of rows to be 5 we get this output.

Constraints:

1 <= N <= 26

Topics
Loops

=================================================================================================================


Print Number Pattern 3
======================
You are given n the number of row of the pattern you have to print.

Input Format
The first line of input contains n the number of rows in the pattern.

Output Format
For each n, print the following pattern.

Example 1
Input

5
Output

0
1 1
2 3 5
8 13 21 34
55 89 144 233 377
Explanation

In the example input you are given 5 rows, and this is the desired patttern.

Example 2
Input

7
Output

0
1 1
2 3 5
8 13 21 34
55 89 144 233 377
610 987 1597 2584 4181 6765
10946 17711 28657 46368 75025 121393 196418
Explanation

The 7 row pattern is given in the output.

Constraints
1 <= n <= 50

Topics
Dynamic Programming
Math


====================================================================================================================


Diamond Pattern
===============
Given an integer N, print a diamond full of stars * with height equal to N.

Note It is given that N is odd.

Input Format
The first line contains the number of test cases.

For each test case: The first line contains an integer N denoting the height of the pyramid.

Output Format
For each test case print the required pattern.

Example 1
Input
5
Output

  *
 ***
*****
 ***
  *
Explanation

The required diamond of height 5 has been returned.

Explanation

The required diamond of height 3 has been returned.

Constraints
1 <= T <= 10

1 <= N <= 100

N is odd.

Topics
Loops


====================================================================================================================

Armstrong Number
================
Write a program to print out all Armstrong numbers between 1 and N.

A number is called an Armstrong number if the sum of cubes of each digit of the number is equal to the number itself.

For example, 153 = ( 1 * 1 * 1 ) + ( 5 * 5 * 5 ) + ( 3 * 3 * 3 )

Input Format
The input contains a single integer representing N.

Output Format
Print all the Armstrong numbers from 1 to N in separate lines.

Example 1
Input

200
Output

1
153
Explanation

1 and 153 are only Armstrong numbers between 1 to 200.

Example 2
Input

1000
Output

1
153
370
371
407
Explanation

1, 153, 370, 371, 407 are only Armstrong numbers between 1 to 1000.

Constraints
1 <= N <= 10^6

Topics
Loops
Basics
Math
Companies
Oracle
VMware

=====================================================================================================================


Right Angle Triangle Stars
==========================
Given an integer n, print a right angled triangle full of stars with height and base equal to n.

Input Format
The first line of input contains the integer n.

Output Format
The output should contain a right angled triangle filled with stars with height and base equal to n.

Example 1:
Input

3
Output:

*
**
***

Explanation:

Since n = 3, 3 lines with increasing number of stars are printed.

Example 2:
Input

7
Output

*
**
***
****
*****
******
*******
Explanation:

Since n = 7, 7 lines with increasing number of stars are printed.

Constraints
1 <= n <= 200

Topics
Loops


===================================================================================================================


Print Number Pattern 2
======================
Given an integer n, print a pattern of n lines, where the ith line has the numbers i to 1 printed in descending order. Check the sample cases for a better understanding.

Input Format:
Input consists of an integer N.

Output Format:
Print the pattern as described above.

Example 1
Input:

5
Output:

Pattern Image

Example 2
Input:

3
Output::

Pattern Image

Constraints
1 <= n <= 9

Topics
Loops

==================================================================================================================


Star Pyramid
============
Given an integer n, print a pyramid full of stars with height equal to n.

Input Format
The first line of input contains the integer n.

Output Format
The output should contain a pyramid filled with stars with height equal to n.

Example 1
Input

3
Output:

  *
 * *
* * *
Pattern Image

Example 2
Input

7
Output

Pattern Image

Constraints
1 <= n <= 200

Topics
Loops









