# Goal Sheet 07

**Problem GS07-01 (concession stand)**

Write a program that acts as the cash register of a concession stand (of a movie theater for example).  You need to have a minimum of popcorn, drinks that use an ```enum``` called sizes (like in the example code).  You also need to have at least two more items that the user can buy.  Decide the prices for things in such a way that the enumerated data is not the price.  Calculate the total and the tax.  The tax must be calculated in a separate function, where you return the tax only.  Output the price, tax, and total cost (price + tax) on separate labeled lines.  As an extension, you could make sure the user does not want more items or let the user choose how many items at what sizes. 

**Problem GS07-02 (Ellipse class)**

Write a class called ```Ellipse``` and a program that tests the class (probably a single program to test all the shape classes).  The class must have the required element (instance variables) of an ellipse (r1, r2).  (An ellipse has two radii.)  The class must also have a default constructor, methods to set the radii, methods to get each radius, a circumference method, and an area method.  The circumference and area methods must return the ellipse’s circumference and area.  Use the compiler’s built-in definition of PI in your code (```Math.PI```).  Notes: The area of an ellipse is Pi * r1 * r2.  The circumference of an ellipse is approximately 2 * Pi * sqrt (r1 * r2) according to Johannes Kepler.  (Note: ```Math.Sqrt()``` is a method that calculates the square root of what is in the parentheses.)

**Problem GS07-03 (Rectangle class)**

Write a class called ```Rectangle``` and a program that tests the class.  (Hint:  Use the same testing code, just add a new shape class to the project and associated code in Main().)  The class must have the required elements (instance variables) of a rectangle (length and width).  The class must also have a default constructor, a method(s) to set the instance variables, a method(s) to get the instance variables, a perimeter method, and an area method.  The perimeter and area methods must return the rectangle’s perimeter and area.

**Problem GS07-04 (Right Triangle class)**

Write a class called ```RightTriangle``` and a program that tests the class.  The class must have the required elements (instance variables) of a right triangle (base and height).  The class must also have a default constructor, a method(s) to set the instance variables, a method(s) to get the instance variables, a perimeter method, and an area method.  The perimeter and area methods must return the rectangle’s perimeter and area.

**Problem GS07-05 (Person class)**

Write a ```Person``` class.  This class must contain a person’s first, middle, and last names as well as the person’s age and phone number.  Make methods to change and get data.  Then create a program that uses the class.

**Problem GS07-06 (NPC class for RPG) ([RPG](https://github.com/MichaelTMiyoshi/CSharpWithMiyoshi/blob/main/Problems/RPG_Requirements.md) class)**

Write a Non-Player Character (```NPC```) class.  This class must contain the NPC’s data you already had (name, health points, damage points) plus some other things.  You need to have a race (enumerated using ```enum``` that you create – orc, elf, dwarf, human, or whatever you choose – and they do not need to be those that Tolkein created).  (You may have more, but not less data.)  Make methods to change and get data.  You must have at least two constructors, a default and one that takes all the data as arguments in the method call.  The default constructor must assign the elements randomly, while the constructor that has arguments, assigns the data appropriately.  Then complete the RPG.  You only need one NPC at this time, but eventually, you will create NPC objects grouped together in a ```List```.  Keep looking at the RPG requirements each time you add to it.
