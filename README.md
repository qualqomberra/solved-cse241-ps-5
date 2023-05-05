Download Link: https://assignmentchef.com/product/solved-cse241-ps-5
<br>
<h1>1)</h1>

Write the definition for a class named Vector2D that stores information about a two-dimensional vector. The class should have functions to get and set the <em>x </em>and <em>y </em>components, where <em>x </em>and <em>y </em>are integers. Next, overload the * operator so that it returns the dot product of two vectors. The dot product of two-dimensional vectors <strong>A </strong>and <strong>B </strong>is equal to




(A <em>x </em>* B <em>x </em>) + (A <em>y </em>* B <em>y </em>).

Finally, write a main subroutine that tests the * operation.




<h1>2)</h1>

Define a class named MyInteger that stores an integer and has functions to get and set the integer’s value. Then, overload the [] operator so that the index returns the digit in position <em>i </em>, where <em>i </em>= 0 is the least-significant digit. If no such digit exists then –1 should be returned.

For example, if x is of type MyInteger and is set to 418, then <em>x </em>[0] should return 8, <em>x </em>[1] should return 1, <em>x </em>[2] should return 4, and <em>x </em>[3] should return –1.




<h1>3)</h1>

Define a class named PrimeNumber that stores a prime number. The default constructor should set the prime number to 1. Add another constructor that allows the caller to set the prime number. Also, add a function to get the prime number. Finally, overload the prefix and postfix ++ and — operators so they return a PrimeNumber object that is the next largest prime number (for ++) and the next smallest prime number (for –). For example, if the object’s prime number is set to 13, then invoking ++ should return a PrimeNumber object whose prime number is set to 17. Create an appropriate test program for the class.


