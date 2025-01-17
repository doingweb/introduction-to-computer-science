# Lesson 4.5: Sequential Search

## Learning Objectives

Students will be able to...

* Explain the sequential search algorithm
* Implement several variations of sequential search

## Materials/Preparation

* [Do Now 4.5: List Tracing ](do_now_45.md)
* [Lab 4.5 handout \(It's Around Here Somewhere\)](lab_45.md) \([Download in Word](https://github.com/TEALSK12/introduction-to-computer-science/raw/master/Unit%204%20Word/Lab%204.5%20Its%20Around%20Here%20Somewhere.docx)\) \([Link to PDF](https://github.com/TEALSK12/introduction-to-computer-science/raw/master/Unit%204%20PDF/Lab%204.5%20Its%20Around%20Here%20Somewhere.pdf)\)
* [Unit 4 Tips](https://github.com/doingweb/introduction-to-computer-science/tree/2be097d7d27009602b7796d96f71602e46923ac4/unit_4_tips.md)

## Pacing Guide

| Duration | Description |
| :--- | :--- |
| 5 minutes | Welcome, attendance, bell work, announcements |
| 15 minutes | Lecture and demonstration |
| 25 minutes | It's Around Here Somewhere Activity |
| 10 minutes | Debrief and wrap-up |

## Instructor's Notes

* Lecture
  * Ask students to consider how to determine if a particular person is in the room or not
    * At first, you will likely get answers like "call out the person's name" or "look around."  Press the students to come up with a method that will always work, including when the person is not present.  If necessary, ask them to pretend they are a computer.
    * Point out that solutions like "look around" are too high-level, and in reality, there is a lot more going on \(such as looking at each person individually\).
    * Guide students to the process of checking if each person is the one they are seeking, in some deterministic order, until they have either found the person or checked everyone.  Emphasize that the absence of the person is only confirmed when everyone has been checked, but that the presence is known as soon as the person is found.
    * Get students to recognize that this process is a traversal of the people in the room.
  * Explain that the process of traversing a list looking for a particular item is known as a "sequential search."
    * Ask students to think about the efficiency of this algorithm.  Emphasize best, worst, and average cases \(both what those cases are and how long they take\).
      * You need not get into specific runtimes or big-O notation, but students should have a basic understanding of the fact that the speed of the search is dependent on the size of the list.
    * If students seem prepared, ask them to speculate under what circumstances you might be able to do better \(eventually leading to binary search\).
  * Show the code for a basic sequential search:   


    ![basic sequential search](../../.gitbook/assets/basicsequentialsearch.jpg)

    * Point out that this code is another variation of a traversal.
    * Emphasize that this is only one variant of sequential search.  The specifics of what to report can vary \(true/false, index in list, item itself, etc.\).
* Activity
  * Students should complete the "It's Around Here Somewhere" activity individually or in pairs.
    * Each part asks students to write a slightly different sequential search.  In all cases, make sure students are clear on what they should be reporting, both when the desired item is found and when it is not.
* Debrief
  * Ask one or two students to provide their solutions to each part
    * Point out the similarities in each solution, emphasizing that the algorithm remains constant and only the value that is reported changes.

## Accommodations/Differentiation

* Advanced students can be encouraged to explore more efficient searching algorithms \(specifically binary search\).
* Struggling students should focus on just parts 1.1 and/or 2.1 of the lab.  Remind these students that they are starting with a traversal and simply changing what happens to each item.

## Forum discussion

 [Lesson 4.5: Sequential Search \(TEALS Discourse account required\).](http://forums.tealsk12.org/c/intro-unit-4-lists/lesson-4-5-sequential-search)

