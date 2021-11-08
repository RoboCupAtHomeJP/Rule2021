# Basic Functionalities
The basic performance of the robot is tested in this task, such as carrying objects, avoiding obstacles, and interacting with humans.

## Notice
* Please watch this [video](https://youtu.be/8OoxJS_4YFs) to help your understanding of the task.
* A rule of the task will be based on the "[basic functionalities](http://docs.google.com/viewer?a=v&pid=sites&srcid=cm9ib2N1cGF0aG9tZS5vcmd8cm9ib2N1cC1ob21lfGd4OjEzYWQ0MzQwYjdhYmQyODM)" of RoboCup2014 and customized rules.

## Focuses
1. Mobile Manipulation
1. Obstacle avoidance and path planning
1. voice recognition

## Tasks
All objects used in the atomic test are announced in advance. The test consists of the following three tasks.

### 1.Pick and Place
The robot moves to a location where two objects are located. One object is "known" and another is "unknown". The robot grabs one object and places it at the specified location. If the robot grabs a "known" object, it moves the object to a predetermined location of the object category. For example, "If the robot grabs a Coke, the robot put it on the kitchen table". If the robot grabs an "unknown" object, the robot throws it into the trash can (or a designated location).

### 2.Avoid That
The robot moves to the location indicated in advance. There are two types of obstacles. The first obstacle is an avoidable object such as a chair, which is placed while the robot is on the move. The robot must move so that it does not come into contact with obstacles. The second obstacle blocks the path between rooms (such as a "door closing") and makes it impossible to avoid, requiring the robot to re-plan its path and move to another room.

The task proceeds in the following order. (1) The robot moves from Room 1 (where Pick and Place is performed) to Room 2 (where What Did You Say? is performed). (2) The path between Room 1 and Room 2 is blocked, so the robot searches for another path. (3) While moving to the other path, an avoidable obstacle is placed in the middle of room 1, so the robot re-plans and moves to the other path. (4) The robot moves to room 2.

### 3.What Did You Say?
The robot enters the room and looks for a questioner, moves close to him/her, and notifies him/her by voice. If the robot does not find the questioner, the robot can ask the questioner to come in front of the robot. In this case, the score of "Found the questioner" is not given. The robot then answers three questions from the questioner. The questions are randomly selected from ten previously announced questions. The following are examples of the questions.

* What is the capital of Germany?
* What is the heaviest animal in the world?

## Additional Rules and Remarks
* When the robot finishes the tasks or exceeds the time limit, it must move to the next task location. **The robot should notify clearly by voice or other means that the robot has moved to the next location. (If the referee does not understand the robot's notification, there may be no time bonus)**
* The robot must prepare within 2 minutes of the arrival for the next task. The robot should clearly notify by voice or other means that the robot is ready for the next task.
* The robots will be tested one by one.
* For each section, a time bonus will be given according to the number of seconds remaining from the three minutes.
  * Refer to the score sheet for the timing of measuring the remaining time.
  * Decimal points are rounded down.
* One task is tested in 3 minutes. It is not possible to restart (The robot can perform only once for one task). Additional points will be given if the robot prepares for the next task autonomously, instead of being pushed by human or controlled by joysticks or keyboards.

## OC Instructions
Please announce the following before the competition starts.

* The 5 known objects
* The location of the start point of the three tests
* The locations of 5 objects for "Pick and Place"
* The location of trash cans for "Pick and Place"
* 10 questions for "What Did You Say"



## Score Sheet
The maximum time for each task is 3 minutes.

|Action　　　　　　　　　　　　　　　|Score　　　|
|:---------------------------------------|-:|
|||
|***Pick and Place:***||
|  Object picked up.                 |50|
|  Object placed in appropriate location.    |50|
| Time bonus: The time from the opening of the door until the robot releases the object. |Remaining time (sec)/10|
|||
|***Avoid That:***||
|  Autonomously prepared to start atomic test.        |20|
|  Avoided obstacle.                              |30|
|  Detected un-avoidable obstacle and re-planned route.  |50|
| Time bonus: Time from the completion of moving to this section start location until the robot autonomously moves to room 2. |Remaining time (sec)/10|
|||
|***What Did You Say?:***||
|  Autonomously prepared to start atomic test.      |20|
|  Person found.                                  |30|
|  Question recognized and answered.              |3x10|
|  Autonomously leaving the arena after finishing the atomic test.   |20|
| Time bonus: The time from the completion of moving to this section start location until the robot exits the arena. |Remaining time (sec)/10|
|||
|***Special penaltie & bonuses:***  ||
|  Not attending                                        |-50|
|  Outstanding performance                            |20|
|||
|Total (excluding penalties and bonuses)           |300|
