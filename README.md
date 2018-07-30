# PA4
CSC2301 Programming Assignment 4

1. Write an assembly program that takes two integer values, *startval* and *endval* where *startval <= endval*, and sums all the integers between those two values.  For example, if *startval* = 1, and *endval* = 5, the program would compute 1 + 2 + 3 + 4 + 5, which is 15.  Some code is provided in `PA4-1.s` to get you started.  This code creates the two integers, *startval* and *endval*, loads *startval* into R2 and *endval* into R3.   Your program should use a loop to add up all the integers between those two numbers.  The final result should be in R1. You must use a loop to do this.  Hint:  Think about how you might write such a loop in C++ or Java, and convert that into ARM assembly.  

2. Write an assembly program that takes an integer, *n*, and computes *n!* (*n* factorial = *n * (n -1) * (n – 2) … * 2 * 1*) and puts that value into register R2.  You are given some starter code, `PA4-2.s`, that creates the integer *n*, and reads a value in using `scanf`.  Your code should use a loop to compute *n!*  Note that, *0!* = *1*, and *1!* = *1*.  Try different values of *n* to test your code!

## Grading Rubric

### Comments
Your code must contain (in comments)
 * Name of author (or both partners for pair assignments)
 * Name of assignment
 * Date assignment is completed
 * A short (one or two line) description of what your program does.
 * A description of how each register in the program is being used
 * When subroutines are created, a description of all inputs and the purpose of the function
 * Any outside resources (other than textbook, or slides) utilized in the completion of the project
 * __Each line of new code you write should indicate what that line of code is doing.__

### Grading standard

| Standard | Correctness | Design and Efficiency | Comments and format |
|----------|-------------|-----------------------|---------------------|
|Full credit|Program fully implements the operational requirements as set forth in the assignment.  For all test inputs, the program produces the correct result.: 20 points | Code implements the algorithm in the most efficient manner possible: 5 points | Code contains all the  comments listed above: 5 points |
| Good | Program produces the correct result in 75% of the test cases: 15 points | Code does two or three operations that are not needed, or could be simplified: 3 points | 1 or 2 items missing or code not neat: 3 points |
| Fair | Program produces the correct result in 50% of the test cases: 10 points | Code does many inefficient operations, but is generally able to be followed:  2 points | about half of comments are missing: 2 points |
| Poor | Program produces the correct result in less than 50% of the test cases, but a reasonable attempt has been made to write correct code: 5 points | | Minimal commenting: 1 point |
| Nothing | Code not turned in or does not appear to address the operational requirements in any meaningful way: 0 | Code is very inefficient or convoluted or difficult to follow: 0 | No commenting: 0 |
