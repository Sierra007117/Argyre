# PineCraft
 
<p align="center"><img alt="BCK" src="http://www.desktopimages.org/pictures/2013/0717/4/creeper-minecraft-anime-ende-wallpaper-694391.jpg"></p>

# PineCraft : A Command Line Interface Implementation of Minecraft in Python
_____________________________________________
# Software Documentation
_____________________________________________________________________________ 
## Created By:
* <b>[2017002102] Tayef Shiham </b>
* <b>[2017002106] Mahadi Sajjad Neloy </b>
* <b>[2017060056] Alec Mabhiza Chirawu </b>
<p> Class 20170021 Object Oriented Programming Computer Science and Technology Department of Information Engineering Huzhou University </p>


# PineCraft Software Documentation
* Contents..........................
* Introduction............................... 
* Objectives..................................... 
* Walkthrough...................................... 
* Implementation............................ 
* Objects.......................................
1. ### Introduction 

* The inspiration of this project Minecraft is a sandbox video game created by Swedish game developer Markus Persson and released by Mojang in 2011.
* The game allows players to build with a variety of different blocks in a 3D procedurally generated world, requiring creativity from players. 
* Other activities in the game include exploration, resource gathering, crafting, and combat. 
* Multiple game modes that change gameplay are available, including—but not limited to—a survival mode, in which players must acquire resources to build the world and maintain health, and a creative mode, where players have unlimited resources to build with. 
* <b>The Java Edition </b> of the game allows players to modify the game with mods to create new gameplay mechanics, items, textures and assets.
* With the same core mechanics in mind,PineCraft has been developed to bring the same game mechanics in a terminal.In PineCraft,player starts with a specific number of items,crafts more items given in the object library and when user succeeds in meeting the goal of making a specific item or a number of items,the game ends in a victory. 
 
 
2. ### Objectives 
* The objective of PineCraft is not so different from Minecraft. However, unlike Minecraft, PineCraft has been developed in Python to be played on a Command Line Interface so that it can be played on any Bash Terminal or any other platform that provides a Command Line Interface.
* The objects in this game are modular,the mechanics are easy to understand and implement so that it can be modded beyond oblivion if the user wants custom items and specific crafting rules. 
3. ### Walkthrough 
* Welcome to Bonga Bonga islands, things don’t go according to the plan, as we all know islands are very cold and since you are lost ,there is no more time to run but to settle down for the night. 
* The question is how will you survive this phenomenon, at least your spirit didn’t leave you and the solution for survival is here, your mission is to figure out how it will build up. 
* Due to the reason that you are new in this forest this is the guideline for the survival.There are help keys you need to know first which are: √ Pressing question mark(?) will show you the two options which are your guide while playing the game.
* √ Pressing ‘i’ will show you the inventory this will help you to keep track of your inventory along the game √ Pressing ‘c’ will show you crafting options After starting the game you need to press i so that you will see what items you have to start building your tent,firepit and torch. 
* A list and quantity of items in the inventory will show up and you have to to choose what you want to craft first and you have to take note that some items like axe cannot be crafted without items like twig. Craft your items by typing ‘craft’ and the name of the item you want to craft for e.g. “craft hay” That will be the way of crafting for the whole game until you manage to craft tent, firepit and torch (maybe an axe,just in case) which will help you to the survive the whole night in the island.
* Be aware that if you run out of mandatory items,the game will be over and you will not be able to survive which means you will be forced either to exit the game or play again. 
* If and only if you manage to craft everything required that’s when you will win or else you get stuck in the Bonga Bonga island.
4. ### Implementation 
* The code has two primary segments;the first one being the object definition segment which contains the object library along with object crafting perimeters and the second one being the game mechanics control segment which contains the algorithm to run the program.
* During development,scalability was the one of the key concerns so that the user is able to manipulate data without destroying the core. 

