# Goal Sheet 10

**Problem GS10-01 (multiply List values by scalar)**

Write a program that declares an integer ```List``` of 50 elements.  (Use a loop to populate the ```List``` with consecutive or random numbers.)  Then use the fact that scalar multiplication of matrices (Lists) is simply the multiplication of each element in the matrix by the given scalar.  Let the user input a number (scalar) that will be used to multiply the matrix (```List```).  Then multiply the matrix by that number.  Output the new ```List``` values to the screen.

**Problem GS10-02 (more fortunes)**

Write a program or modify problem GS06-03 to have 20 different fortunes stored in a ```List``` of strings.  Output a fortune based on a random number which will be the index of the ```List```.  Continue giving random fortunes until the user chooses to exit.

**Problem GS10-03 (sine and cosine lookup tables)**

Lists can be used as lookup tables for values that are often calculated in a program.  By using lookup tables instead of always calculating the answer, you can often make programs run faster because the tables hold the data that takes up processor time to calculate.  Create two lookup tables (Lists) – one for the sine and one for the cosine values.  Each lookup table should hold the sine or cosine value for each degree from 0 to 359.  (You may create one 2D lookup table if you would like.)  When calculating the sine or cosine value, you must make sure that the argument of the function (```sin()```, ```cos()```) is in radians.  Remember that 180° equal &pi; radians.  Use ```Math.PI``` as your constant for &pi;.

**Problem GS10-04 (multiplication table flash cards)**

Write a program to hold the integers of the multiplication table.  The table will hold the answers for the 12x12 table.  That is to say that the numbers will be the answers for all the simple multiplications from 1 to 12 (do not include 0).  (Remember 1x1=1, 1x2=2, 1x3=3, etc.)  Note that when storing the numbers, the multiplications are not the same as the indices.  They are the multiplications of the index + 1.  So calculate accordingly.  The 2D ```List``` should only be 12 by 12.  Also make an interface where you quiz the user with flash cards.  Output the random multiplication (3 x 4, for instance), get user input, then check the user input against the answer in the table.  Keep giving random multiplications until the user tells you to quit (use a loop).  Alternately, you can output the multiplication, wait some amount of time, then flash the answer for a certain amount of time before moving on (or wait for the user to press a key).  Make the multiplications random.  (As an extension, give the user a choice of looking at the whole table before getting quizzed with flash cards.  If you want to get really fancy, you can actually make the UI look like flash cards.)

**Problem GS10-05a (matrix multiplication)**

(You may do the card shuffler instead of doing the matrix multiplication problem.  You do not need to do both.)
The mathematical concept of matrix multiplication is a useful tool in 2-D and 3-D graphics.  Write a program that will find the dot product of two 3x3 matrices.  See below for the formulas used to take the dot product of two 3x3 matrices:

Dot Product of two 3x3 matrices.

Let:
```
	┌		┐
	│ a00  a01  a02	│
A = 	│ a10  a11  a12	│
	│ a20  a21  a22	│
	└		┘
	┌		┐
	│ b00  b01  b02	│
B = 	│ b10  b11  b12	│
	│ b20  b21  b22	│
	└		┘	
	┌		┐
	│ c00  c01  c02	│
C = 	│ c10  c11  c12	│
	│ c20  c21  c22	│
	└		┘
```
The subscripts represent the row and column of the item in the matrices.  The first row of matrix A is thus a00  a01  a02 while the first column of A is a00  a10  a20.  When you take the dot product of two matrices, you multiply the first element of the row by the first element of the column and add it to the product of the second element of the row multiplied by the second element of the column and add it to the product of the third element of the row multiplied by the third element of the column.  So when we multiply matrices C = A*B, and the first element of C is c00 = a00*b00 + a01*b10 + a02*b20.  The complete dot product array is thus:
```
	┌											┐
	│ a00*b00+a01*b10+a02*b20     a00*b01+a01*b11+a02*b21      a00*b02+a01*b12+a02*b22	│
C = 	│ a10*b00+a11*b10+a12*b20     a10*b01+a11*b11+a12*b21      a10*b02+a11*b12+a12*b22	│
	│ a20*b00+a21*b10+a22*b20     a20*b01+a21*b11+a22*b21      a20*b02+a21*b12+a22*b22	│
	└											┘
```
Remember that the matrix dot product is not commutative (A*B != B*A).

(If you pay attention to the subscripts, you should be able to see an easy way to do the dot product for multiplying 3x3 ```List``` using loops.)

**Problem GS10-05b (card shuffler and dealer)**

(You may do the matrix multiplication problem instead of doing the card shuffler.  You do not need to do both.)

Create a class for a playing card.  The class will have two enum datatypes.  One for the suits and one for the designation.  [_**Note**: There is a hierarchy of suits.  They are ranked from lowest to highest: clubs, diamonds, hearts, spades._]  The class will also have face values for each card from 1 to 13.  So your class will have three instance variables (or properties), suit, designation, and face value.  You may also have a string for the name of the card, which will tell you its designation and suit (i.e. Jack of Diamonds).

Create a ```List``` and populate it with cards.  I would suggest populating it with cards in order.  Then, you will need to create a function that shuffles the cards.  That function will give you a random number between 0 and 51 (inclusive), which will be used as the index for a card in the List to be switched with the last card in the deck.  Then, you exclude the last card in the deck (essentially making the unshuffled deck smaller each iteration) and do the same process until you have swapped all the cards.  This is a well-known shuffling algorithm (which I forget the name of right now).

Once you have created the shuffling function, you will deal the deck into four hands.  These hands will be held in a two-dimensional ```List```.  The first dimension will be the number of hands (4) and the second dimension will be the number of cards each hand holds (13).  Make sure to deal the cards into the hands one card at a time from the deck.  When you are finished dealing the cards, output each hand to the screen.  Your deck may be full or empty when you are finished, but make sure that you output the deck in the shuffled order as well as outputting each hand.  Label your output appropriately.  [_**Note**: You may label each hand in the output as North, South, East, and West, the traditional positions of bridge hands._]


**Problem GS10-06 ([RPG](https://github.com/MichaelTMiyoshi/CSharpWithMiyoshi/blob/main/Problems/RPG_Requirements.md) vector of NPCs))**

Continue writing your RPG, but make it more efficient by putting the NPCs into a ```List```.  Which means that you will be creating a ```List``` of classes.  This will modify your code quite a bit so you will want to make sure you are keeping up with your version control.
