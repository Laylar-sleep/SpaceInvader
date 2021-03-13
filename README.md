# SpaceInvader
This is a Space Invader game written in Java. 

## Setup

### For the Windows environment:
Please make sure your computer has installed Java SE/Java SE Development Kit (JDK):
	http://www.oracle.com/technetwork/java/javase/downloads/index.html

You may check the JRE version in the computer by typing java -version" in Command Prompt (Windows) / Terminal (Unix-like).
	
Download and extract the “Release” folder we offered, open the “Space Invader” folder. Double click the “Space Invader.exe” or “Space Invader.jar”, both of them are runnable on Windows. If some warning windows pop up, just choose to allow it to continue.

### For the Mac environment:
Please make sure your computer has installed Java: 
https://www.java.com/download/help/mac_install.html
 
Download and extract the “Release” folder we offered, open the “Space Invader” folder. Double click the “Space Invader.jar”, only the jar file is runnable on Mac OS. 
	
If some warning windows pop up, open the “Security & Privacy” in “System Preferences”, then allow it to open this jar file.

## Game Rules
### Movement
Use “W”, “A”, “S”, “D” on the keyboard to control the plane to move up, down, left and right.

### Attack Control
Pursuit shot
The game system will drop down the “L” food block, move the plane to eat the food block, and the pursuit shot will be invoked when pressing key “L”.
Triple shot
The game system will drop down the “K” food block, move the plane to eat the food block, and the triple shot will be invoked when pressing key “K”.
Ultra shot
Move the plane to eat both the food block “L” and “K”, and the ultra shot will be invoked when pressing the key “U”.

## End Game
When the player loses all life, the pop-up window will show. Press “Enter” to continue and resume the game, press “Esc” to leave the game. When pressing “Esc”, choose the button in the java in-build window to end the game.
