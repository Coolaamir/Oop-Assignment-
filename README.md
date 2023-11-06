# Oop-Assignment-

1ST PROGRAM
This is a simple Java program called "calc" that functions as a basic calculator. Here's what the program does in simpler terms:

It starts by importing the java.util.Scanner class to read user input.
The main method is the entry point of the program.
It uses a while loop to keep the calculator running until the user decides to exit.
Inside the loop, it displays a welcome message and asks the user to enter a mathematical expression (e.g., "5 + 10").
It checks if the input is a valid expression using the isValidExpression method. A valid expression consists of three parts: a number, an operator (+, -, *, or /), and another number.
If the expression is valid, it splits the input into its components and performs the calculation using the performCalculation method. It handles basic operations like addition, subtraction, multiplication, and division. If division by zero is attempted, it throws an exception.
If the expression is not valid, it throws an exception and asks the user to enter a valid expression.
After calculation, it displays the result and asks if the user wants to continue. If the user doesn't enter 'Y', the program thanks the user and exits.
It handles exceptions like invalid input, division by zero, and invalid operators by displaying appropriate error messages.
In summary, this program is a simple command-line calculator that allows users to perform basic arithmetic operations repeatedly until they choose to exit. It checks for valid input and handles errors gracefully.




2ND PROGRAM

This program is written in Java and is designed to process data about students, specifically their names and scores. Here's a simple explanation of what the program does:

It starts by defining a class named "Strings."

Inside the class, there is a "main" method, which is the entry point of the program.

The program begins with a string named "studentData," which contains information about students and their scores in the form of "Name:Score" pairs, separated by commas and spaces.

It splits the "studentData" string into an array of individual student records based on the comma and space using the split method.

The program creates two arrays to store student names and their scores.

It then loops through each student record, splits it into name and score, and stores them in the respective arrays.

Several variables are initialized to calculate the total score, highest score, lowest score, and the names of the top and bottom scorers.

The program calculates the total score, finds the highest and lowest scores, and keeps track of the names of the students with the highest and lowest scores.

After processing all the data, it calculates the average score by dividing the total score by the number of students.

Finally, it displays the results, including the total number of students, the average marks of all students, the student with the highest score, and the student with the lowest score using the System.out.println statements.

In summary, this program takes a string of student data, processes it to find statistics like average score, highest scorer, and lowest scorer, and then prints out the results.


