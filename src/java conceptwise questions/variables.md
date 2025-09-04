Celsius to Fahrenheit 2
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



2. Verify Cube
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