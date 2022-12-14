# Probability Calculator

## Synopsis
This project compares two objects to display probability, dice and/or cards

## Motivation
I created this project so that it could aid myself in game creation

## How to Run
Probability and Probability test are needed to run the program, probProj is an older project
from an earlier class. It is included int the file but is not needed to run the program
intended for this submission.
[Here is the program running](Probability_Calculator_Running.png)

## Code Example
Here is a small sample of code that I am proud of

      		Toggle identify1 = group.getSelectedToggle();
			int input1 = Integer.valueOf(((Node) identify1).getId());
			
			Toggle identify2 = group2.getSelectedToggle();
			int input2 = Integer.valueOf(((Node) identify2).getId());
			
I am proud of this code because it implements getId() which is
crucial to allow my program to run as it does. Referencing those
Id numbers as integers allowed me to use older code and iterate
upon it. It saved me lots of time in the long run.

## Tests
Most of my methods are within the Probability file. JUnit4 can be
used to test these out.

## Contributors
I, John, was the sole creator of this Project
