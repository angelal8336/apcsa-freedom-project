# Entry 1
##### 11/3/24

### Process

For this year's freedom project, I decided to create a open world game revolved around a mini version of society that involves farming, beating opponments, and stories with my partner Shelly. It will be a game similar to stardew village, as it was part of inspiration. I want to create this game using the tool, goDot. goDot is a free game engine that allows for pixeled creation in 2D or 3D. I choose goDot for two reason; I was interested in creating pixel games, and it was the only engine that caught my attention. When I first started this freedom project, I was made to choose what I wanted to create, and what tool I would want to use. I brainstormed 2 ideas with my partner. The first idea was the creation of an moblie app using swift. This app could be a reminder, story, or any app that was useful for students. The second idea was the creation of a open 2d pixel game where users would go through a series of story quests that involved beating opponents or solving an secret puzzle using goDot. Utiately I came to the conlsudion of creating my second idea as it seemed more fun to learn. This is when I partnered up with shelly to create a game, as we both had an common ground, and both wanted to create an open world pixel game using the same tool. 

So how exactly did I tinker with my tool? Well, the first thing I did was to read the dosucmentation, and introduction on the goDot website to learn more about how the engine works and where I can begin. Afterwards, I started their specifially created lessons called GDscript from zero to learn how to code in gdscript. I went through each lessons to learn the main concepts, and coding I would need. The first lesson taught the general infomtion about coding; why and how we code. The second lesson taught me why errors are good but also introduced us to a tool installed in goDot that helps explain an error message. In addition, from that we practiced fixing an error in an function. Moving on, the third lesson taught us that how to use specific functions in Gdscpit such as show(), hide(), move_local_x(), move_local_y(), and rotate(). For example, in the picture below, we learned that by using show() will make an onject that was invisible show, and rotate() would make an object roatate by a certain degree to the left or to right. In addition, we learned that gdScipt is different from regular coding lanagues as the syntax is a bit different. 

```
func run():
    show()
    rotate(0.3)
```

In the next lesson; lesson 4; we were taught how to move something using move_forward(), turn_right(), turn_left(). We were tasked with making an rectangle, and drawing an corner using these commands. I wrote my own code in Gdscipt so that I could create an rectangle using the fnctions I had learned, shown below. 

```
func draw_rectangle():
    move_forward(220)
    turn_right(90)
    move_forward(260)
    turn_right(90)
    move_forward(220)
    turn_right(90)
    move_forward(260)
    turn_right(90)
```
This code allowed the object which was an turtle to move and turn which created an 220 by 260 rectangle. In the last lesson I did; lesson 5, we were taught how to write our own function in gdScript. This lesson was quite hard but I learned two important things. One, you create a function by using func, name, colons, and then :, and two each line of code inside a function MUST be indented. I created my own function that allowed for me to draw three squares at different positions like shown below

```
func draw_three_squares():
    draw_square()
    jump(300,330)
    draw_square()
    jump(300,330)
    draw_square()
```

This code uses an already created function called draw_square to draw three squares at different points by using jump().

### EDP

We are currently in steps 1, 2, and 3 of our engierring design process. As a team, we have defined and researched our tool/game, and brainstormed a few ideas that we wanted to create using our tool. Soon we will go onto step 4 and 5 of our edngierring design process which is to plan and create our protype. Before we do so, we have to learn more about our tool and gasp the concepts, so that we can use it to create out own projects. The problem I wanted to solve once again was boredom. There are many games out there that I like to play, but I want to understand the Behind the scene of thoses games. In other words, I want to feel the joy of playing a game I designed with my partner. In order to do so, I would need to move along in my EDP, so that I can create, design, and get feedback on the game I will create at the end of the year. 


### Skills

The skills I used in the blog was How to learn and how to read. How to learn is the ability to learn something on your own. How to read is the ability to read an article or text and understand what it is telling you. In the entry, I had used and improved on both of these skills by brainstorming my own ideas, and also having the will to go an learn an whole engine alone. For instance, I had to read the whole doucmentation of goDot, and also do their lessons on learn gdscipt from zero. That thing was long, and it was my job to understand the text, and really learn how to use the engine well. Without both of the skills of reading and learning, I would not have understand what im learning or even where to begin nor would I have actually tried to tinker and learn the tool and how I could use it. Basically without using these two skills I would not have been able to write this blog and actually begin my freedom project.

[Next](entry02.md)

[Home](../README.md)
