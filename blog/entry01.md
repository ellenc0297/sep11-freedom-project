# Entry 1
##### 10/28/24
---
### Games
For this year's Freedom Project, I decided to work with my friends by making a separate game by spending cat food to let the user obtain the cat rarity based on what they got due to chances, and turn it into two parts and with two teams, then when we finished the game at the end of the year, we can combine them both together at the end of our Freedom Project. I am doing Part A of the game with Qilin, while Part B Xue and Katee will be making their part of the game. 

The section of the game I will be doing is **Part A** which is the "collecting foods," and to make the game work and based on how we wanted to be will be, I will be using my tools to help make the 2d, Kaboom. But to do that we need to make sure that the player can control the cat and make them move around in a 2D game (that looked like the snake game), the user will then let the cat move from one place to another to collect their foods, using their keyboard keys to help them collect as many cat foods as possible, with the given time limit. 

The others parts of the game called "cat gachapon", which is **Part B** which it will be based on RNG based with cats, but the user need to go to Part A of the game in order to do this or they can't do it. If the user did, the user can use their "cat food" in here to try to get the cats they got. But there will be a gunball looking machine, that rolls out a cat once. Based on the amount needed to roll once to get a cat based on chances. But there will three rarity based on what you got, (Rare, Super Rare, and Super Super Rare) sometimes the user can get the same one they had already obtained, some will be easy to get some will be hard to get. 

### Tool we use
The tool that I decided to use is [Kaboom](https://kaboomjs.com/) to help create part A with Qilin, while Katee and Xue will be using [P5Play](https://p5play.org/) to help create part B of the project. When I was learning "Kaboom", I went to Youtube to find some information about Kaboom, only to find out most of them were "what to do in kaboom" and etc. So, I decided to go to the official webiste to learn it from [Here](https://kaboomjs.com/doc/intro) only to use this to help me tinker my tools (and code snippet from there) and learn from that. Using the the website, I annotated from there to help expand my understanding of Kaboom. 

### Kaboom
Since, it been a while that the last time I created a little mini games back when I was doing "coding" all the way back in elementary school. I thought that some of the components looks familiar because I had used them before back, when I was doing "Code.org" like the ```pos()``` and I think ```sprite()``` if I remember correctly, but I think these knowledge will come in handy as I experience these types of components in the past. 

[Intro to Kaboom](https://kaboomjs.com/doc/intro) ---> I tinker using this as a reference on how to start my code for Kaboom, I learned how to use the img that I wanted using ```loadSprite()``` to make the sprite load up. 

I learned these as I was as I was tinkering my tools, that could be useful in my project
* ```sprite()``` - makes an image of the enivornment in 2D, ex: with "bean" sprite we can just loaded in loadSprite()
* ```add[()]``` - is to add it with the list of the components
* ```pos()``` - position by using the x and y coordinates
* ```area()``` - adds a collider to it
* ```scale()``` - the size of what you wanted to be of your sprite
Using my understanding based on what I know from what I saw from the information given to me, these are my notes to help me understand and help me tinker what was below

```js
            // load assets
            loadSprite("duck", "sprites/duck.png")

            // add my duck on my screen
            add([
	        // list of components
	        sprite("duck"),
	        pos(10, 20),
	        area(),
            scale(1)
            ])
```
I created an variable that help me contain my components, which is ```add([])``` it work like ```var``` variable that we usually learn in Javascript. I used the ```pos()``` it help coordinate the position of my spirte. I used ```scale()``` to help change the size of my sprite.

### Engineering Design Process 
I think am in steps where I am doing some **Brainstroming** and **Researching** to make sure we all agree to what the project would look like to our satifastication while doing our research. On how some of the elements work using trails and error, while tinkering. I'm also in the process to brainstorm what I need to add in my game, while researching what needed to be tinker in there.

### Skills
Some skills that I’m praticing from while working on this blog are **time management**, **collabration**, and **communication**.

#### Time management
I have several commitments from outside of school, such as from these examples like don't procastinate while doing homework and doing my homework near the deadline. But my workload at school is becoming busier, so I needed to make more time for myself to relax more. So I decided to go home immediately and start doing my homework immediately, and to get help if neccassary from my friends. I think this change will change how I moving forward from now on.

#### Collabration
Collabration is the key to help keep things move faster and quicker, since more people are helping each other. But the struggles is that I barely do collabration with another one since I always work by myself with just one project in general. But if I were to do that if I slowly work on that I think I will get the hang of it. 

#### Communication
Communication was another important skill that I must develop over time. Since I’m working on this project with more than one people (group of 4), it’s important to collaborate and talk to one another. But, at the same time I had a hard time communicate with my peers because I don't know what to say and talk about, since I'm so used working independently. But by doing that, because since we will be doing it for this whole school years, I thought that If I can't communicate properly I will be suck and start having trouble on my own side without asking and etc. So I thought it's important to do communication as I will be doing that for the rest of the years. 




[Next](entry02.md)

[Home](../README.md)
