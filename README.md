# MHR-BEST-2019-Programming

## Welcome to the MHR's Github Repo for BEST 2019 Programming!
Below we will be going over how our programming works. 

## Software we are using:
We are using a program called RobotC. We are using RobotC because of the reliability and support for using the Vex Cortex (aka brain).

## Top lines of the code:
The pragma. What is this? It is initializing the motors and servos. Also giving us important information for contrlling them. 
The first part of controlling these motors and or servos is getting power to them. As you can see there is a piece of code that says port followed by a number. This coresponds with the connector on the Vex Cortex. Next we give these motors and servos a name so they can be referenced in the code below. Last thing of main interest is the option to reverse the motor or servo this makes code readability nice and better for the programmer not having to remember to add a negative infront of values. 

All of this code is generated by RobotC's configuration wizard.

## Variables:
Below the pragma we have a section for entering variables that can be referenced in the code. We write variables for all the joysticks on our controller and set their initial value to 0. We also make a variable named "thresh" this is a threshold for the controller deadzone making driving smoother and easier. 

## Task drive (coming soon): 
