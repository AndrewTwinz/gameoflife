# Game Of Life
Python Kivy implementation of Conway’s Game of Life.

### Dependencies
* Python 3.5.5
* kivy 1.10.1

It should also work with python 3.x and others kivy versions. 

### Launch the application
Type `$python gameoflife/main.py` on console.

### Try more patterns
From the application settings, by default, it's possibile to try only 5 patterns.
If you want to explore them all, just add a new file name from the 'patterns' folder
 on the 'layout.kv' file, editing the line 175: <br>
 `values: ["1beacon", "glider", "ghostherschel", "4boats", "star"]`
 
 ### Links
 Original article: <br>
 http://ddi.cs.uni-potsdam.de/HyFISCH/Produzieren/lis_projekt/proj_gamelife/ConwayScientificAmerican.htm <br><br>
 All patterns downloaded from: <br>
 http://www.conwaylife.com/wiki/Main_Page
 
 ### Screenshots
 The main page allow the user to play around with the Conway’s Game of Life:
 it's also possible to edit each cell.
 
 ![Game Board](images/readme/gameboard.png)
 
 Thanks to the settings screen is possible to speed up the animation or zoom 
 on board. The user can also select from the proposed list a pattern to fill the board with.  
 
 ![Settings](images/readme/settings_screen.png)
