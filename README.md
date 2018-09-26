# Programming and why you should care

This is an actual presentation at my university where I get to talk about anything I like and love about.

# Resources

Presentation at https://slides.com/kelvinho/deck-1/live#/

These links should be open prior to presentation:

- Processing projects: http://157239n.com/proc/
- Manipulating dimensions: http://157239n.com/dim/

These videos should be preloaded or downloaded if your internet connection don't work:

- Miegakure trailer: https://www.youtube.com/watch?v=KhbUvoxjxIg
- How to walk through walls in the 4th dimension from Miegakure: https://www.youtube.com/watch?v=9yW--eQaA2I

# Actual presentation script to present

Oh rite, so today I'm going to talk about Programming and why should you care about it.

### Defining programming

First off, what is programming. **(press down button)** Google says it's the action or process of writing computer programs.

That's not very exciting. A rather interesting answer would be **(press down button)** "programming is a tool to manipulate information".

### What interesting ways can you do with a program

And it is powerful, very powerful in fact. Well, you may ask, **(press right button)** how powerful?

When I was in 6th grade, I wasn't very good at English. And studying in Vietnam is not much more pleasant than in America. Teachers are usually very friendly, but some aren't like that. My English teacher, she gave me some homework. To do a simple task over and over again and that is converting active sentences to passive ones. You guys couldn't believe it. The stack of paper would be like half an inch. So what I ended up doing is writing a program to do my English homework for me **(press down button)**

On the screen there is the actual program. You input an active sentence and it puts out a passive one. I later on improved it so that I only need to take a picture of the pages, feed it through the program and it will generate another page filled in with answers. And then I can just print it out and hand it to my teacher. So in the end, it took the program about 3 hours to have all of my assignments completed ready to go which I wasn't supposed to finish in 3 weeks. It feels like cheating but there isn't a rule saying "students must not create programs to do homework for them". Pretty cool rite and it kinda shows that by just manipulating information in the right way can be very helpful. **(press down button)**

In my highschool, I got involved in electronics. I design and manufacture printed circuit boards in house. The quality is not perfect, but it's usable. The picture you're seeing is an actual circuit board that I have used ferric chloride to etch. This is right before I scrap those black looking lines. So the process is really simple. First, you take a fresh board. They have 2 layers, a plastic layer below and a copper layer above. You then design your circuit, print it on a piece of paper, put it on top of your board and iron it so that it sticks. The white areas don't have ink, so the copper get dissolved away, but the black areas the copper don't dissolve in ferric chloride. The final step is just to scrap the ink out of the board and you have a working circuit board. **(press down button)**

On the left is an arduino nano. Any body know what an arduino is?

**(wait for answer and reply appropriately)**

So arduino is an Italian company that manufacture microprocessor. They manufacture a bunch of stuff, but mostly for hobbists to get into electronics. On the right there is an NRF24. The RF stands for radio frequency, that means if you have 2 of these, they can communicate with each other.

At my high school, there is a "no-cellphone policy". There would be RAs wandering outside of our classes to make sure we aren't using cellphones. The teachers are fine with it though. It's just that we'd got a really hardcore RA and wouldn't let us go. To get to us you must pass through a long corridor. My class wanted me to do something about this. They're suggesting a warning mechanism so that everyone in our class can hear the alarm right before the RA wanders outside our class. So I did just that. After 3 months all of the RAs knew about this and funny enough, I almost got in trouble with one of them. But again, it shows you what can be done by just having information at the right place at the right time can be powerful.

Not just powerful in this sense but it can also be really powerful in shaping how we think about stuff.

### Simulations and their powers

From my 9th grade till now, I have been doing simulations. Simulations of natural systems, like magnetic fields and such but also theoretical simulations to explore stuff you can't imagine with your brain. While I was doing these simulations, I really feel the expressiveness of them to describe reality, almost as real as the matrix.

My point is that (press right button) programming is a very useful tool to discover stuff. **(press down button)**

This is a combination of waves. Adding the two top waves will give you the bottom wave. From here, you can do all sorts of stuff. You can study the Fourier Transform with a simulation tool such as this and observe really interesting behavior. Now, why should you care about waves? Before I get to that, I want to show you guys something.

This is an app on my phone that is capable of producing ultrasonic sound. The frequency of sound a human can hear is from 20Hz to 20.000Hz. Anything above is ultrasonic sound. The fun thing is that the older you are, the narrower range of frequencies you can hear. A young child can listen to 20.000Hz. A teenager might be able to hear 17.000Hz. A 25 year old person might be able to hear 15.000Hz. Adults and elders might be able to hear 13.000Hz. Now, I want to do an experiment. I am going to increase the frequency of the sound coming off this cellphone gradually to 20.000Hz. Now, all of you, raise up your hand. Lower your hand when you can't hear the sound anymore.

**(doing experiment)**

So as you can see, some of you guys might not be able to hear sound at 17.000Hz. What does that mean? That means that now, you can build and program speakers which say the exam results in a way that the professor can not hear it. I haven't done it yet, but still, it's an idea for anyone who want to cheat :))

I'm about to show you a few pictures of a few simulations that can get a little bit technical in detail so you don't need to know the details at all. **(press down button)**

This is an image of an electric field with 3 charged particles, 2 positive and 1 negative. **(press down button)**

These are images of what is known as a phased array. It's basically just a lot of transmitters arranged in a line and by delaying the transmitting signal just right, it can create a powerful directional energy wave. **(press down button)**

I've also done simulations in chaos theory. This is a Henon attractor. **(press down button)**

This is a plot of the logistic map. **(press down button)**

This is another plot of the logistic map and on the right there is a cobweb plot of the logistic map. **(press down button)**

This is the Lorenz attractor, which is the preliminary model that Lorenz used to predict the weather while he's investigating how chaotic systems work. **(press down button)**

These are Julia sets, which is a way to produce infinitely many fractals and study their properties. **(press down button)**

There are more fractals than just the Julia set. **(press down button)**

And 3D stuff. On the left is a simple cube and on the right is a continuous surface that you can rotate around in 3D space. I know that you guys have played lots of 3D games but to actually code the rotations and figure out the math yourself can be difficult.

But when you understand how 3D space works, you can do a lot of stuff with it. **(press down button)** This is a project aim to scan a physical object by just using cameras. On the left is the simulated object. If you can see there're 4 squares. The first simulates an actual object with its structures inside. The importance for us here is to be able to discern the object from the background and the second square is depicting what the camera is seeing. The bottom left square contains the scanned object in which you have the model on your computer ready to be exported to other applications. On the right is the actual scanning outcomes. It didn't do very well here because honestly, things in the real world don't behave as you might expected. Fun fact though, this is the project I wrote for my thesis in my 11th grade and it has been very exciting to see how it actually scans the object.

I can do a demo of this now. You guys want a demo? :D

**(do demo)**

So the surprise thing is that once you understand rotations, how do you view stuff in 3D, then it's possible for you to code something in higher dimensions.

A while back I have written a blog post here about those 4D concepts. **(navigate to the blog post about dimensions)** Here it is, scrolling down the bottom and you can see how the 4 dimensional cube would look like in reality. You should be able to see 2 warped cubes, one black and one red. They are linked by 4 blue segments. Just as the faces inside a 3D cube are distorted when you look at it when it's turning, the cubes inside a 4D cube are also distorted as you see here. **(press down button)**

This is Miegakure, a 4D game, in which you must navigate around this 4 dimensional space to complete certain tasks. Here's the trailer for the game. **(play video)** **(press down button)**

And this is the developer trying to explain how you can walk through walls in the 4th dimension. **(play video)**

So I think you can all agree with me that this shit is very exciting. This is exactly the power of programming to discover something new comes in to play: you apply some ideas from what you know and you can build up that idea into something you can't even imagine. **(press right button)**

### Wrapping up

Wrapping up. Programming enables you to manipulate information in smart ways, including solving our problems and discover something new about our world. **(press right button)**

### Questions

Okay, so do you guys have any questions? If not then thank you for listening and have a nice day :D
