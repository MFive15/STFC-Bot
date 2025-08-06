Created for CS4910A-C2 Senior Project at Baker College Online on June 30th. 
Author: Mark Beckerich
The Project is made in Java utilizing Java FX and OpenCV and was made in IntelliJ Ultimate using the student access code

**Idea and solution descriptions**
  The idea of the project was to create a program that interacted with other applications like a human did. Identify a UI element on the screen and either mouse click or type information via keyboard. 
  The solution I had was to utilize OpenCV to identify the UI elements and interact with them using java.awt.Robot.
  Named STFC Bot due to it being the test program, it would queue these interactions up one after another and save them as a routine. The routines could then be saved and loaded to allow users to switch between routines at will. 

**Images of project in action**
  Due to the nature of the interactions the program has with other programs, it looks like a human interacting with the program. However, per instructions, images will be included reguardless. 
  <img width="2562" height="1401" alt="image" src="https://github.com/user-attachments/assets/d707f85d-d44f-42cd-b0e1-13e0b38de180" />
  <img width="2562" height="1401" alt="image" src="https://github.com/user-attachments/assets/902fd48c-6b49-4d21-9eb3-4d281eeb573a" />
  
**Test Results**
  As can be seen in the two images above, the bot works acceptibly when attacking survey type hostiles. The real problems the program has is interacting with UI elements that have animations in their icon on the screen.
  For example, Mining Nodes. The icon for them rotates or pulsates slightly and the current implimentation of OpenCV struggles to find the specified item as that exact image is no longer present. 
  
