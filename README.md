# Smartphone Controlled Arduino 4WD Car

The Arduino 4WD Smartphone Controlled Car is a DIY project that allows you to build a remotely controlled four-wheel-drive car using an Arduino Uno board. This project leverages an Arduino, a motor driver module, a bluetooth module and a smartphone app to control the car's movement, lights, and horn. It's a fun and educational project for electronics and programming enthusiasts.

# Components Needed:

Arduino Uno, 
4WD Car Chassis with Motors, 
2 L298N Motor Driver Module, 
HC05 Bluetooth Module, 
12V Battery, 
LED Lights (Front and Back), 
Buzzer (Horn), 
Smartphone, 
Jumper wires, 
Breadboard (optional)

# Application Required

Bluetooth RC Car (By Andi.Co) on Playstore

![Bluetooth_RC_Car](https://github.com/ArunAK111/Arduino_Car/assets/117448626/d3ad4088-91e7-455d-9a36-382b1652b805)


# Project Features:

Remote Control: You can control the car wirelessly using a smartphone app via Bluetooth communication.

Direction Control: The car can move forward, backward, turn left, turn right, and perform diagonal movements.

Variable Speed: Adjust the car's speed using speed bar on the app.

Light Control: Toggle the front and back LED lights on and off using the app.

Horn Sound: Activate and deactivate the car's horn using the app.


# Arduino Code:

The code you've provided is responsible for controlling the car's movements and interacting with the smartphone app through Bluetooth communication. It defines pin mappings for motors, lights, and the buzzer, as well as functions for different car movements and actions.


# Circuit

![image](https://github.com/ArunAK111/Arduino_Car/assets/117448626/3326245e-cf11-452c-ac11-cf9e77838889)


# How It Works:

The Arduino initializes all pins and sets up the serial communication at 9600 baud.

The loop() function continuously checks for commands from the smartphone app via Bluetooth.

Based on the received command, the Arduino triggers the corresponding function to control the car's movement, lights, and horn.

The code allows you to customize the car's speed and various features like lights and horn.
