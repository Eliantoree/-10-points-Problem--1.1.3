# -10-points-Problem--1.1.3
Assignment #4 Introduction to C Programming – COP 3223

**Download Link:https://programming.engineering/product/assignment-4-introduction-to-c-programming-cop-3223/**


Description
5/5 – (5 votes)
Objectives

To learn how to use loops for repeated execution

To reinforce knowledge of If-Else statements for conditional execution

Introduction: Programmers for a Better Tomorrow

Programmers for a Better Tomorrow is an organization dedicated to helping charities, medical societies, and scholarship organizations manage various tasks so that they can focus on making the world a better place! They have asked you and your classmates to help them develop some new programs to benefit their organizations.

Problem: Scholarship Endowment Fund Part 2 (fund2.c)

One division of Programmers for a Better Tomorrow is their Scholarship Endowment Fund. They provide yearly scholarships to students who need a hand in amounts of 1000, 500, and 250 dollars.

The money for these scholarships comes from interest made on previous donations and investments. You will create a program to track the amount in the Fund as various donations and investments are made. Donations are a one-time increase to the amount. Investments are listed as one-time decreases with the return on investment (ROI) being calculated at a later time. ROI is not within the scope of this assignment.

To begin the program, ask the user for the starting balance of the fund.

Then, your program should allow the user the following options:

Make a donation

Make an investment

Print balance of fund

Quit

Option 1:

Prompt the user for their donation amount. Add this amount to the balance of the fund.

Option 2:

Prompt the user for their investment amount. In order to continue to provide scholarships, the fund cannot be allowed to fall below its initial amount. If an investment would bring the fund below that value, then simply print out “You cannot make an investment of that amount.” If the amount is valid, deduct it from the balance of the fund.

Option 3:

Print the current balance of the fund, the current total number of donations, and the current total number of investments.

2

After options 1, 2, and 3 prompt the user with the menu again.

Option 4:

Print the final balance of the fund, the final total number of donations, and the final total number of investments.

Do not prompt the user for any more information.

Input Specification

Menu responses are guaranteed to be integers greater than zero

Each monetary value will be a numerical value between -20,000 and 20,000.

Output Specification

Any monetary values should be formatted to two decimal places.

Output Sample

Below is a sample output of running the program. Note that this sample is NOT a comprehensive test. You should test your program with different data than is shown here based on the specifications given above.

In the sample run below, for clarity and ease of reading, the user input is given in italics while the program output is in bold. (Note: When you actually run your program no bold or italics should appear at all. These are simply used in this description for clarity’s sake.)

Sample Run #1

Welcome!

What is the initial balance of the fund?

15000

What would you like to do?

1 – Make a donation

2 – Make an investment

3 – Print balance of fund

4 – Quit

1

How much would you like to donate?

1000

What would you like to do?

1 – Make a donation

2 – Make an investment

3 – Print balance of fund

4 – Quit

2

How much would you like to invest?

2000

3

You cannot make an investment of that amount.

What would you like to do?

1 – Make a donation

2 – Make an investment

3 – Print balance of fund

4 – Quit

2

How much would you like to invest?

500

What would you like to do?

1 – Make a donation

2 – Make an investment

3 – Print balance of fund

4 – Quit

3

The current balance is $15500.00.

There have been 1 donations and 1 investments.

What would you like to do?

1 – Make a donation

2 – Make an investment

3 – Print balance of fund

4 – Quit

1

How much would you like to donate?

2000

What would you like to do?

1 – Make a donation

2 – Make an investment

3 – Print balance of fund

4 – Quit

1

How much would you like to donate?

2000

What would you like to do?

1 – Make a donation

2 – Make an investment

3 – Print balance of fund

4 – Quit

4

4

The final balance is $19500.00.

There were 3 donations and 1 investments.

Deliverables

One source files – fund2.c – is to be submitted over WebCourses.

Restrictions

Although you may use other compilers, your program must compile and run using Code::Blocks. Your program should include a header comment with the following information: your name, course number, section number, assignment title, and date. Also, make sure you include comments throughout your code describing the major steps in solving the problem.

Grading Details

Your programs will be graded upon the following criteria:

Your correctness

Your programming style and use of white space. Even if you have a plan and your program works perfectly, if your programming style is poor or your use of white space is poor, you could get 10% or 15% deducted from your grade.

Compatibility – You must submit C source files that can be compiled and executed in a standard C Development Environment. If your program does not compile, you will get a sizable deduction from your grade.
