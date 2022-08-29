# Competency Tests

I have students take what I call competency tests.  They write code by hand.  I do not keep the tests a secret.  Instead, they are in my book and the students have access to them from the time they open said book.

One of the reasons I decided to have students write code by hand is because of the AP Computer Science test.  Since those students needed to write code without the use of a compiler, I figured my intro students ought to do that too.  I figured they needed to be their own compilers.  An industry professional told me later that coding by hand was also beneficial because prospective employees needed to write code during interviews.  They coded by hand on whiteboards.  So I have continued to require my students to write code by hand.

I am including all the competency tests in one place.  The directions I give to my students are below followed by the competency tests themselves.  By the way, I tell my students that they only have 15-20 minutes to finish (see the instructions), but I rarely enforce that.

## Introduction to Competency Tests and Instructions

Competency tests are writing code by hand.  Yes, you need to use pencil (or pen) and paper.  No compiler except your own brain.  They ought to take each person about 15-20 minutes to finish.  They are used to test your ability to think through code without the help of a compiler.  And they test specific concepts.  You only need to write the code snippets necessary to complete the tasks.  You do not need to put in int main() unless specifically told to do so in the instructions.

<hr>

### CT – Variables, Constants, and Division

Demonstrate your competence in using the math operators by creating a short code segment for **each** of the following scenarios, and give example numbers and answers:
1. You have three ints called i1, i2, and i3 and you want to determine the remainders of the division of each of the numbers by 7.  Give three example numbers (at least one number must be less than 7) and the answers of all 3 remainders (modulus operation).  (Put the answers in comments after the divisions.)
1. You have three ints called i1, i2, and i3 and you want to determine the value of each divided by the other.  Give three example numbers and the answers of all 6 divisions.  (Put the answers in comments after the divisions.)
1. You have an int called i1 and a float called f1 and you want to determine what each divided by the other will be.  You want to make sure that when you divide by the float, you get a float answer and when you divide by the int, you get an int answer.  Give two example numbers and answers to both divisions.  Declare appropriate variables in which to store the answers.  (Put the answers in comments after the divisions.)  Make sure that the float has a decimal value not equal to zero (i.e. 3.2 not 3.0).
1. You have an int called i1 and a float called f1 and you want to determine what each divided by the other will be.  But you want to make sure that when you divide by the float, you get an int answer and when you divide by the int, you get a float answer.  Give two example numbers and answers to both divisions.  Declare appropriate variables in which to store the answers.  (Put the answers in comments after the divisions.)  Make sure that the float has a decimal value not equal to zero (i.e. 3.2 not 3.0).

<hr>

### CT – Branching

<ol>
<li>Demonstrate your competence in using the if-structure by creating an if-structure for <b>one</b> of the following scenarios:
<ol type="A">
<li>You have three floats called f1, f2, and f3 and want to find out which has the middle value.  Expected outputs: “f1 is the middle value”, “f2 is the middle value”, “f3 is the middle value”, “there is no middle value” or you can output the number instead of saying which variable is the middle</li>
<li>You have three ints called i1, i2, and i3 and you want to see whether all, some, or none of the values is positive.  Expected outputs: “All the values are positive”, “Some of the values are positive”, “None of the values are positive”</li>
<li>You have three bools called b1, b2, and b3.  You need to know what values of b1, b2, and b3 make the statements (b1 AND b2 OR b3) and (b1 OR b2 AND b3) equivalent (if any).</li>
</ol></li>
<li>Demonstrate your competence in using the switch-structure by creating a switch-structure for **one** of the following scenarios:
<ol type="A">
<li>You have an int input called iAns that can have 5 values with correct results.  Those values are 3, 5, 11, 13, and 17.  Output different responses for each correct value and give a chiding remark when an invalid response (or response other than the 5 correct responses) is given.</li>
<li>You have a char input called cAns that can have 5 values with correct results.  Those values are A, b, Q, T, and x.  Output different responses for each correct value and give a chiding remark when an invalid response (or response other than the 5 correct responses) is given.</li>
<li>You have a bool input called bAns.  Give appropriate responses for all possible bAns.</li></li>
</ol>
</ol>

<hr>

### CT – Looping

When you do the looping competency test, make sure to do one for, one while, and one do-while loop.  You must do all A, all B, or all C problems.  Do not mix and match.  In other words, do 1A, 2A, 3A or 1B, 2B, 3B or 1C, 2C, 3C.  Those are your three choices of problems.

1.  Demonstrate your competence in using the for loop by creating a for loop for one of the following scenarios:

A.	Output the numbers from 15 through 125 (inclusive) skipping 25, 30, and 35.  Use only one loop.  Put tabs between the numbers and only put 5 numbers on each line.

Expected output (first four lines):
```
15	16	17	18	19
20	21	22	23	24
26	27	28	29	31
32	33	34	36	37
```

B.	Count (and output) by a given increment (iIncrement) from a given start point (iStart) to a given end point (iEnd).

C.	Suppose that an empty for loop that counts to 1000 will give you a delay of 1/100th of a second.  Use nested for loops (only two levels of nesting) to delay 0.5 seconds.

2.  Demonstrate your competence in using the while loop by creating a while loop for one of the following scenarios:

A.	Create an error-checking loop that makes sure the user gives a positive input into an int called iNum.

B.	Output the numbers from 1 through 100 (inclusive) skipping 30, 40, and 50.  Use only one loop.  Put tabs between the numbers and only put 6 numbers on each line.

Expected output (first line, then three other lines):
```
1	2	3	4	5	6
…
19	20	21	22	23	24
25	26	27	38	29	31
32	33	34	35	36	37
```

C.	Count (and output) by a given increment (iIncrement) from a given start point (iStart) to a given end point (iEnd).

3.  Demonstrate your competence in using the do-while loop by creating a do-while loop for one of the following scenarios:

A.	Count (and output) by a given increment (iIncrement) from a given start point (iStart) to a given end point (iEnd).

B.	Create an error-checking loop that makes sure the user gives an input between 2.5 and 3.5 (inclusive) into a float called fNum.

C.	Output the numbers from 101 through 300 (inclusive) skipping 135, 140, and 145.  Use only one loop.  Put tabs between the numbers and only put 7 numbers on each line.

Expected output (first line, then three other lines):
```
101	102	103	104	105	106	107
…
122	123	124	125	126	127	128
129	130	131	132	133	134	136
137	138	139	141	142	143	144
```

<hr>

### CT – Strings

Demonstrate your competence in using strings for each of the following scenarios:
1.	Create a String called sFName and initialize it to your first name.  Output the 3rd character in the String.  Then change the String to hold the name, Rumplestiltskin.

Expected outcome:
```
First name: Annabelle		Output: n
First name: Jo			Output: error
```

2.	Create a String called sMName and initialize it to your middle name.  Output the first 5 characters using a loop and subscripts.  Make sure the loop does not try to access characters beyond the last char in your middle name.  (You will need a compound Boolean expression whether or not your name is less than 5 chars to make your answer more general, and to get all four points.  Loss of 1 point if a name shorter than 5 characters makes your loop give an out of bounds error.)  If you have no middle name, initialize the variable to “NoMiddleName” (with or without spaces).

Expected outcome:
```
Middle name: NoMiddleName		Output: NoMid
Middle name: Cruz			Output: Cruz
Middle name: Richard			Output: Richa
```

3.	Create a String called sLName and initialize it to your last name.  Output the name in reverse order.  (Without using a method from the String class or any other function that you do not write.)

<hr>

### CT – Functions

Demonstrate your competence in using functions by creating a function (or function prototype) for **each** of the following scenarios:

1.	Create a function prototype for a function that will not return a value and takes 3 int arguments.

2.	Create a function that takes in two int values and returns the LOWER value.

Expected outcomes: 

Inputs | Output
-----: | -----:
3, 5   | 3
-7, 2  | -7
9, 9   | 9

3.	Create a function that takes one String argument and returns a String which has the original String except that the first letter is capitalized and all the letters after spaces are also capitilized.  Use the following function signature: 

```
static String Capitalize(string original)
```

Expected outcomes: 

Original string | Capitalized string
----- | -----
the rain in spain | The Rain In Spain
what is your quest? | What Is Your Quest?
my name is INIGO! | My Name Is INIGO!

4.	(Extra Credit)  Create a function that gets a double value and the number of decimal places (int) and returns a rounded value to that many decimal places.  (Remember that when rounding, 5 or more goes up, less than 5 goes down.  Do not use the rounding, ceiling, floor, or other functions.)

Expected outcomes: 

Inputs | Output
----------: | -----:
3.14159, 1  | 3.1
-7.89012, 3 | -7.890
1.234567, 3 | 1.235

<hr>

### CT – enums

Demonstrate your competence in using enum and struct by using and/or creating one for **each** of the following scenarios:

1.	Create enumerated sizes using the following definitions:
```
a.	each = 1
b.	dozen = 12
c.	gross = 144
```
Then use those enumerated sizes with two different variables called boxes and envelopes.

<hr>

### CT – Classes

Demonstrate your competence in using classes for **both** of the following scenarios:
1.	Create a square class.  It must include the proper instance variables and methods to set and get those values.  It must also include a default constructor and methods that return the perimeter and area of the square.
2.	Create a person class.  It must include instance variables for name and age.  It must also include a default constructor and methods to set and get the values of those instance variables.

<hr>

### CT – Lists

Demonstrate your competence in using Lists (and loops) for each of the following scenarios:

1.	Declare an integer List that will hold 100 integers.  Initialize that List (using a loop) with the numbers 1 through 100.  (_**Note** to my students: If you choose to initialize the vector without using a loop, the best score you can receive is 2.5/4._)
1.	Declare a two-dimensional integer List.  Use a nested loop to initialize the List to have the following values:  (_**Note** to my students: If you choose to initialize the two-dimensional vector without using nested loops, the best score you can receive is 2.5/4._)
```
1	2	3	4	5
2	4	6	8	10
3	6	9	12	15
4	8	12	16	20
5	10	15	20	25
```

<hr>

### CT – File I/O
11306	Use streams to manage input and output including files

Demonstrate your competence in using data files by writing code for the following scenario:
1.	You have data that you want to store and then retrieve.  You must decide what type of delimiting you would like to use (use comma- or tab-delimiting) to store the following data (The first row is not part of the data, just labels):
```
Name		Age	Height (in)	Weight (lb)	Phone #
Loretta		18	66		130		425.844.1231
Mike		16	68		145		425.844.1232
Charles		17	72		160		425.844.1233
Gracie		15	74		205		425.844.1234
Anna		19	73		170		425.844.1235
George		15	62		115		425.844.1236
```
[_**Note**: If you copy the above data, it has extra tabs so that it looks correct in this file._]

a.	Write code to open a new file for writing.  The file name will be names.txt.  Use a loop to get data from the user (who would then input the above data).  End the loop by asking whether the user is done entering data.  Do not just use Strings for each piece of data.  Use the appropriate data types (name, phone: string; age, height, weight: int).  Tell what type of delimiting you are using (can be a comment in the written code) and output the data to the file accordingly.

b.	Write out what **all** the above data would look like in your file.  Show tabs as \t or commas as commas (,).  Do not put in extra spaces.

c.	Write code that will get the data from the data file (you may hardcode the filename in your code) and output it to the screen.  Get the username and phone number as strings and the other data as unsigned integers.  Use a loop that does not assume there are only 6 pieces of data.

<hr>

That is it for my intro competency tests.  Like I said, my students have access to these from the first time they open my book, so it is no surprise that I would have them available on the internet for all to see.

To those taking the competency tests, have fun being your own compiler and your own printer.
