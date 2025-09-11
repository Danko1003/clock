Project: clock-display
Authors: David Barnes and Michael Kölling

This project is part of the material for the book

   Objects First with Java - A Practical Introduction using BlueJ
   Seventh edition
   David J. Barnes and Michael Kölling

It is discussed in chapter 3.

To use this project, create an instance of class ClockDisplay. Then inspect this 
instance and leave the object inspector window open. With the inspector window open, 
call the object's methods, such as timeTick and setTime. Watch the 
"displayString" in the inspector.

The displayString field simulates the actual clock display device. Were this 
program running in a real clock, it would change the real, physical display 
hardware instead of this string. The timeTick method would be triggered once 
every minute by some timer hardware.

Everything else could be pretty much the same.


Note: This project does not implement adequate handling of errors.


21-It is set at 00:00 because it has no initial time being set so it just resorts to being set to 0, until we set a new value.



22-x



23-60 times



24-x



25-Rectangle window;
   window = new Rectangle(100,80); 



26-The second contructor for clock display creates a new display for hours and for minutes.



27-Because the settime methodalready calls the updatedisplay method.



28-public void print(String filename, boolean doubleSided);
    p1.print("hello/file", true);
    p1.getStatus(4)



29- Square, Triangle, Circle



30- roof.changeSize(60, 180);
    roof.moveHorizontal(20);
    roof.moveVertical(-60);
    roof.makeVisible();



31-Yes, drawn is = true



32-2 remains



33-it gives a negative remain when it is a negative value.



34- -4, -3, -2, -1, 0 ,1 ,2 ,3 ,4



35- the range scales from [-m to m]



36-



37-



38-



39-



40-



41-



42-



43-



44-



45-



46-



47-



48-



49-



50-



51-



52-



53-



54-



55-



56-



57-



58-


