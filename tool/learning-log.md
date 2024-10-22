# Tool Learning Log

## Tool: **Kaboom**

## Project: **Collect Foods**

---

### 10/19/2024:
[Replit for Kaboom](https://replit.com/@replit/Kaboom#code/main.ts) ---> using this as a reference on how to start my code for Kaboom (basically a quicker/easiest version to start using Kaboom, using this as an example to help me understand the code a bit better.

After looking at the replit, based on what I can refer to
#### Notes
* "sprite()" - makes an image of the enivornment in 2D, with "bean" sprite we can just loaded in loadSprite()
* "add[()]" - is to add it with
* "pos()" - position with the x and y coordinates
* "area()" - adds a collider to it

``` js
add([
	// list of components
	sprite("bean"),
	pos(80, 40),
	area(),
])
```
#### Explain what I think is happening
I'm slowly learning on how this work, after researching a bit on how those codes work because I can't find place to tinker with this code with since it wont work.
But I think "bean" is the character they are using to demonstrate it, in the game enivorment where he use it to make him move
position is where he starts and the area be how big the place is for "bean" to go

### Goals
* to make sure to find a proper webiste to tinker my codes with, maybe try making an account for replit?
* do a bit more research on the codes ---> there could been more then that, **do more research**
* try not to procastinate too much ---> kept forgetting that I needed to learn my tools

---

### 10/22/24:
[Replit for Kaboom](https://replit.com/@replit/Kaboom#code/main.ts) ---> using this as a reference on how to start my code for Kaboom (basically a quicker/easiest version to start using Kaboom, using this as an example to help me understand the code a bit better.
I used this again to start seeing my code and if it works.

#### Notes
* "sprite()" - makes an image of the enivornment in 2D, with "bean" sprite we can just loaded in loadSprite()
* "add[()]" - is to add it with
* "pos()" - position with the x and y coordinates
* "area()" - adds a collider to it
* "scale()" - the size of what you wanted to be
Using my understanding based on what I know from what I saw from the information given to me

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
This was the code that I used to tinker and to expand my understanding of Kaboom, I used the image of my duck to test out the result that was given to me

### Challenges
Throughout the time when I was doing the code, I had some struggle when trying to load up the image because it give me the game's background, which isn't what I wanted. I wanted my duck to load in that was also included. So, I ask my friend, Qilin to clarify what was wrong with the image that I loaded in into my folder. She showed me that I could have sepreated the folder or forgot the ".." in the front. But it was because I didn't put it in the folder with Kaboom. But I solved this problem from there understanding and taking some notes into my "Sep11 Notes"

Another one was getting the image that I wanted, was a duck. Since I was usually on my ipad to upload my image into Github. But I forgot on how you do that and when I dragged the image and saved it, it didn't work. So, I ask my friend Essie to help me what I did wrong to help me clarify my misunderstanding on how to use the chrome issued from the school. She told me that I had to drag it once you have the file and named it. But I solved this problem from there understanding and taking some notes into my "Sep11 Notes" so I won't make the same mistake twice.

### Goals
* Try not to procastinate too much ---> kept forgetting that I needed to learn my tools
* Try to slowly understand how to use the computer, as I always use my ipad
* Do a bit more research and a bit more tinker to expand my understanding

<!--
* Links you used today (websites, videos, etc)
* Things you tried, progress you made, etc
* Challenges, a-ha moments, etc
* Questions you still have
* What you're going to try next
-->
