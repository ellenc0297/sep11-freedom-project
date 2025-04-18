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

---

### 11/4/24:
[Kaboom Notes](https://kaboomjs.com/doc/intro) after trying out the code with trails and error from the examples, I realized there was notes in the official website that I didn't know about.

#### Notes
* "onKeyPress()" - when the user press on a specific key makes it run continuously
* ".jump()" - make the character jump
* "body()" - gives it a physical body, making it fall due to gravity and ability to jump ---> slow fall
* "move()" - makes it move towards a direction infinitely, where u want it to go
* "anchor()" - defines the origin point of positioning, same as "pos()" but instead of top left we can do any pos u want

---

### 11/18/24:
[Kaboom Notes](https://kaboomjs.com/doc/intro) using this for my notes up there to continue futher my understanding of kaboom

#### Video
[Kaboom Startup](https://youtu.be/iRXI6ThRJvM?si=I_ZWxmmtyYsf7bNC) It helped me understand how to setup my kaboom and help learn other component of codes
* ```.solid()``` the player won't fall through the screen, it used to help it from doing that ---> it can go on top of items like an actual soild

The rest of the video it was just him using animation and other tools, which I'm not learning. But if you continue on towards the end there was more Kaboom stuff
* ```.origin()``` where the start position going to be ---> could be left, center, and etc
* ```.keyPress()``` where the user can press on the key based on where they want to go to an direction ---> space, left, right and etc

#### Tinker
```js
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
When I was tinkering my code for I changed some of the code from the pervious time when I tinker, I added a ```const``` in my code because I needed a varaible for as "duck" so that the ```const``` can be used for the bottom, for ```onKeyPress``` can help me move my sprite. I made the sprite ```body()``` so it can be soild and respond to gravity.

I was struggling to make the spirite move as it kept saying error even though I did it correctly, I got pissed and I asked for help. But I realized it was glitch as I type the same code again.

```js
 // setGravity(1600)
        // // .jump() when "space" key is pressed
        // onKeyPress("space", () => {
```
This code when I was trying out help make it like "Flappy Bird" that continuious jump everytime the user press the spacebar. I was using this when I was struggling to do the moving the sprite and took the examples from the "Kaboom"

### Goals
* Try not to procastinate too much ---> kept forgetting that I needed to learn my tools
* Is ok to stress over things as it could be a glitch ---> I got pissed off and kept fixing it even tho is correct, but it said it was wrong. But I realized it was a glitch for some reason
* Try to slowly understand how to use the computer, as I always use my ipad
* Do a bit more research and a bit more tinker to expand my understanding

### 12/8/24
[Kaboom Notes](https://kaboomjs.com/doc/intro) after trying out the code with trails and error from the examples, I realized there was notes in the official website that I didn't know about.

This was the beginning of it and combined with the rest of my code
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


```js
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
It now works as it walk to make it work

### Challenges
Throughout the time when I was doing the code, I had some struggle when trying to load up the image because it give me the game's background, which isn't what I wanted. I wanted my duck to load in that was also included. So, I ask my friend, Qilin to clarify what was wrong with the image that I loaded in into my folder. She showed me that I could have sepreated the folder or forgot the ".." in the front. But it was because I didn't put it in the folder with Kaboom. But I solved this problem from there understanding and taking some notes into my "Sep11 Notes"

Another one was getting the image that I wanted, was a duck. Since I was usually on my ipad to upload my image into Github. But I forgot on how you do that and when I dragged the image and saved it, it didn't work. So, I ask my friend Essie to help me what I did wrong to help me clarify my misunderstanding on how to use the chrome issued from the school. She told me that I had to drag it once you have the file and named it. But I solved this problem from there understanding and taking some notes into my "Sep11 Notes" so I won't make the same mistake twice.

The third one was how the duck doesn't move how I wanted to be, I somehow made it work with the video that I used previously. It somehow doesn't work, so I ask my friend to help me, Qilin said that the coordinate of the code is wrong making it look werid and work properly. I changed it based on what she said and it works now.

### Goals
* Try not to procastinate too much ---> kept forgetting that I needed to learn my tools
* Is ok to stress over things as it could be a glitch ---> I got pissed off and kept fixing it even tho is correct, but it said it was wrong. But I realized it was a glitch for some reason
* Try to slowly understand how to use the computer, as I always use my ipad
* Do a bit more research and a bit more tinker to expand my understanding

### 12/28/24
[Kaboom Notes](https://kaboomjs.com/doc/intro) after trying out the code with trails and error from the examples, I realized there was notes in the official website that I didn't know about.

As my progress continue from my goal that I made in my blog only leads to some as failure as there was **challenges** on how it leads to failure as it doesn't work and won't pop out the way that I wanted giving me error everytime I do it, so I decided to do it next time when I come back from school and ask further, but I rememeber something I didn't make in my goal for my winter break progress was to try to make a score. It still in progress as I need to make more adjestment on the code I was trying to make how I want it to be like. As I was trying to make the score I realized I need more image so it can be workable for it to actually work. (when the player touch the food the score will go up)

Tinker of my code:
``` js
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

        // setGravity(1600)
        // // .jump() when "space" key is pressed
        // onKeyPress("space", () => {
   	 	//         duck.jump()
	    //             })

        onKeyPress("right", () => {
   	 	        duck.move(100, 5)

	                })
        onKeyPress("left", () => {
   	 	        duck.move(-100, 5)
	                })
        onKeyPress("up", () => {
   	 	        duck.move(-0, -3500)
	                })
        onKeyPress("down", () => {
   	 	        duck.move(+0, 3500)
	                })

        // keep track of score
        let score = 0;
        // display
        const scoreLabel = add([
            text(score),
            pos(24, 24),
            ]);
```
#### Goals
* Try not to procastinate too much ---> kept forgetting that I needed to learn my tools
* Is ok to stress over things as it could be a glitch ---> I got pissed off and kept fixing it even tho is correct, but it said it was wrong. But I realized it was a glitch for some reason
* Try to slowly understand how to use the computer, as I always use my ipad ---> the longer I use it the more I understand some of the shortcut on the computer
* Do a bit more research and a bit more tinker to expand my understanding ---> without much struggles

### 1/12/25
[Kaboom Notes](https://kaboomjs.com/doc/intro) after trying out the code with trails and error from the examples, I realized there was notes in the official website that I didn't know about.

As my progress continue from my goals that I made in my blog only leads to some as failure as there was **challenges** on how it leads to failure as it doesn't work and won't pop out the way that I wanted giving me error everytime I do it, so I decided to do it next time when I come back from school and ask further, so I asked my friends about how to make a the key continuously without having to press it over and over. I realized my mistake was that I type the function wrong and that's why it wasn't moving. So my next step of my progress is to try to make a timer for the game to make it actually work.

```js
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
```
#### Goals
* Try not to procastinate too much ---> kept forgetting that I needed to learn my tools
* Is ok to stress over things as it could be a glitch ---> I got pissed off and kept fixing it even tho is correct, but it said it was wrong. But I realized it was a glitch for some reason
* Try to slowly understand how to use the computer, as I always use my ipad ---> the longer I use it the more I understand some of the shortcut on the computer
* Do a bit more research and a bit more tinker to expand my understanding ---> without much struggles

### 3/2/25
[Kaboom Notes](https://kaboomjs.com/doc/intro) after trying out the code with trails and error from the examples, I realized there was notes in the official website that I didn't know about.

As I continue my progress to tinker from my code and pratice more on how to use kaboom from my blog goal only to lead to my groupmate don't need it anymore, and we are basically almost finished with our game other than the game's details like the start menu. Unless I ask more from my groupmate to ask if they need any help with coding or anything else to our game to make it more prettier. But for now I just added a sprite and try to make it that it stay still, but right now I don't know what to put to make it stay in one place, so I need to do more research on it or I ask my peer or my partner.

```js

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
#### Goals
* Try not to procastinate too much ---> kept forgetting that I needed to learn my tools most of the time
* Is ok to stress over things as it could be a glitch ---> I got pissed off and kept fixing it even tho is correct, but it said it was wrong. But I realized it was a glitch for some reason or I put the wrong code in
* Try to slowly understand how to use the computer, as I always use my ipad ---> the longer I use it the more I understand some of the shortcut on the computer
* Do a bit more research and a bit more tinker to expand my understanding ---> without much struggles so the codes doesn't stop working because of spelling and etc.

### 3/9/25
[Kaboom Notes](https://kaboomjs.com/doc/intro) after trying out the code with trails and error from the examples, I realized there was notes in the official website that I didn't know about.

Today for my progress there isn't much as my partner kinda finished what she needed to do help finish our freedom project of doing "cat foods." From my last progress I was able to make the duck move how I wanted to be and added a sprite to make it as thing to slow down the player from getting more foods.
* I think is important for me to do that as it can help benefit my partner ideas on what to add in the game

Then during that time, my teammate was communicating more to my part B group as gather idea on what to add next to our project because we are kinda starting to add more deeper stuff to our game like adding more of the art we drew to the game and other stuff we wanted to add in our game.

* Add drawing to our game = more cats to the Part B of our game where **Xue and Katee** is working
* Add some background image in our *Cat food* so that t doesn't look plain and just white from the kaboom white wallpaper = maybe our next learning log?
* Try make the menu button so that if you press on the button it will take you to the game?

But right now I'm just looking at what my peers and my part B teammates are doing since some aren't done but my partner finished her part of her code, when the time comes and she is stuck with her codes I can help her and tinker. But for right now there is none unless my partner need help or need me to do.
* I think I can try adding p5js to my kaboom, since we are learning that in class and could be possible for it to work = I'm not sure as is not part my tools but I will ask my partner if not Mr Muller
* Asking question to my teammate if they are struggling for since we are learning p5js

This is the code of my progress so far, since there isn't much I can do since my partner finished and didn't ask for anything else to be added.

```js

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
#### Goals for next time??
* Try not to procastinate too much ---> kept forgetting that I needed to learn my tools most of the time
* Is ok to stress over things as it could be a glitch ---> I got pissed off and kept fixing it even tho is correct, but it said it was wrong. But I realized it was a glitch for some reason or I put the wrong code in
* Try to slowly understand how to use the computer, as I always use my ipad ---> the longer I use it the more I understand some of the shortcut on the computer
* Do a bit more research and a bit more tinker to expand my understanding ---> without much struggles so the codes doesn't stop working because of spelling and etc.

3/23/25

[W3schools](https://www.w3schools.com/css/) was where I refresh my memory of how to do CSS again.Using the webiste from [Bootstrap](https://getbootstrap.com/docs/5.3/components/buttons/) to help me how to get started coding for buttons

My notes this time for tinkering is using my knowledge from SEP10 of making webpage because my partner told me we needed someone to make the homepage.

Today for my progress there isn't much as my partner kinda finished what she needed to do help finish our freedom project of doing "cat foods." From my last progress I was able to make the duck move how I wanted to be and added a sprite to make it as thing to slow down the player from getting more foods.
But for my tinker this time is to make the menu in the project where you click it will take you to each of our game.
* I think is important for me to do that as it can help benefit my partner ideas on what to add in the game
* More drawing towards our project?

Then during that time, my teammate was communicating more to my part B group as gather idea on what to add next to our project because we are kinda starting to add more deeper stuff to our game like adding more of the art we drew to the game and other stuff we wanted to add in our game.

* Add drawing to our game = more cats to the Part B of our game where **Xue and Katee** is working
* Add some background image in our *Cat food* so that it doesn't look plain and just white from the kaboom white wallpaper = maybe our next learning log?
* Try make the menu button so that if you press on the button it will take you to the game?
    * Which I am working on now since we finished what we needed to do --> make it look better and flexible

But right now I'm just looking at what my peers and my part B teammates are doing since some aren't done but my partner finished her part of her code, when the time comes and she is stuck with her codes I can help her and tinker. But for right now there is none unless my partner need help or need me to do. Giving me more idea on what I should put on my homepage as there could be disagreement.
* Asking question to my teammate if they are struggling for since we are learning p5js
* Using my knowledge from last year when we were making web pages for our project and looking back on my notes

This is the code that I made my menu for my teammates which is basically what we learned last year using bootstarp and our knowledge from CSS and HTML

``` css
/* CSS */
            h1 {
                margin: auto;
                padding: 30px;
                text-align: center;
                font-size: 75px;
                font-family: "Times New Roman"
            }

        </style>
```
That top of the code is for CSS only from what I got from tinkering to make my homepage look better with fonts.

``` js
        <title>Cat Collectors</title>
    </head>
    <body>
        <!-- HTML -->
         <h1>Cat Collectors</h1>
         <div class="container">
            <div class="row">
              <div class="d-grid gap-2 col-6 mx-auto">
                <button class="btn btn-primary btn-lg">Part 1</button>
                <button class="btn btn-primary btn-lg">Part 2</button>
                <button class="btn btn-primary btn-lg">Gamble</button>
              </div>
            </div>
          </div>
```
This top of my code is for the HTML of my homepage, which includes the button from the bootstrap.

#### Goals for next time??
* Try not to procastinate too much ---> kept forgetting that I needed to learn my tools most of the time
* Is ok to stress over things as it could be a glitch ---> I got pissed off and kept fixing it even tho is correct, but it said it was wrong. But I realized it was a glitch for some reason or I put the wrong code in
* Try to slowly understand how to use the computer, as I always use my ipad ---> the longer I use it the more I understand some of the shortcut on the computer
* Do a bit more research and a bit more tinker to expand my understanding ---> without much struggles so the codes doesn't stop working because of spelling and etc.

<!--
* Links you used today (websites, videos, etc)
* Things you tried, progress you made, etc
* Challenges, a-ha moments, etc
* Questions you still have
* What you're going to try next
-->
