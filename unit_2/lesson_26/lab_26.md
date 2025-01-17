# Lab 2.6: What Goes Up...

In this lab, you will use everything you've learned about loops and conditionals to construct a simple model for gravity.

## Before You Start

Go to the starter project at [https://aka.ms/intro-lab2-6](https://aka.ms/intro-lab2-6). Log into SNAP and save your own copy of the project by choosing “Save as” from the file menu. Be sure to click the “Share” button in the Save dialog box. Highlight the URL in the address bar and copy it.

## Channeling Newton

Write a script for the Dino sprite so that:

1. \(1 point\) When the green flag is clicked.
2. \(1 point\) Dino goes to the top of the stage.
3. \(2 points\) Dino falls towards the bottom of the stage in a forever loop.
4. \(3 points\) But when Dino hits the ground \(in other words, if Dino is touching the ground\), it should stop falling.  You can use the fact that the ground is all the same color green, along with the “touching color” block.  You can change the color by clicking on the color, then clicking on anything that has the desired color.

## ...Must Come Down

1. \(2 points\) Modify your code so that when the green flag is clicked, Dino will not only move to the top of the stage, it will move to a random x-coordinate on the stage \(between -240 and 240\).  Use the “pick random” block:
2. \(2 points\) Modify your code so that the Dino sprite not only stops falling when it touches the ground, but it also stops falling if it is touching the Platform sprite.  In other words, it should always fall unless it is touching the ground OR it is touching the Platform sprite.  

## Jump Up

1. \(2 points\) Modify your code so that when the spacebar is pressed, Dino will jump up.  Have Dino jump by using a repeat loop with a block in it that will move Dino up.  Dino will have to move up faster than you think since it will be fighting the forever loop that causes it to always go down.

## Challenge!

1. \(2 points\) Dino jumps any time the spacebar is pressed, even if it is in midair.  How do you make it so Dino can only jump while on the ground or the platform?
2. \(2 points\) Can you add code so Dino will move right and left with the arrow keys?
3. \(5 points\) In reality, gravity pulls down with constant acceleration, not constant speed.  How can you change your code to model gravity as a constant acceleration instead of a constant speed?  

