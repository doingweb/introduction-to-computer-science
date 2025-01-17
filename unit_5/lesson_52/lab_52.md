# Lab 5.2: Lots of Balls

In this lab, you will use cloning to create many identical sprites without having to reprogram each one individually.

## Part 1 - Follow the bouncing sprites

1. Create a SNAP program that contains a single sprite, choose from available costumes \(i.e. basketballs, hearts, stars, balloons, Alonzo, doves\). When the green flag is clicked, the sprite should go to the center of the stage, pick a random direction, and start moving in the chosen direction. If the sprite hits a wall, it should bounce off and keep moving.
2. Modify the program to be controlled by the stage rather than by the sprite itself. When the spacebar is pressed, the stage should broadcast a message that triggers the sprite's movement. Pressing the spacebar again should restart the sprite's movement, including a new speed and new direction.
3. What would you need to do to add a second bouncing sprite \(that behaved in the same way\) to the program? What about 10 sprites? 100 sprites? What would happen if you wanted to change the speed of all the bouncing sprites in the program after you had created 100?

## Part 2 - Clones!

1. Modify your program so that, instead of a single sprite restarting each time the spacebar is pressed, a new clone of that sprite is created. You'll want to use the ![](../../.gitbook/assets/createacloneof.png) and ![](../../.gitbook/assets/whenistartasaclone.png) blocks in place of ![](../../.gitbook/assets/broadcast.png) and ![](../../.gitbook/assets/whenireceive.png).
2. What happens to the original \("master"\) sprite each time the spacebar is pressed? Does that seem useful? What role should the original sprite play now that we're cloning?
3. Modify the program so that the original \("master"\) sprite hides at the beginning of the program and each new sprite appears when it is created.
4. BONUS: Assign each clone a different value for some properties, such as speed, color, or size. Try controlling these values from the master sprite rather than having each clone choose its own.

## Grading Scheme/Rubric

| **Lab 5.2 Criteria** |  |
| :--- | :--- |
| 1.1 One bouncing sprite | 0.5 points |
| 1.2 Sprite controlled by stage | 0.5 points |
| 2.1 Clones created by stage | 0.5 points |
| 2.3 Hide master sprite | 0.5 points |
| 2.4 Bonus: Sprites have different properties | 0.5 points |
| **PROJECT TOTAL** | **2.5 points** |

