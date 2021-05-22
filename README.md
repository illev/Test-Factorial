# Test-Factorial
This exercise is about getting familiar with unit testing and JUnit 5 approach in particular.

First, you need to design and code a  method in
the Factorial class. Here are some details:

the method takes a String as a parameter, transforms it to an integer value and counts its factorial.
The method returns a result as a String.
String parameter  must represent a non-negative integer number. If it does not, throw an IllegalArgumentException.
Next, you need to complete the test classes:

FactorialBadInputTesting
There are four empty methods that you must complete:
testNullInput
testNegativeInput
testFractionalInput
testNonDigitalInput
FactorialCsvParametrizedTesting
This is a parameterized test, that takes arguments from the csvCases.csv file. Do
not change the csv file, only implement the method.
FactorialMethodSourceParametrizedTesting
This is a parameterized test, that takes arguments from the  method. You must complete the test method and
introduce the  method, that provides following cases:
"1", "1"
"2", "2"
"5", "120"
FactorialRegularInputTesting
This is a test class where you can add regular test cases. Consider covering cases that are not present in other test
classes.
In order to pass the exercise, your tests must correctly detect flaws of some other implementations. There are special
tests in several classes that applies your tests to your and some of such bad implementations:

FactorialTestingsTest
LazyFactorialTestingsTest
WrongOperationConcatIntFactorialTestingsTest
WrongOperationSumIntFactorialTestingsTest
Your solution method must pass your tests, and others must fail in some cases.

Also, there is one more secret test class that you do not have access to. It will be applied to your solution once you
submit it to Autocode. So, mind variety of possible cases.

Hint: 
Factorial reference
﻿

This exercise is about getting familiar with unit testing and JUnit 5 approach in particular.
Design and code a factorial method in the Factorial class. Here are some details:

The method takes a String as a parameter, transforms it to an integer value, and counts its factorial.
The method returns a result as a String.
The string parameter n must represent a non-negative integer number. If it does not, throw an IllegalArgumentException.

Complete the test classes:
FactorialCsvParametrizedTesting  –
FactorialMethodSourceParametrizedTesting  –


FactorialBadInputTesting
There are four empty methods that you must complete:


testNullInput - test null input cases

testNegativeInput - test negative number input cases

testFractionalInput - test fractional cases

testNonDigitalInput - test non-digit cases



FactorialCsvParametrizedTesting
It is a parameterized test that takes arguments from the csvCases.csv file.
Do not change the csv file, only implement the method.

FactorialMethodSourceParametrizedTesting
It is a parameterized test that takes arguments from the testCases method.
Complete the test method and introduce the method that provides the following cases:

"1", "1"
"2", "2"
"5", "120"



FactorialRegularInputTesting
It is a test class where you can add regular test cases.
Consider covering the cases that are not present in other test classes.

To pass the exercise, your tests must correctly detect flaws of some other implementations.
There are special tests in several classes that apply your tests to your implementation and other problematic (“bad”) ones:

FactorialTestingsTest
LazyFactorialTestingsTest
WrongOperationConcatIntFactorialTestingsTest
WrongOperationSumIntFactorialTestingsTest

Your solution method must pass your tests while other implementations must fail your tests in some cases.
Also, there is one more secret test class that you do not have access to. It will be applied to your solution once you submit it to Autocode. So, consider the variety of possible cases.
Hint: Factorial reference
