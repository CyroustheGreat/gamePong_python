i need a window. notice s is capitalized. 
i m going to give it a title
i m going to call that pong by @... it's my twitter handle. 
and do feel free to leave comments 
i do keep close eye on things
an if you having trouble, let me now 
and i want to change background color of the window to black classic. 
and  iwant to change the size of the window. 
i want the width to be 800
and i want the height to be 600 pixels

i m gonna do something called wind tracer
and this one a little bit hard to explain but basically what that does is it actually stops the window from updating. and so we have to manually update it. what this lets us do is basically speed up our games quite a bit
if we didn't do that, things would run much, much slower. so every game meet needs something called a main game loop. and this is where basically all the meat and potatoes of your game goes to. 
so we're gonna make a loop while true
and then leave four spaces there
you can use tabs, but spaces are recommended. 
whatever you use make sure that you are consistent. 
snd what that does is very time the loop runs, it updates the screen okay, just a  quick note this program is written for beginners, so i'm nor really using object oriented programming, i'm not really using classes, except as it relates to the turtle module. this is basically a really straight forward, old school style of programming methodology. 
see how it goes, and what we should have is we have our title.
it is 800 wide by 600 tall. 00 is at the center. so plus 300 minus 300. plus 400 and minus 400. Rememebr those numbers because they'll come in handy in our next few tutorials. So that's all for this particular lesson. 
I just want to get you started. We move on to lessen two. we'' add our paddle on the left paddle on the right and our ball. 
in this part of tutorial, we're going to add our paddles to teh screen and we're foing to add the ball to the screen as well. so let's get started with that. Basically what we have in Pong is we have pat, I'm gonna call it paddle a, we have paddle B. and we have a ball. I mentioned earlier, in the previous video, we are using the turtule module to, you know, add our graphic, it works for basic games, a lot of people use PI game, which is great. But for simple games, this is probably an easier way to get started. so everything in our game needs a name, si i'm ging to call it paddle ng very original.an it's actually gonna be turtle, what's known as a turtle object. so to do that, it's turtle dot capital turtle. Notice the capitalization. because that is our module name, capital T, because that is a class name. Now, as this tutorial is aimed at beginners, i'm not going to talk about classes, i'm not writing in object oriented style, i'm just writing it in, you know, functional style. Although there some objects kind of patterns here, you''ll see. But for beginners, don't worry about that stuff for now. so then what i want to do is paddle a 
i nedd to the speed. Now this mot the speed that the paddle moves on the screen. This is the speed of animation. this is just something we need to do for the turtle module. and what this does it it sets the speed to the maximum posible speed, otherwise, things would be really slow. We want to give our paddle a shape. and there are a few built in shape. and we are going to use square in this case. Okay, there's circle, circle square and a few others. 
we're gonna give our paddle a color. we're gonna call it white, because what pong looks like. to do basically something called pin up. Turtles, by definition, what they do is they drew a line as they're moving. we don't need to draw lines, because that's not what this program does. so we do the pin up, and i want my paddle to start at minus 350. and zero and vertically centered in the screen. so in our game, 00 is in the middle, minus 350 plus 350. So i'm gonna go ahead and run that and see what it looks like so far. so this is our left pattern. Now you know, you've played pong, you've seen the demo pattern from 
the first video. Clearly. it's not the right size. So what we can do in our program this. now just for your information, by default, the shape is 20 pixels by 20, so it's 20 pixels wide by 20 pixles high. so what we're going to do is we're ging to stretch the shape. so we use the shape size method, you can see i'm using visual studio codes, very good program, you don't want a Mac, and it tells you know, what tou can do stretch with stretch length. so what i want to do is I want to stretch the width by five sets to be five times 20. so that'll ,make it 100 tall. Okay, so you see now we've got a paddle over here, 20 pixeles wide by 20 pixel high. i'm kind of lazy guy. so i'm just gonna copy this. so what i always recommend if something's similar, similar styles are similar, you know, functions, you know, get it working right once and copy it. paste and then make the necessary changes. so now that we've done that, we just need to change that to B. so if you keep consistent names, it will really help your programming. and in this case, we want it to go on the right side of the screen. that's gonna be plus 350. so i m gonna test it.
testing your program is very important at each stage, a lot of beginners i don't know why they insist on typing the whole program in and then trying to test it. 
and the lasting we need is to be our ball, \
so im' gonna go ahead and copy this becuse this is the same thing
i don't need it streched i want  to keep it the original size and i want  to start in the middle of the screen, and i'm gonna to call it ball istead of paddle
so you see once, if you do like it this method, if you get everything working correctly there's
there's no error and you tested it, 
i'm gonan run it one more time, 
no you see we've got our left paddle, 
we've got our righr paddle, and our ball in the center, so we're off a  good start, 
in this lesson we're gonna learn how to move the paddles using the keyboard. 
so what we need to do is creating some functions. and if you haven't ever used the function before, a function is basically kine od a peace of the program that does a something that's been defined for it. So in this case, we  want to move paddle a and up and down. so to use function you first need to define a function. and i'm gonna call this first function paddle a up. if you recall, in the last video, we talked about doing one function at a time one piece at a time, getting working perfectly. and then you can copy and make the necessary changes. so that's what we're gonna do here. so to move a paddle up what i need to do is i need to know the cyrrent y coordinate. so what i'm gonna do gonna say y equals paddlea.ycore()
so i'll leave it the way it is. so now we having a function doesn't actually do anything until we call the function. 
watch what i do here

so let me explain what that does so this line here, it tells the program to listen 
for keyboard input. The line here says, when the user presses W, notice that lowercase w 
so if you have caps lock on, it won't work,. Call the function, paddle a up, here's our. 
here's our function paddle a up. says get the y coordinate, add 20 to the y coordinate, and actually set th ey of the paddle to the new y coordinate. 

ok so let's test that and se what happens. so im going to hit the w key. so you can see how it is moving up. so we actually moved off the screen. 

what can i do is i can copy that 
and i m gonna change this to paddle a down

so instead of adding 20, i'm gonnad to substract 20. 

and i need to key binding for that as well. 
and in this case i'm gonna use s key. 
you can use whatever key you want. 
so once again, i've done one thing, i've changed it, now i'm gonna taest it. 
ok so everything's working exactly as expected. so what i'm gonna do is now i've got 
both of those working i'm gonna copy it, i'm gonna do paddle b, that'll pannel b

for the paddle be i'm gonna use arrow keys. i'm gonna use up this capitalize and down is the down arrow. so agin, i made a couple of changes 
i'm gonna test my code

w and s on the left up and down on  the right and voila, there you have it, 

this is really kind of the meat and the central kind of part of the program. 

this where we actually get the ball to move. 
we  need to get it to bounce off the top and the bottom and bounce off the paddles. 

but the ball does'not yet
what i wanna do with the ball is i want to seperate the ball's movement into two parts
an x movement and a y movement. so we're going to call that i'm going to say ball dot d x 
d means delta or change. You can even call it xp or whatever you want byt dx works very very well. 

so you might have to play with the numbers here to get it to where you feel the game should be. so dx and dy equals two. so what that means every time our ball moves, it moves by two pixels. So since x is positive, it's gonna move to the right to and since y is positive, it's going to move up to 
so it'd be kind of moving up and diagonally. okay, so to get that to actually happen, we have to go inside the main game loop. an in here, i'm gonna say move the ball. so
what we need to do is ball dot set x. and what we want is the current x coordinate. 

combining what i did up here into one line plus ball .dx Okay, so the ball starts at 00. so the first time through this loop. it's going to an x time the loop is gonna go to to two so depending on your computer speed it could just fly off the screen or 
it couldir ir it can go a little bit slower so again /
you have to play around with that a little bit. so that when i say 
ball.sety(ball.ycor + ball.dy)

so i'm ganna test and see what happen. yo see some red lines here. i think there's gonnabe maybe a problem. so i'm gonna run that and explain why it's not gona work.
Okay. you see here i've got an error and this is something again, beginners, i 

