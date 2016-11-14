# Multistorage-Box-with-menu
I want to create a Dialog script that will group and count each item in the contents and display them in a hover text (which can be turned off and on from the menu as well), and then create a button for each type of item that you can click and receive one of the items, the script will then recount and update the hover text.

Example:
I have a box that I am storing food for a roleplay system in.  The box contains 3 Apple Juice, 10 Grilled Fish and 5 Baked Potato.
The hover text above the box would read:
    Food Storage 
   Apple Juice  3
  Grilled Fish  10
   Baked Potato  5
 
 The "Food Storage" I believe can be pulled from the Description that you have in the item itself, the rest of it needs a script to Sort and count the items.  

When you click the box, you get a dialog menu.  On the first page of the menu will be 2 buttons; "Hover" (which will toggle the Hover text off and on) and "Take".
When you go to the "Take" menu, it will open a second menu that, in this example, would have 3 button; "Apple Juice", "Grilled Fish" and "Baked Potato".  If you click on "Apple Juice", it will give you one of the Apple Juices in the box and recount so that the hover text will now read:
    Food Storage
   Apple Juice  2  
  Grilled Fish  10   
   Baked Potato  5
   
 When you add other items to the box, the script will add those items to the menu buttons.
 I have certain components of this but have not been able to put it all together.
