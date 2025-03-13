# Entry 3
##### 3/12/25

### Context

After setting goals for winterbreak and above, we got to learning our tool which is GoDot. Our goal for this break was to get more familiar with GoDot engine, and the sections/components that make up the engine such as filesystem, scenes, and inspector. We wanted to understand and learn the engine (not the code), and how to use the tools in GoDot to create a prototype of our game. Our freedom project is to create a 2D pixel game that simulates real life; trading, buying and selling with a hint of magical elements such monsters. Like the last blog, this blog will focus on how we learned our tool this month. 

### Progress

Putting a pause to learning GDscript, we wanted to become more familiarized with how to actually use the engine in creating our game. Unlike other applications I have tried such as kaboom, the world, sprite, and items will not be created using code. To start off on my learning, I first downloaded the engine through the goDot website, downloading it to my files in my computer. From there, I opened it up, and explored the engine, to understand what each tool and section does and how I can use it to create my 2D pixel game. On that day, for about 1 hour all I did was tinker and mess with the engine, clicking on random stuff to get a brief understanding of what I was doing. To be honest, the engine itself was very overwhelming, so I decided to watch a video () on a beginner guide on using the engine. From that video, I learned quite alot ranging from inspector and filesystem, to all kinds nodes and scenes. The first thing I familiarized myself with is the concept behind creating something in goDot. In goDot everything is comprised of nodes, which is individual parts of a object or what we called scenes in goDot, such as the physics of a character. When you combine multiple types of nodes, you create one scene such as a coin object that can be used in a bigger scene such as a world map. This is essentially how games in goDot are created: nodes -- scenes --> game. When I understood this, everything became easier including learning each tool in goDot. Instead of explaining what I learned, a picture below is shown that shows my interpretation of each major section in the engine. 


After figuring out the engine and learning more about it, I started to learn and create a game in 2D in the engine to further understand how to use goDot. The first thing I did was find a sprite sheet online that is free and is useable. I downloaded the sprite sheet and imported into my filesystem. Afterwards, I found some tilesheets that I liked and imported into the tile2D node using the inspectors. From there, I started to create my map of my game by "painting" into the screen like shown below:



Unlike other coding apps, goDot lets you create a world map and blocks by dragging it onto the screen. When I finished that, I added physics nodes and colliison nodes into the spirit and adjusted it using the inspector. When I press the play button to run my game, my spriit fell right through my map tiles, so I decided to also add the phsics node to the tiles itself to give it a solid ground. To do this, all I needed to do was use the inspector to select the tiles that I wanted to add this node to. Afterwards, I once again ran the game and my problem was fixed. However, I couldnt move the spriti whatsoever, and I had no idea how to make it move either so I did some research on what to do. I rewatched the video and found that goDot actually had a library for prewritten code, so I added a movement gdSCript from the libary and imported into a file in the engine. This allowed my spirit to jump and move left/right but it was too fast so I changed the code a bit by changing the vecoity of it. When I ran it once more, my prootype of my tinkering was done; the basic movement and the basic map. 






With this mini project finished, I was able to grasp a better understanding of how to use this in my own game that we will start to code in a week. Our next step will be to create our sprite  and map while also learning the codes from GDscript. 



### Engineering Design Process

We are currently on step 4 and 5 of the Engineering Design Process](https://hstatsep.github.io/students/) which is to plan and create our prototype, In the future we hope to finish creating our game and to test it out for any bugs. However as of now, we are still in the beginning of making our game, and hopefully will start making progress. Our goal with this game is to cure our boredom problem by creating something we always enjoyed which was playing games. We hope to get feedback in a few months so that we are able to improve our game.

### Skills

The skills we used in this blog was Collaboration and How to Learn. Collaboration is working together with a partner or group effectively to achieve a mutual goal while How to Learn is the skill of learning something on your own. With this being a tool we have never used or known existed until this year, we had to learn how to use it all on our own. There was videos out there and documentation that we had to watch and read in our free time to understand how to use this tool. It was something we had to dedicate our time to, and we had to try our best to learn it displaying the skill of LOYO. Not to mention, me and my partner had to communicate with each other and work together on this project by making sure we are on the same page, and actively keeping track of each person push and pull. In other words, we had to collaborate on our project by ensuring that we know and do what we are suppose to do. To sum it up, this blog heavily rely on the use of collaboration and how to learn as we had to learn our tool and collaborate on our project so that we can develop the 2D game. 

### Next Steps

Our next step is to start actually coding our game. We have learned a lot of what we need such as sprite, world building, nodes and scenes that is used to develop a game. Now we have to start putting everything we know into one single project. We have to basically create a prototype and physical components of the game so that we have the layout mapped out. From there, we can start adding our own gdScript by of course first spending a few weeks learning it. However that step can come after we have "wireframed" our game, and have installed everything needed to complete our MVP. After the MVP and all the needed code, we might add some extension to the game to make it more challenging. 


[Previous](entry02.md) | [Next](entry04.md)

[Home](../README.md)
