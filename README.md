# AI-voice-control-navigation-robot
Overview

This project features a voice-controlled robot that can be operated using human voice commands. The system utilizes an Android application as an interface to transmit user commands to a microcontroller via Bluetooth. The microcontroller then processes the received commands and controls the robot's movement accordingly.

Features

Voice-controlled movements: forward, left, right, stop, etc.

Uses an Android app for voice input

Bluetooth module for wireless communication

Microcontroller-based processing (Arduino Uno)

Compact and space-efficient design

Components Used

Microcontroller: Arduino Uno

Bluetooth Module: HC-05 or HC-06

Motor Driver: L298N

Power Supply: 9V/12V battery

Chassis: Robot car frame

Android App: For voice input processing

How It Works

The user gives voice commands through the Android app.

The app converts speech into text.

The text command is transmitted to the microcontroller via Bluetooth.

The microcontroller processes the command and controls the robot's movements accordingly.

Installation & Setup

1. Hardware Setup

Connect the Bluetooth module (HC-05) to the Arduino Uno.

Connect the motor driver (L298N) to the Arduino and motors.

Power the system with a suitable battery.

2. Software Setup

Install the Arduino IDE.

Upload the provided Arduino sketch to the Arduino Uno.

Install the custom Android app (APK) on your smartphone.

3. Running the Robot

Turn on the robot.

Open the Android app and pair it with the Bluetooth module.

Give voice commands and see the robot respond in real-time.

Commands Supported

"Move forward"

"Move backward"

"Turn left"

"Turn right"

"Stop"

Applications

Smart home automation

Assistive robotics

Educational projects

Remote-controlled vehicles

Future Enhancements

Adding obstacle detection using ultrasonic sensors

Enhancing speech recognition accuracy

Implementing AI-based decision-making

Contribution

Feel free to fork this repository and contribute improvements! Pull requests are welcome.
