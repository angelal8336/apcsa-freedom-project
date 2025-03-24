# Tool Learning Log

## Tool: **GoDot**

## Project: **X**

---

### 10/6/24:
* I read the introduction for goDot and learned what goDot is, what engine, and how to start using it
  * goDot is an free game creating platform that allows you to create 2d and 3d games using GDscript which stands for Godot script
  * There are many sources of recourses to use such as watching Gdquest, and viewing websites like gdscript.com

* I did the beginner tutorial called learn GDscript from zero to learn how to code in gdscript.
  * Lesson 1: States why we code, how we code, and basically general information about coding.
  * Lesson 2: Learns why errors are good, and a tool installed in goDot that helps explain an error message. In addition, we practiced fixing an error in an function
  * Lesson 3: Learned how to use functions like `show()`, `hide()`, `move_local_x()`, `move_local_y()`, and `rotate()`
    * `show()` makes something visible, and `hide()` makes something invisible; no need arguments
    * `move_local_x()` and `move_local_y()` moves something by # of pixels; one argument
    * rotate() rotates something; one argument
    * In GoDot we must use an exisiting function inside of an custom function
      * To create an function in GDscipt, you write `func name():`
      * Learned what an agrument is 
  * Lesson 4: Learned how to move something using `move_forward()`, `turn_right()`, `turn_left()`
    * *these function only works in learn GDscript from zero, and not actually in goDot*
  * Lesson 5: Coded my own function using GDscript
    * You create a function using func, name, colons, and then :
    * Each line of code inside a function MUST be indented



### 11/24/24:

* Lesson 6: Learned how to use functions with parameters -- how to create them
  * Finished coding activity 1 through 4, which includes: Drawing corners of different sizes, Using multiple parameters, drawing squares of any size, and drawing rectangles of any size.
     * Learned how to use parameters to draw squares and rectangles that can be used in game as an "outline for items in inventory", map, etc
* Lesson 7: Learned how to use variables, and the types of variables in goDot such as sub and member varables
  * Member varables are variables that are attached to the game's entity (character), and within each member varable there are sub-varables such as x and y that can be accessed using the dot.
  * Finished coding practice 1 and 2; Draw a rectangle at a precise position and Draw squares at different position
* Lesson 8: Learned how to create my own variables, and what print() does
  * To create an variable you write `var (name)` and assign it to an value using the = sign.
  * `print()` prints out something to your box
  * Variable is like an label and putting it on a item
  * IF YOU USE `var` TO DECLARE YOUR VARIABLE YOU CAN CHANGE THE VALUE FROM AN NUMBER TO ANOTHER DATATYPE LIKE STRINGS
  * Finished coding activity 1, define a health variable
* Lesson 9: Learned how to add and subtract an value
  * `-=`, `+=`, etc, does the operation and then set the vararible equal to that new value; shorten version of `health = health - amount`
  * Finished activities 1 and 2, damaging the robot and healing the robot
* Lesson 10: learned goDots loop function called `_process(delta)`
  * `_process(delta)` is an function that does continous actions and calculations
  * "if the function exists in your code, and it is called _process then goDot will automatically run it every frame"
  * Finished activities 1 and 2, Rotating a character continuously and creating circular movement

### 12/9/24:
 * Lesson 11: We learned to to use time Delta in the _process method
   * Almost every object has a _process method that can be used to load frames.
   * Completed Rotating Using Delta and Moving in a circle Using delta activity
 * Lesson 12: Learned how to use variables to make code easier to read
   * Completed Clafiying code using variables and fixing an out of scope error acivity
 * Lesson 13: Learned how to use conditions in Godot
   * Very similar to that of java or other coding lanuages, the only difference is that there are no ()
   * Completed using comparisons, limiting healing and preventing health from going below zero activity's
   * The conditional is the very much the same; <=, !=, >=, <, >, etc

### 3/9/24

* Watched this 1:17 hr long video explaining goDot engine
  * https://www.youtube.com/watch?v=LOhfqjmasi0 
* Learned how to use goDot engine such as the filesystem, nodes, and scenes to create characters and world
 * I created my own character that is able to move using spriti sheets and gdscript
   * The character was created using CharacterBody2D, AnimatedSprite2D, CollisionShape2D as well as gdScript to make it move. 
   * The Inspectors was used to modify the nodes (CollisionShape2D)
* I created my a map for my game using TileMap and tileset sheet
  * Basically I "drew" in the map and layed out all the tile blocks I wanted
  * I set the physics prorties to certain tiles so that I don't fall right through them
  * By putting Camera2D under the player, the camera follows the player

### 3/23/24
* Continued watching the 1:17 hr long video
  * https://www.youtube.com/watch?v=LOhfqjmasi0
* Learned how to create items that are able to be picked up like a coin
  * Uses Area2D node that doesn't allow collision but has an area to detect if another object enters.
  * Learned how to code GDscript for collisions using signals (there is a whole list of signal for area2d) and` quene_free()` (removes objects)
    * Put your character in another physics layers
* Learned how to make a character "lose" by using Camera2D and killzone
   * Learned to code a GDscript using signals again, timer, `getTree()`, and` Reload()`
* Learned how to use path to access different levels of a hierachy/tree
   *  For example to access the camera node inside the player inside the game, we would write $player/camera
*  Learned to caterioze nodes
* **ADDED more elements to my project such as coins, score, and losing**
   * **Basically I created my own coin sprite using sprite sheets, and added the conponments (signal and nodes) so that when my player touches it, it disappers and score++.**
   * **Added a system that restarts the game whenever the player falls**
 
 
   
  


<!-- 
* Links you used today (websites, videos, etc)
* Things you tried, progress you made, etc
* Challenges, a-ha moments, etc
* Questions you still have
* What you're going to try next
-->



