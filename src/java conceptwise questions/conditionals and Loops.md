1.Grading System
=================
You are given marks of a student as input. Display a correct message based on the following rules:

for marks above 90, print "Excellent".
for marks above 80 and less than equal to 90, print "Good"
for marks above 70 and less than equal to 80, print "Fair".
for marks above 60 and less than equal to 70, print "Meets Expectations".
for marks below and equal to 60, print "Below Expectations".


Input Format
There is a single integer N.

Output Format
Print a single string in a line.

Example 1
Input

95
Output

Excellent
Explanation

As according to the given condition, for N (marks) >90 - Excellent is printed

Example 2
Input

75
Output

Fair
Explanation

As according to the given condition, for 70 < N (marks) <= 80 - Fair is printed

Constraints
1 <= |N| <= 100

Topics
Conditionals
Basics


=============================================================================================================


2.Leap Year
===========
Given a year, find if it is a leap year.

A Leap year is a year that is multiple of 4. However, multiples of 100 except for the multiples of 400 are not leap years.

Your task is to print 1 or 0 depending upon if the year is a leap year or not.

Input Format
An integer Y, denoting the year.

Output Format
Print 1, if the given year is a leap year or 0 otherwise.

Example 1
Input

2004
Output

1
Explanation

2004 is divisible 4 by hence it's a leap year

Example 2
Input

2000
Output

1
Explanation

2000 is divisible by 400 hence, it is a leap year.

Example 3
Input

1900
Output

0
Explanation Since 1900 is divisible by 100 but not divisible by 400, so it is not a leap year.

Constraints
1000 <= Y <= 9999

Topics
Basics
Math
Companies
Zoho

============================================================================================================


3.Which angled triangle
=======================
Given the 3 sides of a triangle, find out whether it is acute-angled, right-angled, or obtuse-angled.

You need to output 1 for acute, 2 for right-angled, and 3 for an obtuse-angled triangle. You can assume that the input values always form a triangle and are valid integers.

Note

A triangle is acute-angled, if twice the square of the largest side is less than the sum of squares of all the sides.

A triangle is obtuse-angled, if twice the square of its largest side is greater than the sum of squares of all the sides.

A triangle is right-angled, if twice the square of its largest side is exactly equal to the sum of squares of all the sides.

Example 1
Input

3 4 5
Output

2
Explanation


Since 2x5x5 is equal to 5x5 + 3x3 + 4x4,
So this is a right-angled triangle and hence, the answer is 2.

Example 2
Input

3 3 3
Output

1
Explanation


Since 2x3x3 is less than 3x3 + 3x3 + 3x3,
So this is an acute-angled triangle and hence, the answer is 1.

Constraints
1 < a , b , c <= 10^5

Topics
Math


======================================================================================================================


4.Which Case
============
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


=====================================================================================================================


5.Number of Days
================
Given the number of the month, your task is to calculate the number of days present in the particular month.

Note:- Consider non-leap year.

Input Format
An integer M, denoting the number of the month.

Output Format
Return the number of days in the month corresponding to the given number. Consider a non-leap year.

Example 1
Input

1
Output

31
Explanation

January has 31 days.

Example 2
Input

3
Output

31
Explanation

March has 31 days.

Constraints
1 <= M <= 12

Topics
Conditionals


======================================================================================================================


6.Conditional Problem 6
=======================
You are given two integers a and b. You need to perform the following operations

If both integers are odd, print `we are odd`.
Else print `we are simple`.
Input Format
First line contains two variables a and b.

Output Format
Output will be "we are odd" if both the variables are odd numbers. Otherwise output will be "we are simple".

Example 1
Input

1 3
Output

we are odd
Example 2
Input

2 5
Output

we are simple
Constraints
-10^8 <= a, b <= 10^8

Topics
Conditionals
