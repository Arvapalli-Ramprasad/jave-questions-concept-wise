1.Celsius to Fahrenheit 2
==========================
Given a temperature in Celsius, output the fahrenheit equivalent of it.

Note

Print complete answer up to 6 decimal places.

To do so, you can use the System.out.printf() function in Java

For example,

float myFloat = 76.45678f;
System.out.printf("%.3f", myFloat);
%.3f is the format specifier used in System.out.printf. It indicates that the value of myFloat should be printed as a floating-point number with three decimal places. The output is rounded to three decimal places: 76.457.

Input Format
Input consists of 1 line of a decimal number.

Output Format
Output consists of a single line of temperature in Fahrenheit.

EXAMPLE 1
Input:

32
Output::

89.600000
EXPLANATION:

To convert temperatures in degrees Celsius to Fahrenheit, multiply it by 9/5 or 1.8 and add 32.

EXAMPLE 2
Input:

25
Output:

77.000000
EXPLANATION:

To convert temperatures in degrees Celsius to Fahrenheit, multiply it by 9/5 or 1.8 and add 32.

Constraints
-100000 <= C <= 100000

Topics
Basics

==================================================================================================================================

2.Verify Cube
=================
Take two positive integers from the user. Verify if (a+b)^3 = a^3 + b^3 + 3a^2b + 3ab^2.

Calculate the Left hand side (LHS) and the right hand side (RHS) of the equation. Print the (LHS) and the (RHS).

Print VERIFIED in uppercase if they are equal, otherwise print NOT VERIFIED.

Input Format
The first line contains two integers A and B.

Output Format
Print two integers, the LHS and RHS in separate lines.

Then print "VERIFIED" (without quotes and in uppercase) if they are equal, else print "NOT VERIFIED".

Example 1
Input:
4 5

Output:
729
729
VERIFIED

Explanation:
We have A = 4 and B = 5.
Since, LHS = 729 and RHS = 729, our equation is Verified.

Example 2
Input:
1 2

Output:
27
27
VERIFIED

Explanation:
We have A = 1 and B = 2.
Since, LHS = 27 and RHS = 27, our equation is Verified.

Constraints
1 <= A <= 100000
1 <= B <= 100000



==================================================================================================================

3.Circle Area-Perimeter
=======================
You are required to take the radius of a circle as input from the user, and finally, print the area and perimeter of the circle.

Note: Take pi as 3

Input Format
One line contains an integer number which is the radius of a circle.

Output Format
Print the area of the circle in the first line

Print the perimeter of the circle in the second line

Example 1
Input

4
Output

48
24
Explanation

pi * r * r = 48 and 2 * pi * r = 24, where r is the radius.

Example 2
Input

7
Output

147
42
Explanation

pi * r * r = 147 and 2 * pi * r = 42, where r is the radius

Constraints
0 <= radius <= 100000

pi = 3

Topics
Math


==========================================================================================================


4.Variable Practice Question 1
==============================
Declare a variable named var and assign it a value of 10. Then print the string “My num is ” (without quotes) followed by the value stored in the variable.

Input Format
No input.

Output Format
Print the string “My num is ” followed by the value stored in the variable.

Output:

My num is 10


=============================================================================================================


5.Variable Practice Question 2
==============================
Declare a variable of type float named var and initialize its value to 10.45

After that re-initialize its value to 20.55 and print the variable var

Input Format
There is no input in this question

Output Format
Print value of variable var

Example 1
Input

No Input
Output

20.55
Topics
Basics


=============================================================================================================


6.Mathematical Operations
=========================
You are given two positive integers. You have to calculate the result by performing +,-,*,/,% operations on them.

Input Format
The first line of input contains two space-separated integers A and B.

Output Format
The first line of the output should contain the sum of A and B.

The second line of the output should contain the difference of A and B.

The third line of the output should contain the product of A and B.

The fourth line of the output should contain the quotient of A divided by B.

The fifth line of the output should contain the remainder of A modulus by B.

Example 1
Input:

8 3
Output:

11
5
24
2
2
Example 2
Input:

10 2
Output:

12
8
20
5
0
Constraints
1 <= A <= 10^3
1 <= B <= 10^3


=========================================================================================================


7.Celsius to Fahrenheit 2
=========================
Given a temperature in Celsius, output the fahrenheit equivalent of it.

Note

Print complete answer up to 6 decimal places.

To do so, you can use the System.out.printf() function in Java

For example,

float myFloat = 76.45678f;
System.out.printf("%.3f", myFloat);
%.3f is the format specifier used in System.out.printf. It indicates that the value of myFloat should be printed as a floating-point number with three decimal places. The output is rounded to three decimal places: 76.457.

Input Format
Input consists of 1 line of a decimal number.

Output Format
Output consists of a single line of temperature in Fahrenheit.

EXAMPLE 1
Input:

32
Output::

89.600000
EXPLANATION:

To convert temperatures in degrees Celsius to Fahrenheit, multiply it by 9/5 or 1.8 and add 32.

EXAMPLE 2
Input:

25
Output:

77.000000
EXPLANATION:

To convert temperatures in degrees Celsius to Fahrenheit, multiply it by 9/5 or 1.8 and add 32.

Constraints
-100000 <= C <= 100000

Topics
Basics


===============================================================================================================


8.Variable Practice Question 4
================================

Declare two variables as a and b. Initialize the values to those variables as 1042 and 7 respectively.

Declare another two variables quo and rem that will store the quotient and remainder of these numbers taking a as dividend and b as divisor.

Print quo and rem in a line separated by a space.

Input Format
No input. User has to declare the variables themselves.

Output Format
Print the quotient and remainder of these numbers by taking a as dividend and b as divisor.

Output:

148 6 