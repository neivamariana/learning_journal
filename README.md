# learning_journal
Class learning journal - Mariana - LSBU Game Programming

Learning Journal:

I had handwritten notes, so I have divided my journal into 2 Sections:
Class logs and Project logs.
Class logs are my class notes and Project logs notes I took while I was doing each section for my game prototype and tutorials.
Class Logs:
Week one:

Don't Delete things because their wrong!
Collect evidence because it shows you made it.

Unity Problem:
Doesn't give things enough push.
Fix this by correcting the 2 decimal places

Always make GitHub 
Projects Public so lecturers can see it.

Evidence of Progress:
"I hear it, and I forget it,
I see it and I remember
I do and I understand."

Pomodoro technique: "a time management method that helps you break down work into manageable chunks"

Scientific method:
Guess 
Predict the implications of guess.
Compare with experiment.
It if disagrees, your guess is incorrect
Try again!

Week two
:

Create a learning journal.
Create a Depository on GitHub:
	Make it Public,
	Add a ReadMe
	Gitgnone Unity
	License none
	Don’t forget to commit changes!

Anatomy of a script:
Everything in C# is a class.
C# is an object-oriented system.
Classes are based on other classes.
Member Variable is a member of the class.

Week 3 to 6 log:
Create 4 tutorials.
1 Game Prototype
1 video of game prototype.
1 learning journal.

Ideas for Tutorials:
1 Start screen:
	Buttons:
		1st create a canvas in unity
		2nd create the buttons on unity
		3rd create a script and attach it to the buttons.
My guess:
Different functions for different buttons?
Public void AllButtons (string button)?
Planning:
I will do this for all the following Steps:
Take screenshots along the way.
Write out the tutorial when I finish, or I might do that at the end when I complete all my scripts, at this point I haven’t decided
Learning journal entry dedicated to each script.

4 tutorials I deas:
First tutorial MainMenu UI:
1st I will make the buttons/ start menu
2nd I will program them
3rd I will connect them
[Idea for possible buttons I will make Start, Exit/Quit, Chapter, Setting back load]
Second Tutorial Player Movement:
1st Create player
2nd Program movement script
3rd Then connect it to player
[right now I am doing thinking of doing this in a top down view with a point click movement system.]

Third Tutorial Inventory:
1st create inventory in scene
2nd Program inventory script
3rd Then connect the script to the inventory.

Forth tutorial Currency System:
1st Create currency Prefab
2nd Program currency script
3rd Then connect it to prefab and player.

Week 7, class notes:
When zipping a Unity project, delete the library folder.
The needed files are the following:
Assets
Packages
Project Settings

No spaces in Unity File Names.
A repository is like a Database.

Week 8 to 12 log:
Schedule:
MainMenu: DONE
Steps:
Unity File: DONE
Canvas for UI: DONE
Make the buttons in Unity: DONE
Set scene by number in unity in the Scene List build profile: DONE
Make script for all buttons: DONE
Did I program them to find a scene by index in unity scene list? YES
Movement Program: Started
Steps
Remind myself of Time.Delta.time? DONE
Make Level 1 scene: DONE
Make a capsule and set it as the player: DONE
Make another capsule for the NPC: CHANGED MY MIND 
Instead:
Make Cubes and use them as obstacles: DONE 
Make a script for player movement: DONE
Make a Script for the player movement: Started but I am stuck.
Inventory System:
[Chest (button) > inventory <able to drag from and to> bag 
Steps:
Use level 1 scene and add chest: DONE
Make chest and bag buttons: 
Make scene for inventory and bag: DONE
Make chest a button:
Link Chest and bag buttons to scene inventory:
Program interactions between chest and bag
Program the interactions:
Add exit/back button:

Currency System:
[ I want to have 2 types of currency]
Steps:
Make wallet Pop-up that shows how much currency the player has:
Make wallet scene: Done
Add money example to level 1 scene:
Make currency script:
[Pseudo code: if player picks up the currency, then +1 else do nothing]

Folders I want to have in my unity project:
Button folder
Scene folder
Currency folder
Movement folder (NPC folder and Player folder)

Inventory Further Notes:
[I am struggling with this therefore I am making an extra log.]
1st Create a folder for your script to be organised.
[rethinking this I want to change the way I organised my folders I will make note of this later]
2nd Create a scene for inventory add an UI canvas.
Breaking it down:
What does an inventory have:
>The container;
>The item data;
>Item Instance.

What is an instance?
Item instance is a class that represents item data in game.
What is a class?
They are categories.
Real life example/ analogy:
Classes of society:
A King, 
A Duke,
A Marques.

King is the class or category. Depending on the Class they do different things.
Category dictates their job in society. 
Class dictates their behaviour (job) in the script.

What is Item data?
It is the definition of what it is and what stats it has etc.
Real Life example/ Analogy
A Dictionary:
The word Pomegranate:
The class of this word is a noun.
Then it is described: “a spherical fruit with a tough golden-orange outer skin and sweet red gelatinous flesh containing many seeds.”

Example in a game:
If I created a class for fruit in my game so that the player can eat and gain health.
The class would be Fruit
The item data would be: Food, specifically a fruit. Stats +10 health 
I could even add to this and make the stats be like so 
Pseudo Code: 
If (Player Eats fruit)
{If( fruit is ripe)
{then + 10 health }
Else ( meaning that the  fruit is rotten) 
{Then -10 health}}
This would make it so if a fruit is rotten and the player eats it they lose health if it is ripe they gain health.

Container:
Something that has the items stored in it
It allows you to pass different items between different containers in game (e.g. player moves fruit from a chest to a bag).
Sort of like when I have something at home in your bag and move it to my desk drawers or vice versa.
Creating the container:
I will need a sprite/image/plane in my scene
I want to make this a UI canvas in its own scene that can be called and overlayed in any scene in game expect the main menu
Then I will need to add text to say inventory, so the player knows what it is
Creating the items:
Elements to consider:
Can I have multiple elements? YES
Is there a limit to how many? 10
Do they stack? YES
Does every item stack? YES, this means I will need to use an 2D or 3D Array
Do they have a description of item data shown in game? YES

Example:
Base Item Pomegranate.
Item Data: price and health

Instance of object is what players have in inventory.
Inherits all the attributes from item class: Fruit (e.g. price, health, etc…)


Project Logs:

Programming learning journal 
General Logic:

Starting point: 
I already planned everything I originally wanted to make and how I was going to do it in my Class Logs.
Right now, I want to create a backlog of code I could re-use for other projects by changing simple things like the names of the variables. 
Obstacles:

I have quickly realised that for me to be able to create something I can consider a backlog, I will need to understand what I am coding and to make sure that my code made sense and that I know what I am using and why I am using it in each line of code.
Also, this will allow me to more easily make my tutorials!
How I overcame these obstacles:
Firstly, I simplified the goals I previously set. 
Instead of making movement, inventory and currency scripts I will make a game where you can drag and drop items and then another item will spawn. 
This is because while I am perfectly capable to code the previous goals, I want to be able to explain it well and so I think I need to pick a simple interaction and go from there. I picked drag, drop and spawn because it’s something I had to look at when I was thinking of my inventory and my currency system.
Since my tutorials will now be simpler I will focus om explaining everything well and learning along the way what things are. 
Secondly, I now have 3 aims to make this possible:
1 - if I watch a tutorial, I must research everything I don’t know how to explain.
2 - read and watch videos about programming theory.
3 - to re-read every script I create and made sure I understand what everything is doing and why.
What I achieved:
With these aims I ensured that I understood everything, and it made it a lot easier to then create a tutorial. I know I would have not been able to explain my scripts so thoroughly had I not gone back to the basics.



Menu UI:
Starting point: 
I want to create buttons to make a simple menu UI. 
This is something I am comfortable with doing.
Obstacles:
I quickly realised while I was comfortable creating this. I did not understand why I was doing certain things.

How I overcame these obstacles: 
So, I went back to my aims which allowed me to focus on the logical side of things.
I watched a lot of YouTube tutorials and researched each part of the code. 
I explained all of it in my tutorials. For example I learned that a void in unity means that the method or function has no return value, its empty. It has no Data type.
Data type is for example a Boolean, it will always have a value of true or false!

What I achieved:
I was most happy with my discovery of what a void is in C# since I had always wondered!
Also, I created a script that allows me to spawn a scene using the Unity and quit a game.
Then, I created a button that instead of using a script to spawn a scene, it uses the OnClick() in the unity inspector to enable and disable parts of the scene. 
This way I don’t need to make as many scenes that are extremely similar, like a main menu and an options menu. 
I also learned how to create a sliding bar in unity! In the future I want to learn how to create a script that allows buttons and a sliding to interact with elements like how loud the game is.



Dragging Log:
Starting point:
At this point I had no idea how to code this in c#. 
I did know that logically I had to some how tell unity that when the player clicks down the item on the mouse must follow. 
My guess was that I could use an If statement.
Pseudo Code:
Set variable Item
If(player clicks down) 
{then Item follows;}
Else 
{do nothing}

Obstacles:
I know what my logic makes sense, but I don’t know if it works with C# logic.
How am I going to tell unity where the mouse is?
How will unity know what items can move?
How I overcame these obstacles:
I watched a few videos and ended up being able to code it and understand it but simply looking at what things where on several websites. My favourite find was Unity Documentation. Its like a manual for Unity including code, I read this, and it helped me a lot. I always when back to it to check what something did! Even if sometimes I don’t understand what the documentation means I can research it elsewhere.
What I achieved:
I achieve a code that not only drags an item when the player clicks down on their mouse it also offsets the item to not be completely under the mouse so that it looks better!

Dropping Log:
Starting point: 
Since I can more easily read code and understand it now, I wanted to try to code this by myself.
Obstacles:
Again, for me I as I understand it this would be written like so:
Pseudo Code:
If(player lets go of mouse) 
{Then item drops}
I assume that I need to create a method for MouseUp. I also assume that I will need to use a prefab somewhere if not here later down the line.
I don’t know how I will make it so the item can ONLY be dropped in the slot Else it will go back to the original position.

How I overcame these obstacles:
I gave it some tries and when it realised that I still needed more help I went back to my video.
What I achieved:	
I created a script that now drags and drops only to a slot I set when the player doesn’t drop it in the slot it drags back to the original position. 

Spawning Log:
Starting point: 
I wanted to be able to code something that will add to my script the ability to now spawn a prefab if the player adds the correct items 
Obstacles:
I couldn’t find a video that did what I wanted nor one I understood.
How I overcame these obstacles:
I asked my family for help, since some of them are programmers, they could help me but they do not program games or in C# so they mostly helped me with the logic.
So I had to go back to my trusty Unity Documentation.

What I achieved:
I learned how to spawn a prefab and how to force unity to let me see a private variable in the inspector with “[SerializedField]”. Then I learned how to spawn an item or how to “Instantiate()” an item in unity. 
Using an If statement inside an If stamen I already had I achieved my desired result of a game prototype that allows me to drag items to slots and spawn an item after deleting the items I dropped.

Tutorials:
Starting point: 
I had no idea how I wanted to make these. So, I started by using word documents and I even considered making a website just for these. 
Obstacles:
I thought a tutorial in a word document would be hard to read and understand and a website would complicate it too much.
My biggest hurdle was that I simply did not want to make a tutorial that left people wondering but what is this line for?
This is because I am always frustrated by tutorials that leave me having to endlessly research or watch even more tutorials. 
I don’t want the person following my tutorial to be stuck in an infinite Tutorial loop! (because I was at the start of the project before I set my goals)
How I overcame these obstacles:
I made myself look at my tutorials as if I was teaching a class or if I was teaching my sister how to do this. So, I used PowerPoints because not only are they more interesting visually, at least for me, a word document can be quite daunting, but a PowerPoint makes things look more digestible. 
I decided to write my tutorial how I write my recipes! I see them as tutorials in a way and I want anyone to be able to understand them and use them no matter the skill level.
I explained every line of code and even added extra information where I thought someone that doesn’t know a lot about C# or even programming in general would get confused. I tried to add these in extra slides so that if someone doesn’t need them they can skip it!
 
What I achieved:
In the end I believe I created tutorials that would have at least helped me in the beginning of my learning journey!

Final Thoughts:
Starting point: 
I started this project being very worried about my lack of ability to read my code and other peoples code and understand it.
This was concerning since I know what I cannot teach something that I don’t fully understand.
However, I have been very adamant since the beginning about creating code I can reuse or at least go back to and remember how to do something. 
Obstacles:
I always struggle with time management. 
I always aim for my best possible outcome. This means that sometimes I want to very complicate things and I get frustrated when I cannot.
I got stuck watching and reading tutorials for a while.
I didn’t know how to create a backlog of code I could re-use when I didn’t understand it.
How I overcame these obstacles:
I planned multiple times how I wanted to do things and made step by step lists!
I simplified my goals! Quality over quantity.
I set goals to stop my need for tutorials and started to break code down into smaller pieces.
I created 2 scripts I will be able to reuse and add to.
What I achieved:
I achieved 4 tutorials, 1 game prototype and most importantly I deepened my understanding of C# and Unity.
















 














