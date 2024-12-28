# Entry 2
##### 12/9/24
---
## Tool: Kaboom (context)
The main part of the project was to make the sprite accessible to move for the user, during the past months I was about to make some progress by how to make my sprite work the way I wanted to be and the code, so I can practice to do it for my project. It will help a lot to make it pretty and helpful for my current freedom project with my group mate and to make it look good and smooth with the result we are satifasted with. But to be able to tell that I was doing the work and it will work out with progress I made, I tinker using my tool for past months for our freedom project to help me expand my understanding of my tool from the, **Kaboom's official website** and what I need to work on with the tools that I'm using to make it better by tinker in my CS50.dev. (Since JSbin don't work because Kaboom need some specific link for it to work properly) so I have tinkering in there to help me to test the code. 

### Tinker progress so far?
I learn my tool through the materials with the variable/terms gave to us to help me make a small mini game. Throughout, my time learning from my tools to tinker place that I store in my progress and look at what I learn. This is what I have done during my time and my progress from my tinker. 

``` js
const duck = add([
	        // list of components
	        sprite("duck"),
	        pos(10, 20),
	        area(),
            body()
        ])

        onKeyPress("right", () => {
   	 	        duck.move(500, 5)
	                })
        onKeyPress("left", () => {
   	 	        duck.move(-500, 5)
	                })
        onKeyPress("up", () => {
   	 	        duck.move(-0, -3500)
	                })
        onKeyPress("down", () => {
   	 	        duck.move(+0, 3500)
	                })
```
This was my progress to try to make the duck move so the duck can move to different area by tapping on the button to make them move from the sprite I gave the user to move around with, but before it became like this it was more of getting the setup of the duck to make it pop out, so I can slowly start my project on what I can do with my sprite 

``` js
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
This was my beginning progress to see if it works and a lot of trail of error because of technical issues and somehow don't work, throughout my challenges, but it work out somehow and it work. By looking at some spelling and missing variable to not make it unable to run correctly. 

### Winter Break Goal?!
During the *Winter Break* I wanted to improve more from my progress because it looks like I didn't do much from the look of it, making the sprite load in and make it move using button. I was thinking when I'm bored during my time in winter break, I can improve a bit from what I need to add for my current freedom project. I was thinking to add more of...
- Learn how to do set a timer, since my groupmate agree to add timer so the user doesn't infitine collect the cat food and stop when they feel like stopping, so if I learn how to do that they will get how much they have in there inventory.
- I had made the duck able to move from four direction (top, left, right and down), but it won't hold down continuously and realized there was a code for it to hold continuosly ---> means that I will need to tinker over time
- If I don't do anything during the winter break, I will forget them when I come back from school. So I need to do them maybe day by day if not when I have the time to tinker.  

## Engineering Design Process
I am currently on the stage of on **Improve**, **Research** and **Test**, I believe that I'm still on that stage to do more stuff from my tinkering process because that is not enough to make any progress on our project for the freedom project. By doing that I need to research more on *Kaboom* so I can help my groupmates, Qilin. So, I can be able to look through my tinkering log to help my groupmate on the project and have the code ready to be type in. Without that part of the process it can lead to failure and confusion on the project. At the same time, testing my code to see if it work and move the way that I wanted to be so I can use it the way that I like it, so I can put it on my freedom project. 

### Skills
Some skills that I’m practicing with while working on this freedom project are **time management**, **collabration**, and **communication**.

#### Time management
I have several commitments from outside of school, such as from these examples like don't procastinate while doing homework and doing my homework near the deadline. But my workload at school is becoming busier, so I needed to make more time for myself to relax more. So I decided to go home immediately and start doing my homework immediately, and to get help if neccassary from my friends. I think this change will change how I moving forward from now on and to help prevent burnout. 

#### Collabration
Collabration is the key to help keep things move faster and quicker, which is also another thing that I'm practicing since more people are helping each other. But the struggles is that I barely do collabration with another one since I always work by myself with just one project in general. But if I were to do that if I slowly work on that I think I will get the hang of it. 

#### Communication
Communication was another important skill that I must develop over time. Since I’m working on this project with more than one people (group of 4), it’s important to collaborate and talk to one another. But, at the same time I had a hard time communicate with my peers because I don't know what to say and talk about, since I'm so used working independently. But by doing that, because since we will be doing it for this whole school years, I thought that If I can't communicate properly I will be suck and start having trouble on my own side without asking and etc. So I thought it's important to do communication as I will be doing that for the rest of the years with my groupmate to help improve how I talk with the others too. 


[Previous](entry01.md) | [Next](entry03.md)

[Home](../README.md)
