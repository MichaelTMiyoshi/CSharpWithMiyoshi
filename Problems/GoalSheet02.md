# Goal Sheet 02

**Problem GS02-01 (output 1-10 with one variable)**

Write a program that uses only one int variable to output to the screen the numbers one through ten.  Make sure to put each number on its own line.  Do not just output the numbers (using no variables).  Output the one variable.  As an extension, make sure the ones digits all line up on the right side without using a space.  (Hint: look up String.Format() and give a specific number of digits to output.  You can also right justify the output, but you need to still give a specific number of digits to output.)

**Problem GS02-02 (A little division)**

Start with the example code given and create your own math problems.  Make sure to output all your results to the screen.  Assign the variables appropriately (do not try to put fractional data into int variables).  You need to have an int and double problem for addition, subtraction, and multiplication.  (6 problems)  For division, you need to have int, double, and two mixed.  For the mixed, divide an int by a double and put it into an int variable (use typecasting to ensure you do int division) and divide a double by an int and put it into a double variable (use typecasting to ensure you do floating point division).  Also, make sure that you find the remainders (use modulus) for all your integer divisions (including the mixed one that goes into an int variable).  (6 problems)  In total, you should have 12 math problems with their 12 outputs.

**Problem GS02-03 (dice and other random numbers)**

Generate random numbers.  You want to simulate a 6-sided die (numbers 1-6), a 12-sided die.  Also generate a random double between 0.0 and 5.0 (inclusive), and a random character of UPPER CASE letters (A-Z, inclusive).  Your output should be labeled and have only one random output per line.  (You should have 4 lines of output.)

**Problem GS02-04 (More random stuff) ([pair programming](https://github.com/MichaelTMiyoshi/CPPwithMiyoshi/blob/master/Problems/PairProgramming.md))**

Write a program that lets the user choose the limits of random numbers and characters.  First, find a random double between 0.0 and 1.0 (exclusive of 1.0).  Then, have the user choose upper and lower values for a random int, a random double, and a random character.  You decide whether the maximum values will be included or excluded in the range.  Label the output and output each random item on a separate line.

**Problem GS02-05 (Bus Charter)**

You are in charge of chartering busses for tour groups.  You need to make sure that each bus is filled to capacity before you hire vans.  Each bus holds 60 people.  Get the number of people going on the tour from the user and then output the number of busses and the number of people left over who will need to ride in vans.  (Use modulus to your best advantage.)  As an extension, calculate the number of vans if the vans can take 7 people.  Give an introduction and ask for the user’s name (put it in a String).  Make sure to address the user when you ask for the input.  Get the appropriate input from the user.  Make sure to address the user when you come up with the answer and label the output appropriately.

**Problem GS02-06 (Averages)**

Make an app that calculates a user’s average speed (miles per hour) and average fuel consumption (miles per gallon).  Make sure to address the user when you ask for the input.  Get the appropriate input from the user (miles traveled, hours traveled, gallons used).  Make sure to address the user when you come up with the answer and label the output appropriately.  Output the average speed to the nearest mile per hour (mph) and the average fuel consumption to the nearest tenth of a mile per gallon (mpg).  (Hint: use double data and Console.WriteLine() using {0:0.0} as was shown in earlier example code but which used 3 decimal places instead.)
