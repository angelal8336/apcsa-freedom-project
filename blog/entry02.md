# Entry 2
##### 12/4/24

### Context
After deciding on what tool I wanted to use for this year's freedom project, we will be spending a few month's learning about that tool. To recap, my goal is to create a 2D pixel game that involves real life components, like farming, building, buying and exploring. In other words, it's similar to a real life simulation with some "magical" elements. This project will be created using [goDot](https://godotengine.org/). For this blog, I will be explaining how I learned my tool this month.

### Process
To continue from where I left off in [GDscript from zero](https://gdquest.github.io/learn-gdscript/), I completed lessons 6 through 13. In lesson 6, we learned to use functions with parameters. We learned how to initialized and create a function that is used to repeat things in Godot. Using that knowledge, I completed four coding activities that required me to draw rectangles of different or any size using multiple parameters. While coding, I learned that these rectangles drawn could be used for outlines of items in a inventory and even a map. Below is my code for the activities combined. 

```
func draw_rectangle(length, height):
	move_forward(length)
	turn_right(90)
	move_forward(height)
	turn_right(90)
	move_forward(length)
	turn_right(90)
	move_forward(height)
	turn_right(90)
```

The code above draws a rectangle at any given length and height by the user, which means that we are able to draw any rectangle instead of just one size. 
Moving on, I learned how use variables but also the types of variables in lesson 7. This lesson explained sub and member variables and exactly how it worked. Apparently, a member variable are variables that are attached to the game's entity (character). Within a member variable there are sub variables like x and y, which can be accessed using a dot. When I learned about this, it reminded me of java methods that belong to the class and can be called by writing the method's name with (). After reading about lesson 7, I finished two coding practices that asked me to draw a rectangle at a precise position and draw squares at different position. Below is the code:

```
func run():
	position.x = 120
	position.y = 100
	draw_rectangle(200, 120)
```
This code draws a rectangle with a length of 200 and a width of 120 at the posititon (120, 100)
```
func run():
	position.x = 100
	position.y = 100
	draw_rectangle(100, 100)
	position.x = 300
	position.y = 300
	draw_rectangle(100, 100)
	position.x = 500
	position.y = 500
	draw_rectangle(100, 100)
```
This code above draws three rectangles at differnt positions that are each 100px away. In other words the rectangles drawn are separated by 100px in a diagonal pattern. 

For lessons 8 and 9, I learned how to create my own variables and use them to add and subtract values. I learned many operations that are used in goDot such as `-=` and `+=`. In fact, this lesson was the exact same as java, which made me breeze through it. Additional we were briefly taught the `print()` mehtod that allowed us to print something into a box we created. Not to mention, some important information was given to us in this lesson such as the fact that you can change the value of a `var` from a one datatype to another. For these lessons, we completed two activities that asked us to define a health variable and use that to do math. Below is the code:

```
var health = 100
func take_damage(amount):
	 health = health - amount

func heal(amount):
	health = health + amount
```
The code above adds and subtracts health from the character whenever it is called. So for example, if you call `take_damage(20)`, the health of the character will be 80. 

For lessons 10 and 11 we learned a special goDot loop function called `_process(delta)`. When this function is called, it will automatically run every frame. In other words, we can make a character move more than 100+ times within one second. This part was by far the hardest to understand as I couldn't gasp the concept of the delta. Even till now I have no idea how delta works, and can only assume that it is a built in variable. In fact, the delta in this loop is a special symbol that can represent quite a lot of things. One thing is the time delta that represents the amount of time since the last frame. In these lessons we were asked to rotate a character continuously, creating a circular movement using the loop. Then we were asked to use time delta to rotate the character so that it is dependent of time. Below is the two codes:

```
func _process(delta):
	rotate(0.05)
	move_local_x(5)
```
The code above rotates the character 0.05 while moving it by 5 to the right multiple times wihtin a second, creating an animation.
```
func _process(delta):
	rotate(2 * delta)
	move_local_x(100 * delta)
```
The code above rotates the character by 2 radians but this time the rotate is dependent on what delta is. In other words, it rotates the character in a constant motion that can be changed depending on the value of delta. 

Moving onto lesson 12, one of the more simpler lesson, we learned how to use variables to make code easier to read. We basically fixed an out of scope error using what we learned so far about variables, but also learned to clarify code using variables through two activites. Lastly for lesson 13, we learned conditional and used them to compare variables wihtin an activity. We learned if-else statements and operators such `<=`, `!=`, `>=`, `<`, and `>`. From this I realized that this is very similar to that of java or other coding languages, the only difference is that there are no () when you declare it. Using this knowledge, I completed a few activites that required me to code something that limited the health of the characters. Below is the codes:

```
func heal(amount):
	health += amount
	if health > 80:
		health = 80

func take_damage(amount):
	health = health - amount
	if health < 0:
		health = 0
```
The code above prevents the health of the character from going below 0 or going above 80. This means that the health cannot be negative or greater than 80, setting a limit to the amount of hp the character have. 

### Goals- winter break
During winter break, I have a few goals that I would like to achieve related to learning my tool. The main goal I set for myself is to finish the rest of the lessons in learn goDot from zero while logging them down so I am prepared to actually start learning more advance methods from the documentation. I hope to complete this goal 3 days before the break ends so I can spare some time for other important tasks. A smaller goal I have if able, is to create a large project to review everything I learned so far in goDot. Some codes learned here are specifically design for these lessons, so I might not be able to use them but I can still review the concepts of goDot such as conditional. I will try to dedicate about one hour a day/two days to learn goDot methods/codes so that when I get back I can official begin coding if allowed.

### Engineering Design Process
We are currently still on steps 2 and 3 of the [Engineering Design Process](https://hstatsep.github.io/students/) which is to research as in learning our tool and brainstorm how we should make this game. Soon we will begin to start planning the design of the game; concepts, maps, inventory, etc, and hopefully we can start to actually bring our plan alive by coding it. However for now, we will still continue to learn our tool until we are able to have enough information to start creating the game. This game is designed to solve our boredom but also to do what we are very passionate about which is games so I hope me and my partner can move along the EDP, in order to receive our feedback and to improve it. 

### Skills
This blog required the skill of how to learn and growth mindset. How to learn is the ability to learn on your own in a way that allows you to progress in your knowledge. Growth mindset is the ability to keep trying until you succeed. Combined, they are the ability to learn without giving up. In this entry I utilize these skills the most, improving them along the journey. For example, when doing the lessons in goDot, I did not give up despite trying to learn a whole new language. Yes it was difficult to understand at times such as `_process(delta)`, but I took it upon myself to keep trying until I have a decent understanding on the concept, displaying growth mindset. As for how to learn, me learning the tools at home and progressing through the lessons shows my willingness to put in my personality time into doing something I enjoyed, displaying the skill of how to learn. In other words, not only was I able to learn the tool by myself, I was about to continue it despite struggling on certain concepts, like time delta and functions. In summary, I believe that I have 100% improved on these skills even if I have room to grow. 

[Previous](entry01.md) | [Next](entry03.md)

[Home](../README.md)
