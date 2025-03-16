# Entry 4
##### 3/16/25
---
## Tool: Kaboom (context)
The main part of the project I was trying to make, is to make the sprite accessible to move for the user and other stuff that can help with my project. During the past months I was making some progress by how to make my sprite work the way I wanted them to be from the code I made, so I did it to practice more for my project. Since it will help me a lot to make it pretty and creative for my current project with my group mates and to have a good and smooth result that all of us are satifasted with. But to be able to tell that I was doing the work and it will work out with progress I made, I tinker using my tool for past months for our freedom project to help me expand my understanding of my tool from the, **Kaboom's Official Website** and what I need to work on with the tools that I'm using to make it better by tinker in my CS50.dev. (Since JSbin don't work because Kaboom need some specific link for it to work properly) so I have tinkering in there to help me to test the code.

### Tinker progress so far?
I learn my tool through the materials with the variable/terms give to me to help me make a small mini game. Throughout, my time learning from my tools to tinker place that I store in my progress and look at what I learn, but during the time learning I feel like I not doing much in my code, as my groupmate finish what they need for their project. This is what I have done during my time and my progress from my tinker.

``` js
kaboom()

            // load assets
            loadSprite("duck", "sprites/duck.png")

            // add my duck on my screen
            const duck = add([
	        // list of components
	        sprite("duck"),
	        pos(10, 20),
	        area(),
            body()
        ])

        loadSprite("froggie", "sprites/frog.jpg")

            // add my duck on my screen
            const froggie = add([
	        // list of components
	        sprite("froggie"),
	        pos(80, 40),
	        area(),
            body()

        ])

        // setGravity(1600)
        // // .jump() when "space" key is pressed
        // onKeyPress("space", () => {
   	 	//         duck.jump()
	    //             })

        onKeyDown("right", () => {
   	 	        duck.move(100, 5)
	                })

        onKeyDown("left", () => {
   	 	        duck.move(-100, -10)
	                })

        onKeyDown("up", () => {
   	 	        duck.move(0, -100)
	                })

        onKeyDown("down", () => {
   	 	        duck.move(0, 100)
	                })

        // keep track of score
        let score = 0;
        // display
        const scoreLabel = add([
            text(score),
            pos(24, 24),
            ]);

        </script>
    </body>
</html>
```
In my last progress I made extra sprities so when the sprite of the duck hit the sprite of the frog, you will be respawn. Since the frog can kill you because is an enemies. But my teammate doesn't since she already did that part, and even the score point part. But this was the code I was trying to work on with no progress because it doesn't work how I wanted it to be.

```js
// keep track of score
        let score = 0;
        // display
        const scoreLabel = add([
            text(score),
            pos(24, 24),
            ]);
```
### Plan to do next for my MVP?!
During the past month, I wanted to improve more from my progress because it looks like I didn't do much based on what I see, making the sprite load in and make it move using key button. So now that the break is over I was thinking to add more of...
- Color and menu button, so when the player click it will be transfer into the two different games that was created by us
- Other stuff to make our project look good --> draw more to make it look more creative? (we are doing that for our sprite and character in game)
- More ideas I can think of during the process of learning more of my tool or groupmates ideas

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

[Previous](entry03.md) | [Next](entry05.md)

[Home](../README.md)
