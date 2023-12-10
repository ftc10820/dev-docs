# dev-docs
*FTC developer documentation, tips and tricks*

This document is intended to help FTC devs get started and/or unstuck.

## The Basics
At a minimum, you will need:
1. Android Studio https://developer.android.com/
  1. If on a Mac, Android Debug Bridge (ADB)
  2. If on Windows, REV Hardware Client https://docs.revrobotics.com/rev-hardware-client/gs/install
2. a REV Control Hub
3. a driver station


Your robot project should be a clone of:
https://github.com/FIRST-Tech-Challenge/FtcRobotController

Your code goes in TeamCode/src/main/java/org/firstinspires/ftc/teamcode.

The driver station allows the user to choose an OpMode to run. Think of an OpMode as a program. OpModes are subclassed from OpMode or LinearOpMode. The latter provides helper methods to aid in managing your control loop.

There are many examples in FtcRobotController/src/main/java/org/firstinspires/ftc/robotcontroller to help you get started.

# 3rd Party Libraries
The base FTC project includes a wide variety of support for your robot code. If you want to use additional libraries such as road runner, add references to TeamCode/build.gradle according to the 3rd party library's instructions.
