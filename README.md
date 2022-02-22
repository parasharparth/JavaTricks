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

**Conversions**
This is the example for conversions between an integer and string

**Calender**
Example for calender class

**Calender Local and Global Date and Time**
Example for Global Date and Time

**Comparator**
Comparator Example

**Regex Example-1**
Checking the regex

**Regex Ip Validation**
Validating the IP address in the format of 
000.12.12.034
121.234.12.12
23.45.12.56

Invalid IP addresses are:- 
000.12.234.23.23
666.666.23.23
.213.123.23.32
23.45.22.32.
I.Am.not.an.ip

**Java Regex-Duplicate-Words-removal**
This program removes any duplicate words from the input provided

**invalidUsernameRegex.java**
It identifies the invalid username according to the policy as mentioned below:- 
The username consists of 8 to 30 characters inclusive. If the username consists of less than  8 or greater than 30 characters, then it is an invalid username.
The username can only contain alphanumeric characters and underscores (_). Alphanumeric characters describe the character set consisting of lowercase characters , uppercase characters , and digits .
The first character of the username must be an alphabetic character, i.e., either lowercase character  or uppercase character .

**HTML AND XML tag Content Extractor**
TagContentExtractor extracts the tags 
