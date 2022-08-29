# Goal Sheet 03

**Problem GS03-01 ([RPG](https://github.com/MichaelTMiyoshi/CSharpWithMiyoshi/blob/master/Problems/RPG_Requirements.md) start)**

Continue to make your [RPG](https://github.com/MichaelTMiyoshi/CSharpWithMiyoshi/blob/master/Problems/RPG_Requirements.md).  (Keep adding to your original project.  Which also means you need to update your pseudocode and maintenance log.)  You will have a player who has health (or hit) points and damage points.  The health (hit) points are for how much health the player has and the damage points are for how much damage the player can inflict on a non-player character (NPC).

Below is some pseudocode to help you with your coding.  (The pseudocode is also the requirements for the program so far.)

```
	Output an introduction to the screen (already done)
	Create variables for hit points (your health), damage points (damage you give), and name
	Choose max and min for health and hit points and randomly give them to the user
	Address the user by name where appropriate
```

**Problem GS03-02 (Science Quiz using if)**

Write a program that gives a student a science quiz.  Get the name of the student (string) and address the student when asking each question.  Your quiz will have 3 multiple-choice questions.  Each question will have a minimum of four answers.  You must use if to determine whether your student gave the correct answer.  You must also automatically score the quiz.  Each correct answer gives the student four points and each incorrect answer subtracts one point.  (Yes, scores can be negative.)  Answers that are not one of the answers listed will neither add nor subtract from the score.  Make sure to output the user’s name and score at the end of the quiz.

**Problem GS03-03 (Computer Programming Quiz using switch)**

Write a program that gives a student a programming quiz.  Get the name of the student (string) and address the student when asking each question.  Your quiz will have 3 multiple-choice questions that cover topics from cmopuer programming (I/O, identifiers, operators, branching so far).  Each question will have a minimum of four answers.  You must use switch to determine whether your student gave the correct answer.  You must also automatically score the quiz.  Each correct answer gives the student one point and each incorrect answer subtracts 0.25 point.  (Yes, scores can be negative.)  Answers that are not one of the answers listed will neither add nor subtract from the score.  Make sure to output the user’s name and score at the end of the quiz.

**Problem GS03-04 (Choose your own adventure using if and switch)**

Write a short choose your own adventure story.  You must address the user by name and tell the story from the user’s perspective.  You must give the user at least 3 places where the story will branch.  The story will branch based on the user giving string input in at least two places and the story will branch based on int input in at least one input (minimum of three branching options).  Make sure that you have appropriate endings at all 9 (minimum) branch endings, which means at least two levels of nesting.  (The adventure does not need to be complicated.)  [_**Note**: This program is to demonstrate nesting.  You can have 2 levels with 3 possible choices at each level (giving 9 endings).  Or you can have 3 levels with 2 possible choices at each level (giving 8 endings), but at least one of your choices will have 3 possible choices (giving the required 9 endings)._]

**Problem GS03-05 (ACSII Art) ([pair programming](https://github.com/MichaelTMiyoshi/CSharpWithMiyoshi/blob/master/Problems/PairProgramming.md))**

Write a program that gives the user three choices of ASCII art.  Display the art (which can be animated) that the user chooses.  If you decide to use other people’s art, give them credit by citing the source for the user (not just in the comments).  As an extension, use strings to make and output your ASCII art.

**Problem GS03-06 (Non-looping Maze)**

Create a maze.  The maze looks like the picture below, but you need not have a graphical user interface (GUI).  Instead, you will give the user choices at each juncture.  There is a catch to this maze.  When you go through a door, that particular door (not every door in the room) shuts behind you and you cannot enter (or exit) it again.  This leads to many dead ends.

We have not yet covered loops, so you must use nested branching.  Be aware that there are three or more levels of nesting.  Also, make sure that the user is able to take every path to the very end (even if it is a dead end).

![picture](https://github.com/MichaelTMiyoshi/CSharpWithMiyoshi/tree/main/images)
