# Balloon-Shooting-Game-using-8086

**ABSTRACT:**

The aim of this project is to create a fun and interactive gameplay of the original old generator 
pixel game of the balloon shooter game. The project will be intended for a single balloon 
shooter which shoots the balloon streaming up with the assistance of changing its position and 
there are some standard procedures which if not adhered to lead the user to lose the game. 
Information on the work in the software tool is illustrated, just as cutting edge information on 
constructing agents and working with library functions. From this project, we will get a better 
idea of how to work with the emu8086 emulator.

**PROPOSED WORK:**
It's a balloon shooting match-up where the player shoots a bolt to hit the inflatable and when 
the inflatable gets hit it signals and another balloon springs up and you get to shoot another 
arrow towards it.
Few labels and conditional jump statements to update logic and display everything:

**Main_loop:**
This is where the logical part of the game, handling user inputs and visually rendering 
happens.
**Inside_loop:**
 Checks collision detection
 Changes direction of player
 Hides arrow when it gets out of viewport
 Assuming that there isn't any balloon on viewport it fires another one
 
**Hit:**
 Plays sound (beep)
 
**Render_loon:**
 The balloon moves upwards
 
 **Render_arrow:**
 Moves arrow forwards
 
**Inside_loop2:**
 Render player on viewport
 
**Handling user input:**
 Check if any key is pressed
 
**UpKey:**
 Set player's direction to up
 
**DownKey:**
 Set player's direction to down
 
**SpaceKey:**
 If no arrow on screen fire new one

**IMPLEMENTATION:**

In this project, a balloon shooting game is built, where a balloon pops up from the bottom of 
the screen and keeps going up and a arrow from the left side is shot to hit the balloon, if it hits 
the balloon correctly then hits score will be increased by 1, if it misses the balloon, then miss 
score is decreased by 1.
Modules:
a) Shooter (User) module - User gets to control the position of the arrow, with upward and 
downward keys and can shoot the balloon using spacebar.
b) Balloon module - In this module a balloon pops up from the bottom and it controls the 
movement of the balloon, the upward motion.
c) Arrow module - In this module, the arrow moves horizontally on being shot by user.

**CONCLUSION:** 

In this project, I worked with EMU 8086 to build our project. We learnt about main basic 
concepts about assembly language in this process. Our project "Balloon Shooter with 
EMU8086" works efficiently. We can play this game balloon shooter on our desktop using this 
project. Based on how many balloons hit or miss by the user the hits and misses count is 
modified. The archer can move up, down and shoot using the keyboard controls. It’s a user-friendly, fun and interactive game play of the original old generator pixel game of the balloon shooter game.

