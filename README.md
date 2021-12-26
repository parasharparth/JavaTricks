# JavaTricks

**In nextline**
code is here to explain that when in a single scanner input, if we have to take the input as integer and strings consecutively, then we have to use sc.nextLine to properly read the string because there are no empty strings after a integer.

**In System.out.printf** 
System.out.printf("%-15s%03d%n", s1, x); This statement is present to explain how formatting can be done using printf. 
Explanation for %-15s%03d%n is :- ("%-15s%03d%n", s1, x) % : used as a formatter. '-' : minus sign used for left indentation of the string. 15s : here 15 denotes the string's minimum field width 15. '0' : pads the extra 0s in the integer. 3d : here 3 denotes integer's minimum field width 3. %n : prints the new line

**In Table** 
Printed a table using proper fomatting (println)

**Series riddle**
Java loops-II problem on hackerrank

**In Datatype**
Java has 8 primitive data types; char, boolean, byte, short, int, long, float, and double. For this exercise, we'll work with the primitives used to hold integer values (byte, short, int, and long):

A byte is an 8-bit signed integer.
A short is a 16-bit signed integer.
An int is a 32-bit signed integer.
A long is a 64-bit signed integer.
Given an input integer, you must determine which primitive data types are capable of properly storing that input.

**END OF FILE**
The challenge here is to read  lines of input until you reach EOF, then number and print all  lines of content.
Input Format
Read some unknown  lines of input from stdin(System.in) until you reach EOF; each line of input contains a non-empty String.
Output Format
For each line, print the line number, followed by a single space, and then the line content received as input.

**Static initialization blocks**
Static initialization blocks are executed when the class is loaded, and you can initialize static variables in those blocks.
In this example, we are calculating the area of parallelogram using the static initialization blocks
