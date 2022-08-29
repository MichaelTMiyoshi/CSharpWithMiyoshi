# Goal Sheet 04

**Problem GS04-01 (looping quiz)**

Start with one of the two quizzes you made previously and make it so that each question must be answered correctly before going to the next question.  You can get rid of the scoring since you know that the user must answer correctly before going to the next question.  (You may also leave it in if you want to see the scores go negative while you are testing.)  Make sure that at the end, the user has the choice to run the program again.  (Reset the score if you score, but do not reset the name.)

**Problem GS04-02 (Convert to Roman Numerals) (may be [pair programming](https://github.com/MichaelTMiyoshi/CSharpWithMiyoshi/blob/master/Problems/PairProgramming.md))**

Write a program that converts numbers to Roman numerals.  Limit the user to numbers from 1 to 3999 (inclusive), and have an error checking loop to make sure that this limit is followed.  Put the converted Roman numeral into a string that you output when finished.  While the whole is not strictly a looping problem, make sure that you have a loop around the conversions so that the user can pick a different number to convert.  When you loop the program, make sure to reset both the number (int) and the Roman numeral (String).  [Hint: you can use modulus (to find each digit) and branching or loops or a combination to find the answer.  There are several good solutions to this problem.]

A couple notes on Roman numerals.  
* You only need to convert numbers from 1-3999 (inclusive).
* Roman numerals have up to only three repeating digits (i.e. III)

Decimal | Roman
------: | -----
1000 | M
900 | CM
500 | D
400 | CD
100 | C
90 | XC
50 | L
40 | XL
10 | X
9 | IX
5 | V
4 | IV
1 | I

Since Roman numerals only have a maximum of 3 repeating "digits," you need a way to show 4s and 9s.  These two numbers are shown with a larger number preceeded by the next higher "digit."  So 4 is IV instead of IIII, and 9 is IX instead of VIIII.  You can see this all the way through the Roman numeral system shown above through 1000.

**Problem GS04-03 (Count characters in a String)**

Write a program that gets user input into a string and then counts certain characters.  When you get input from the user, you need to make sure that you can get whitespace characters.  (The user will end the input by pressing a tilde (~) followed by the <ENTER> key.  Or you can try to use a different character like the <ESC> key.)  Once the input is obtained, the application will count the number of spaces, tabs, newlines, and numbers (digits).  You do not need to determine the amount of each digit, just the total number of digits in the input.  Output the data in a readable format.  [Hint: remember that this is a looping problem and that there is example code to get you started.]

**Problem GS04-04 (ASCII art and animation) ([pair programming](https://github.com/MichaelTMiyoshi/CSharpWithMiyoshi/blob/master/Problems/PairProgramming.md))**

Write a program that gives the user 3 choices of ASCII art and animation (you need to have at least one animation).  The user will choose between the three animations or exiting.  Only exit when the user chooses.  Give an error message when the user chooses something not on the menu.

**Problem GS04-05 (looping maze)**

Create a new maze.  The maze will have the same exact pattern as that from GS03-05, but the doors do not close behind the user.  Instead of using all the code from the old program and trying to modify it, it is easier to start the code from scratch with an overarching loop and branching for each room.

![picture](https://github.com/MichaelTMiyoshi/CSharpWithMiyoshi/blob/master/images/CSharpMaze.png)

**Problem GS04-06 ([RPG](https://github.com/MichaelTMiyoshi/CPPwithMiyoshi/blob/master/Problems/RPG_Requirements.md)  game loop and main menu)**

Continue making your RPG (using the same project).  [_**Note**: If you created your own repo for this project, you ought to consider making branches off of your master.  That way you always have your working code in your master.  Yes, all of your commits ought to have working code, but there are a few places down the road where you might want to go back in time and continue again.  This is where branching might be a great option.  You can look at the different branches in my [RPGDemo repo](https://github.com/MichaelTMiyoshi/RPGDemo) to get a simple idea of what branching might look like._]

Create a main menu (inside a loop) where you can choose to equip your character (and other things later) or enter the game.

Equip the user with at least one item.  You may choose to let the user have up to three items.  However many items you choose to let the user have, there must be at least three choices for each item.  We do not yet know how to store these items, but you should have a variable that represents how many items and variables to tell which items are chosen.

Also put in a loop that will go around the rooms / locations you will be making.  (This is the main game loop and will sit outside the main menu loop.)  These locations are part of a bigger “dungeon.”  You will be creating a dungeon of at least 25 rooms.  While you are not going to make the rooms yet, you need to have a loop around a movement system that lets you move from room to room.  This will consist of some sort of branching, which will not have much in each of the branches yet.
