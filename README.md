# Elementary Arithmetic

## Objectives
1. Introduction to MASM assembly language
2. Defining variables (integer and string)
3. Using library procedures for I/O
4. Integer arithmetic

## Description
Write a MASM program to perform the tasks listed below. Test your program to ensure that it functions correctly.
1. Display your name and program title on the output screen.
2. Display instructions for the user.
3. Prompt the user to enter two numbers.
4. Calculate the sum, difference, product, (integer) quotient and remainder of the numbers.
5. Display a terminating message.

## Requirements
1. The main procedure must be divided into sections:
    -  introduction
    - get the data
   - calculate the required values
   - display the results
   - say goodbye
2. The results of calculations must be stored in named variables before being displayed.
3. The program must be fully documented. This includes a complete header block for identification, description, etc., and a comment outline to explain each section of code.
4. Submit your text code file (.asm) to Canvas by the due date.

## Notes
1. A program shell (template) is available on the course website. See the Week 1 Basics page in Modules.
2. You are not required to handle negative input or negative results.
3. You have a limited number of late days. Try not to use these on the first program.
4. To create, assemble, run, debug, and modify your program, follow the setup instructions available within Canvas on the Syllabus –> Tools page.
5. Find the assembly language instruction syntax in the textbook.
6. Documentation for the Irvine library procedures is provided in the textbook.

Example Program Operation
```
Elementary Arithmetic by Wile E. Coyote
Enter 2 numbers, and I'll show you the sum, difference, product, quotient, and remainder.
First number: 37
Second number: 5
37 + 5 = 42
37 - 5 = 32
37 x 5 = 185
37 / 5 = 7 remainder 2
Impressed? Bye!
```

## Extra Credit Options (original definition must be fulfilled)
1. (1 pt) Validate the second number to be less than the first.
2. (1 pt) Display the square of each number. Recall that the square of a number is obtained by mutiplying a number by itself. For example:

```
Square of 37 = 1369
Square of 5 = 25
```

To ensure you receive credit for any extra credit options you did, you must add one print statement to your program output PER EXTRA CREDIT which describes the extra credit you chose to work on. You will not receive extra credit points unless you do this. The statement must be formatted as follows...

```
--Program Intro--
**EC: DESCRIPTION
--Program prompts, etc—
For example, for extra credit option #1:
Elementary Arithmetic by Wile E. Coyote
**EC: Program verifies second number less than first.
Enter 2 numbers, and I'll show you the sum, difference, product, quotient, and remainder.
First number: 7
Second number: 9
The second number must be less than the first!
Impressed? Bye!
```
