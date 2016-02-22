# Week 3 Project Mailbox

<i>CodePath Assignment</i>

This assignments task was to recreate some of the gestures of the Mailbox app.

Time spent: 8 hours in total

<b>Completed user stories:</b>

- User can swipe left or right on first email to do action:
 - Archive, Delete, List, Later
- User can swipe from left edge of screen to reveal menu and close it. (The view will snap either to original or right position depending on the direction swiping)


Notes:

Implemented an extra UIPanGestureRecognizer to be able to move the mainView back to its original position. Because once triggered from the UIScreenEdgePanGestureRecognizer I was not able to close the menu.


<b>Walkthrough of all user stories:</b>

![Image of Carousel_additional](http://imgur.com/DOWab0X.gif)
