# ROBOT MOVEMENT

# Arduino Stepper Motor Control with HC-SR04 Sensor: 
This Arduino sketch enables control of a stepper motor based on serial commands received from a computer. It also reads distance data from an HC-SR04 ultrasonic sensor and communicates it over serial.

## Overview: 
The sketch includes functionality for:
* Serial Communication: Listens for serial commands ('F' for forward, 'B' for backward, 'S' for stop) to control the stepper motor's direction and speed.
* HC-SR04 Sensor: Reads distance data from an HC-SR04 ultrasonic sensor and sends it back via serial communication.

## Hardware Setup: 
* Connect the stepper motor and HC-SR04 sensor to the Arduino based on the pin configurations.
* Ensure the Arduino board is connected to a computer via USB for serial communication.

## Arduino Setup:
* Libraries required: AccelStepper (for stepper motor control) and NewPing (interacting with HC-SR04 sensor).
* Open the stepper motor control file in the IDE and use the logic provided.
* Select the appropriate board and port in the Arduino IDE.
  

## Send the following commands to control the stepper motor:
* 'F' to move the stepper motor forward.
* 'B' to move the stepper motor backward.
* 'S' to stop the stepper motor.
