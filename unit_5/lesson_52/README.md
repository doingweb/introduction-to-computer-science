# Lesson 5.2: Cloning Sprites

## Learning Objectives

Students will be able to...

* Demonstrate the difference between sprite and global variables
* Explain how cloning and prototyping simplify working with numerous similar sprites in the same program
* Create prototype sprites and clones of the prototype sprite
* Explain the difference between a "master" sprite and a "clone" sprite

## Materials/Preparation

* [Do Now 5.2: Star Wars Troopers ](do_now_52.md)
* [Lab 5.2 handout](lab_52.md) \(Lots of Balls\) \([Download in Word](https://github.com/TEALSK12/introduction-to-computer-science/raw/master/Unit%205%20Word/Lab%205.2%20Lots%20of%20Balls.docx)\) \([Link to PDF](https://github.com/TEALSK12/introduction-to-computer-science/raw/master/Unit%205%20PDF/Lab%205.2%20Lots%20of%20Balls.pdf)\)
  * Test out the lab on student machines before class--  cloning in SNAP! can bring the web browser to a crawl on some machines
* [Unit 5 Tips](https://github.com/doingweb/introduction-to-computer-science/tree/2be097d7d27009602b7796d96f71602e46923ac4/unit_5_tips.md)

## Pacing Guide

| Duration | Description |
| :--- | :--- |
| 5 minutes | Welcome, attendance, bell work, announcements |
| 15 minutes | Introductory discussion |
| 30 minutes | Lots of Balls lab |
| 15 minutes | Debrief and wrap-up |

## Instructor's Notes

1. Introductory discussion
   * Show students a brief video demonstrating space invaders \(YouTube: [https://youtu.be/kR2fjwr-TzA](https://youtu.be/kR2fjwr-TzA);

     Vimeo Link: [https://vimeo.com/54796819](https://vimeo.com/54796819)\)

     * Ask students to think about how we create all the “invaders”?
       * Answer with current knowledge: make one invader sprite, and copy it many times while adjusting the copies as necessary
     * Ask what might go wrong or be bad about this approach
       * If anything in an invader changes, it will need to be changed many times
       * Lots of sprites clogging up the program that are all basically doing the same thing

   * Introduce cloning as the automated way of doing the manual copying
     * Demonstrate how to create a clone using ![](../../.gitbook/assets/createacloneof.png)
     * Point out that clones inherit all aspects of the "master" or "prototype" sprite, including scripts
     * Emphasize the importance of using ![](../../.gitbook/assets/whenistartasaclone.png) to ensure clones don't duplicate out of control
2. Activity
   * Students should complete the ["Lots of Balls"](lab_52.md) lab
     * This lab will largely duplicate the code shown in the lecture part of the lesson-- that's OK
     * Students should focus on ensuring they are differentiating between "master" sprites and "clone" sprites, and that the stage is serving as the main "driver" for the program

## Accommodations/Differentiation

* Advanced students can attempt to assign properties to clones \(color, size, etc.\) so that not all clones look alike.  To do this, they will need to use a global variable to temporary hold the value that can be "claimed" by the clone.
* Struggling students should focus on just creating a single clone from the prototype and not worry about creating multiple clones.

## Forum discussion

 [Lesson 5.2: Cloning Sprites \(TEALS Discourse account required\).](http://forums.tealsk12.org/c/intro-unit-5-cloning/lesson-5-2-cloning-sprites)

