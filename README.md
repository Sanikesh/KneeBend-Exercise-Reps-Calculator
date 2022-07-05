# KneeBend-Exercise-Reps-Calculator
This is a robust algorithm to calculate successful rep count for knee bend exercise (using mediapipe pose model)

The conditions for the counting is as follows:

1. Add a holding timer limit of 8 sec
2. Include feedback logic in your code, which should be triggered only when a person fails to stay in holding position till 8 sec.Feedback message - “Keep your knee bent”.

Exercise Description:

● Leg should be bent to start timer
● Slight inward bend is enough to start the timer. ( <140 deg)
● After a successful rep, the person has to stretch his/her leg straight.
● No restriction for back angle
● Consider leg closer to camera as exercised leg
