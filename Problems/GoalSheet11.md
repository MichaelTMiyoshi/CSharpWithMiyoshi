# Goal Sheet 11

**Problem GS11-01 (count characters in a file)**

Write a program or modify problem GS04-03 to read the data of a text file and count the number of digits (0-9), tabs, spaces, newlines, and total characters (not just the letters but all the characters).  Make sure that the counting routine runs until the end of the file is reached.  One way to do this is read each line into a ```String```, then check each character in the ```String``` one by one (but you cannot count newlines in the String, you will need to count the number of times you read lines).  If you decide to modify the old code, copy the .cs file or the whole project.  Create a text file for testing the data.  (You can do so with any text editor, even your compiler.)  Make sure the text file has a known number of digits, tabs, spaces, and newlines (for testing).  The total number of characters should just be the number of times your code runs through the inner loop (if you read each line), not the number of letters (you do not need to count letters).

**Problem GS11-02 (delimited files)**

Create a comma-delimited file with an ```int```, a ```double```, a ```String``` (with or without spaces), and a ```char``` (in that order) on each of 10 rows.  Write a program to get in the data and then output it into a tab-delimited file.  You may use the data below as the data for your file:
```
1,2.3,abcdef,q
2,3.4,ghijklmn,r
3,4.5,opqrstu,s
4,5.6,vw,t
5,6.7,xyzpdq,u
6,7.8,abc123,v
7,8.9,qqqrrrsss,w
8,9.01,tea,x
9,0.12,taxation,y
10,11.12,present,z
```

**Problem GS11-03 (search a ```List```)**

Write a program that will read the data from the File I/O competency test [here](https://github.com/MichaelTMiyoshi/CSharpWithMiyoshi/tree/main/CompetencyTests/CompetencyTests#ct--file-io).  You will need to create a comma or tab delimited file with the data.  Then, read the data into a ```List``` of classes.   You want to search the data in the ```List``` for any of the specific data (i.e. name, age, etc.).  Make sure that you get all the data that matches.  For instance, if you search for age 15, you ought to output both lines of data that have age 15 (Tom and Yuki).  You can choose to output all the data in a line or let the user choose which columns (but at least the name and searched for data).  (By the way, this will give you practice for the competency test.)

**Problem GS11-04&05 (encrypt and decrypt files or periodic table)**

You may choose to do either of the following two problems.  [_**Note** to my students: Either one will count as two problems for your goal sheet.  Doing both will not count as extra credit._]

#### _Encrypt and Decrypt Files_

Your task is to:

Write a program to encrypt and decrypt the contents of a file.  Read the data in from one text file and write it out to a second text file, then decrypt the encrypted file to a third file.  Your encryption method should rotate the characters by a number given by the user.  Rotate the characters between the space and the tilde (represented by ASCII values from 32 to 127).  When you rotate the characters, you just add the number given by the user to each character in the file.  Since a character is merely an integer, it will change what the character is in the encrypted data file.  If the value ends up to be greater than 127, it rotates around back to 32 plus whatever is left of the added value. (For example, if the user gives a 1, 127 becomes 32 but if the user gives 3, 127 becomes 34.)  Merely subtract for decrypting.  Make sure that the user can give file names for reading and writing.  (In this program, it is best to use unsigned char for your data type as you encrypt and decrypt each char in the file.)  You can do this many different ways, including having the user choose the files and file names.

You can choose to encrypt spaces, but do not encrypt non-printable characters (including the newline).  Non-printable characters are between 0 and 31 (inclusive) on the ASCII table.  Since 32 is a space, you can decide whether you will encrypt spaces or not.  

The best programs let the user choose the names of the original file, the encrypted file, and the decrypted file.  They also let the user choose whether to encrypt or decrypt.  The files are just text files, so you can create the original files(s) inside or outside of the compiler (notepad or any text editor is good for that).  When you “rotate” the letters, you can either treat the letters as unsigned char or typecast them as ints.  You might get strange and unexpected results if you do not do this.

#### _Periodic Table_

Your task is to:

Write a program that will read in the elements of the periodic table from a file called chem.dat (this file is given).  The file holds the element symbol, element name, atomic number, and atomic weight all separated by commas (no spaces in the delimiting).  The data for each element is on a single line.  Create a structure to hold the data for each element.  The longest symbol is 3 characters and there are a few names with spaces.  Other than that all the data is only separated by commas, and each set of data is on its own line.  Create a vector of structures to hold the data after being read from the file.  Then create functions that will search for an element based on the symbol, name, or atomic number (as an extension, you can search for atomic weight, but it is not required).

You can do this with what you know, but here are some hints to help you out.

*	I already said it in the requirements, but use a struct for the elements.  Then, use a vector of those structs to hold all the data.  This is both a hint and a requirement.
*	Remember how to compare ```int```s and ```String```s.
*	Only read the data in one time.  You can do this in a function.  Just pass the class ```List``` or pass a ```List``` by reference.
*	Use loops to your best advantage.  And loop until the user decides to exit the program.
*	If you decide to search for atomic weight, do not search for equality with doubles.  When searching for the atomic weight (or doing any double comparisons), search for a range.  In other words, see if the atomic weight your user is looking for is between a range of numbers, not exactly any double value.  You get to decide what range you are looking between.  For instance, if your user wants to find an element with an atomic weight of 262.0, you might give answers between 261.0 and 263.0 or between 261.5 and 262.5.  (By the way, I chose 262.0 because 2 elements in the list have that atomic weight.  So if you choose to search by weight, you should be able to give multiple elements to your user.)

**Problem GS11-06 ([RPG](https://github.com/MichaelTMiyoshi/CSharpWithMiyoshi/blob/main/Problems/RPG_Requirements.md) state and high scores)**

Continue modifying your RPG (same project).  You should save the state of your game whenever your user decides to save or when you reach certain checkpoints.  The game state will be the status of your NPCs and of your user.  Choose how you will delimit your data.  Add an option at the beginning of the game to continue your campaign or start a new game.  If you have high scores for your game, have a file that lists the top ten scores.  Display these high scores at the beginning, the end, and/or at the user’s discretion.
