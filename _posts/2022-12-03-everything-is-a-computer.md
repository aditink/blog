---
layout: post
title:  "Everything is a Computer"
date:   2022-08-01 07:47:00 -0400
categories: unconventional computing
---

The key insight behind the field of unconventional computing is that many systems in nature compute, often in fundamentally different ways.
Computers today compute in the binary model, where everything is encoded as 1's and 0's, and all computation consists of manipulating these 0's and 1's per fixed operations.
But some problems can be solved better with other models of computation (quantum computing being a prime example).

I see a computer as something that takes in an input, and then, following a set of rules, produces an output.
Historically we ended up doing computers with switches that could represent two states (usually represented as 1 for on and 0 for off).
Our physical realization of this two state (_binary_) model has kept improving.
We started using transistors with high (1) and low (0) voltage back in the 50's.
And as Moore's law famously says, with every decade we have gotten so much better at making transistors that we fit twice the number on a chip.
But while the binary computation model has served us quite well, it has some fundamental limitations, that building faster and better computers can't overcome.
Binary computers are bad at factorizing prime numbers for example, which is the basis of modern encryption.
Alice cannot pretend to be you because her (binary) computer simply cannot do the kind of computation that would need.
But there are other ways to compute, that can solve problems that are hard to binary computers, and let Alice pretend to be you.

To see how problems that are hard for a binary computer could be easy for a different model of computation, consider the raindrop that just landed at the top of your window pane.
If I asked you to predict precisely where it would end up after tracing its desultory path to the bottom of the pane, you would probably have a hard time.
You might start by pulling up the rules of fluid dynamics, and code them into a physics simulator.
You would probably measure the wind speed, and the tiny specks of dust on your window and write those in.
Even so, your computer simulation would have small inaccuracies, resulting from its inability to handle the infinite precision of nature in a finite sequence of 1's and 0's.
The tiny mistakes would keep adding up as the simulator traced out the droplet's path.
You would end up with an incorrect result, different from where the droplet actually lands.
A much better way to figure out where droplets on windows land is to put the droplet on the window and see where it lands.
The system of the droplet and the window is a computer.
Its input is the initial position of the droplet and environmental conditions, and its output is the end position of the droplet.
I imagine there exists no more precise computer to predict the behavior of a droplet trickling down a window.
It's not just droplets that binary computers are bad at: we haven't quite figured out many impactful questions, like predicting the weather, and simulating the climate.

Now, the problem with building droplet-computers is that they do not _generalize_.
They don't form a good unit of computation that might solve interesting problems well.
But there are other models of computation that do.
Quantum computers are a popular example.
They leverage the complexity of how matter behaves at the quantum scale to compute in a superposition of 0's and 1's.
You can see this as running multiple binary computations at once.
Using Shor's algorithm, a quantum computer factors prime numbers quickly (and provide exponential acceleration vs. a binary computer).
This is why, when they become a reality, we would have to redesign encryption, since anyone with a quantum computer could compute how to pretend to be you.
The complexity of quantum mechanics can be wrapped into a fundamental computational unit that solves the problem of (prime factor based) decryption.

What other elements of nature could we use, that are like quantum computers?
That is what the field of unconventional computing seeks to answer.
People are trying to use, for example, the complexity of how light behaves (Boson Sampling).
In general, a candidate computational model should have the following properties:
- It should generalize well to solve interesting problems. Think quantum computers, rather than rain drops.
- It should solve problems that are hard for existing computers. A trinary computer, that uses three states rather than two, is hardly worth the effort of engineering because it isn't able to solve problems much better than binary computers.
- It should be physically realizable. Humanity has a track record, though, of displaying the grit and ingenuity to engineer machines of seemingly impossible complexity, so this point does not eliminate much!

I see unconventional computing as diversifying the raw material we can solve problems with.
Lego blocks are like binary computers.
We know how to make and use them really well.
They generalize beautifully to solve a menagerie of problems.
The same lego blocks work great regardless of whether you're building a model spaceship or a doll house.
And yet, if you are looking to build something like the statue of liberty, you probably want different sculpting material.
Metal's superiority in building the statue does not mean that it is the best sculpting material for every project, however, much like quantum computers aren't great at some stuff that binary computers do really well.
But as the choices of material grow, so do the possibilities that humans can realize.


Disclaimer: This is a first draft attempt at presenting the idea of unconventional computing to a general audience based off my general knowledge. It is not well researched an may have inaccuracies that I will (hopefully) come back and fix at some point, adding in links and citations.