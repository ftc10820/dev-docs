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

## Compile, Deploy and Run
### Compile
To compile your code, use the Build > Rebuild Project menu item. This will pull in any additional project references automatically.

### Deploy
You must be connected to the Control Hub to deploy your code to the robot. You can use a USB cable with the Control Hub's USB-C port to connect your computer to the Control Hub.

The Control Hub must be set up to allow deployment over wi-fi:
https://docs.revrobotics.com/duo-control/programming/android-studio-using-wireless-adb

To deploy code after building, click the green arrow next to "Team Code" in the center top of the Android Studio window.

### Run
Use the driver station to connect to the robot's Control Hub. After a connection has been established, select the OpMode and press run.

## 3rd Party Libraries
The base FTC project includes a wide variety of support for your robot code. If you want to use additional libraries such as road runner, add references to TeamCode/build.gradle according to the 3rd party library's instructions.

### Road Runner
Road Runner is a popular open source odometry/path planning project for FTC. It is maintained by FTC Team 8367 (Acme Robotics) at:
https://github.com/acmerobotics/road-runner

There is excellent tuning advice using Road Runner at:
https://learnroadrunner.com/



