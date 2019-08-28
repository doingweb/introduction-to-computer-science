# Lesson 3.1: Abstraction and Friends

## Student Objectives

Students will be able to...

* Define the following terms in a computer science context:
  * abstraction
  * detail removal
  * generalization
  * procedural decomposition
* Describe how utilizing procedural decomposition can improve the readability and maintainability of algorithms and/or code
* Recognize opportunities to improve algorithms by abstracting or generalizing parts into subprocedures

## Materials/Preparation

* [Unit 3 Tips](https://github.com/doingweb/introduction-to-computer-science/tree/2be097d7d27009602b7796d96f71602e46923ac4/unit_3_tips.md)
* Student algorithms from lesson 0.2
  * If algorithms are not still available, either provide students with a canonical sample or have them recreate their algorithms as the first part of this lesson
* Paper/writing implements for each group of students

## Pacing Guide

| Duration | Description |
| :--- | :--- |
| 5 minutes | Welcome, attendance, bell work, announcements |
| 10 minutes | Introduce terminology, introduce first activity |
| 10 minutes | Students rewrite PB&J algorithms |
| 10 minutes | Review rewrites |
| 10 minutes | Students write lasagna algorithms |
| 10 minutes | Review new algorithms, debrief, wrap-up |

## Instructor's Notes

1. Introductory discussion
   * Ask students to review \(or recreate\) their algorithms for preparing a peanut butter and jelly sandwich \(from lesson 0.2\)
   * Point out that some parts of the algorithm are similar or redundant
     * e.g. spreading peanut butter repeatedly until enough is on the bread; spreading peanut butter and jelly are basically the same operation
   * Define and discuss the following terms:
     * _abstraction: removing the specifics that are not relevant in a given context_
       * e.g. being able to drive a car without understanding how an internal combustion engine works
     * _detail removal: reducing the complexity of an algorithm or process by focusing on the important parts_
       * e.g. focusing simply on falling in the platform game instead of trying to create true parabolic motion
     * _generalization: combining a group of related concepts or processes into a single category_
       * e.g. spreading any condiment or ingredient onto a slice of bread \(butter, jam, peanut butter, mayo, etc.\)
     * _procedural decomposition: breaking a problem down into smaller subtasks, usually to increase readability and/or maintainability, often by applying one of the above concepts_
2. Activity, part 1
   * Instruct students to review their PB&J algorithms looking for opportunities for abstraction and procedural decomposition and rewrite the algorithms to improve readability
     * Possible opportunities include: abstracting spreading peanut butter and jelly, looping when spreading to get enough of the ingredient, removing details with regard to opening packages, etc.
   * Break students into groups and encourage students to make their new algorithms as concise as possible while still being easy to understand
3. Review
   * Ask one or two groups to share their rewritten algorithms, pointing out the places where they abstracted or generalized
     * If possible, choose groups with good approaches while circulating during the activity
   * Ask other groups to point out any missed opportunities for or overuses of abstraction
   * Discuss advantages to writing algorithms using abstraction
     * More concise code, more structure, easier to follow, ability to ignore details until relevant
4. Activity, part 2
   * Have students return to their groups and develop an algorithm for constructing and cooking a food that invloves layers \(ex. [lasagna](https://en.wikipedia.org/wiki/Lasagne)\).  
     * Encourage students to be aware of opportunities for abstraction and/or procedural decomposition when writing their algorithms
     * As much as possible, students should abstract while writing the algorithm rather than writing a complete algorithm and then making edits
   * Emphasize the balance between conciseness and readability
     * Too much abstraction or generalization can make the algorithm hard to understand \(e.g. end up with a "do stuff" procedure\)
5. Debrief
   * Ask at least two new groups to share their lasagna algorithms
     * Ask students not in either group to compare and contrast the presented algorithms
     * Point out, or ask students to point out, uses of, missed opportunities for, and overuses of abstraction
   * Ask students how the skills learned in this lesson can be applied to programming
     * Drive students to realize that code is simply an application of algorithms
     * Tease the need for custom blocks \(procedures\)

## BJC Lecture Suggestions

### Background Information for Instructors

* BJC Video Suggestion: [BJC Lecture 1: Abstraction](https://www.youtube.com/watch?v=Dxw9cIbzaLk)
  * Abstraction: 11:40-15:40
  * Generalization: 15:50-20:00

## Accommodation/Differentiation

* A lasagna is used in this activity because it has many similar, repeated steps with different ingredients \(layer of noodles, layer of sauce, layer of cheese, etc.\).  If students are not familiar with lasagna, another recipe with similar characteristics can be substituted.
  * A club sandwich \(or other "multi-decker" sandwich\) can work, as can baking recipes \(if the various dry ingredients that need to be mixed are treated separately\)
* As in [Lesson 0.2](../unit_0/lesson_02.md), students may go overboard with the decomposition in the second part of the activity.  Encourage these students to think about the balance between brevity and usability, and remind them that the goal is not to write the _shortest_ algorithm possible, but the _clearest_ algorithm they can.

## Forum discussion

 [Lesson 3.1: Abstraction and Friends \(TEALS Discourse account required\).](http://forums.tealsk12.org/c/intro-unit-3-variables-and-customization/lesson-3-1-abstraction-and-friends)

