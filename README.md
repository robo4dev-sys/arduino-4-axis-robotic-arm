# 4-Axis Arduino Robotic Arm

## Overview

This project presents a custom-built **4-axis robotic manipulator** controlled using dual analog joysticks and an Arduino microcontroller. The robotic arm was designed in **Autodesk Fusion 360** and fabricated using **3D-printed components**.

The system uses five servo motors to control base rotation, shoulder movement, elbow articulation, wrist motion, and a gripper mechanism.

## Features

* 4-axis robotic manipulator
* Dual joystick manual control
* Arduino-based servo motor control
* Custom 3D-printed mechanical structure
* Gripper with passive return mechanism using rubber bands
* Cost-effective and simple hardware design

## Hardware Components

* Arduino Uno / Arduino Mega
* 5x SG90 Servo Motors
* 2x Dual-axis Joystick Modules
* Breadboard
* Jumper wires
* 3D printed robotic arm structure

## Project Structure

Code&Connections
Contains the Arduino code and circuit/wiring diagram used for controlling the robotic arm.

Stl_Files
Contains all the STL files required for 3D printing the robotic arm components.

4-Axis_Documentation
Contains the full project report describing the design, hardware architecture, and software logic.

## System Functionality

The robotic arm is controlled using two analog joystick modules. Each joystick provides two axes of movement which are mapped to the arm’s joints:

* Base rotation
* Shoulder movement
* Elbow movement
* Wrist movement

The gripper mechanism is actuated by a dedicated servo motor and uses rubber bands to provide passive closing tension.

## Software Logic

The Arduino firmware performs the following operations:

1. Reads analog signals from the joystick modules
2. Maps the input values (0–1023) to servo angles (0–180 degrees)
3. Sends PWM signals to the servo motors using the Servo library
4. Controls the gripper through a button input or joystick trigger

## Future Improvements

* Upgrade to **MG90S metal gear servos** for higher torque
* Add **external power supply** for improved stability
* Implement **inverse kinematics** for coordinate-based control
* Improve motion smoothness and precision

## Author

M.V. Jishnu
