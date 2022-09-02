# Goal Sheet 06

**Problem GS06-01 (fraction reducer)**

Write a program that reduces fractions using a function.  The function will return an int and have two int arguments.  The returned int will be the greatest common factor (GCF).  The function signature and the GCF function from the example in the chapter may be used as a starting point.

**Problem GS06-02 (square root reducer) ([pair programming](https://github.com/MichaelTMiyoshi/CSharpWithMiyoshi/blob/main/Problems/PairProgramming.md))**

Write a program that simplifies integer square roots.  (You probably never thought you would need to do that again after you finished the math class where you did it.)  You do this by determining if the user’s input number has any square factors.  You then return the factor (not squared) from your function.  For instance, if you pass the number 72 to your reducer, it has the square factor 36.  Your function would return the factor 6 (6 * 6 = 36).  In your calling function (presumably main), you would output that the reduced number is 6√2.  You do not need to use the square root symbol.  You can instead say the reduced number is 6 times the square root of 2.  Or something to that effect.  If you would like to use the square root symbol (√), its ASCII value is 251 (decimal).  Your function signature should look like the following:
```
static int RootReducer(int number)
```
[_**Note**: The square root reducer would be a great place to try and return two values.  Note that these two values would both be ints._]

**Problem GS06-03 (fortune cookie)**

Write a program that is passed a number and gives the user a fortune.  You will decide which fortune (of ten possible) based on the number that is passed to the function.  Then, the function will pass the fortune back to the calling function.  Output the fortune in the calling function.  You must loop the program (in Main()) so that the user can keep getting fortunes until opting to quit.  (As an extension, use a random number to determine the number you pass to the function instead of getting the number from the user.)  Your function signature should look like the following:
```
static String FortuneCookie(int num)
```

**Problem GS06-04 (function maze)**

Write a program that uses functions for the rooms (minimum of 12) of a maze.  The maze should have beginning and ending points.  Between are rooms that can be traversed via your own system.  The best way to do the maze is not to call rooms from other rooms but to have a loop in the Main() function and call the rooms based on a room variable (like the example with three rooms).  Your maze must have a minimum of 12 rooms and the user may travel to each one.  You may have one path or multiple paths that get you to the exit.  You might even put a story to it, although that is really part of the major program.

**Problem GS06-05 (word reverser)**

Write a program that reverses the characters in a String.  While there is a function that does this, using it does not count as writing a function.  Your function should pass one String to it and return one String.  (See signature below.)  Your function gets passed the original String and returns the reversed String.  Note that you will output the original and reversed strings in the calling function.  Your function signature should look like the following:
```
static String Reverser(String original)
```

**Problem GS06-06 ([RPG](https://github.com/MichaelTMiyoshi/CSharpWithMiyoshi/blob/main/Problems/RPG_Requirements.md) functions)**

Create functions for movement, rooms, fighting and such.  [_**Note** to my students: You will be concluding your major project in the first part of the second semester._]
