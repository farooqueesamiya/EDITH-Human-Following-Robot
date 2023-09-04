# EDITH-Human-Following-Robot
In this repository, we will design and develop a human-following robot using Arduino Uno, Ultrasonic, and Infrared sensors, following a tutorial from DIY Builder on YouTube.

# EDITH - The Follow Me Robot Documentation

## Acknowledgment
This project, EDITH - The Follow Me Robot, was developed as a part of a learning experience during the final year of engineering. The idea and guidance for this project were sourced from a tutorial created by the YouTube channel DIY Builder(tutorial link - https://www.youtube.com/watch?v=yAV5aZ0unag&t=5s) and their Instagram account @diy.builder(https://www.instagram.com/diy.builder/).

We would like to express our gratitude to DIY Builder for providing valuable insights, instructions, and inspiration for this project. Without their contribution, this project wouldn't have been possible.

I would like to extend my heartfelt gratitude to the Integral University Robotics Lab (https://www.robotics.iul.ac.in/) for their invaluable support throughout the development of this project. Their generous provision of funds, tools, and a conducive environment for research and innovation has been instrumental in bringing this project to fruition. I am also deeply appreciative of their guidance and expertise, which have played a pivotal role in the successful design and implementation of the follow me robot. This project would not have been possible without their unwavering support and mentorship.

## Introduction
EDITH - The Follow Me Robot is a robotic project designed to assist users in carrying objects autonomously. This project utilizes an Arduino Uno and Ultrasonic sensor for navigation and object detection. The combination of these technologies allows the robot to follow a user while avoiding obstacles.

## Objectives
The main objectives of EDITH - The Follow Me Robot are:
- To design a robot prototype capable of autonomously following a user.
- To implement reliable obstacle detection using Ultrasonic sensors.
- To create an affordable and accessible robotic solution for assisting users in carrying objects.

## Functionalities
The robot's functionalities include:
- Autonomous following of a designated user.
- Obstacle detection and avoidance to ensure safe navigation.
- Flexibility in carrying various objects alongside the user.

## Hardware Requirements
To build EDITH - The Follow Me Robot, you will need the following hardware components:
- Arduino Uno board
- L293D Motor driver
- Four wheels
- Four TT gear motors
- Servo motor
- Ultrasonic sensors
- Infrared sensors
- 18650 Li-ion battery
- Battery holder
- Male-to-female jumper wires
- Acrylic sheet
- DC power switch

## Software Requirements
The software required for this project includes:
- Arduino IDE for programming the Arduino Uno.
- SolidWorks software for designing the robot's chassis and components.

## Project Description
### Step 1: Collecting Requirements
- Gather the necessary hardware and software components for the project.

### Step 2: Chassis Design
- Use SolidWorks software to design the robot's chassis with dimensions of 13.5 cm in length and 9 cm in breadth.

### Step 3: Motor Driver Attachment
- Attach the L293D motor driver to the backside of the chassis and connect the motor wires to the driver.

### Step 4: Circuit Setup
- Create the electronic circuit and connect the Arduino Uno to the motor driver.
- Establish connections between the motor driver and the Arduino pins.

### Step 5: Arduino and Motor Driver Mounting
- Mount the Arduino Uno on the PCB and establish connections with the components.
- Connect the motor driver to the Arduino pins (IN1 to D5, IN2 to D4, etc.).

### Step 6: Mounting Sensors and Servo
- Attach the servo motor to the chassis.
- Place the Ultrasonic sensor in its mount and attach it to the servo.

### Step 7: Sensor Connections
- Connect the servo and Ultrasonic sensor to the Arduino.
- Ensure proper wiring: servo to servo pins, Ultrasonic sensor pins (trig, echo, GND, VCC).

### Step 8: Uploading the Code
- Remove servo and Ultrasonic sensor wires from the PCB.
- Connect the Arduino Nano to your computer and upload the code using the Arduino IDE.

## Applications
This project has various potential applications, including:
- Assisting individuals with carrying objects in various settings.
- Enhancing mobility for people with limited physical capabilities.
- Serving as a platform for further robotics and AI research.

## Conclusion
EDITH - The Follow Me Robot is a successful prototype that accomplishes its objectives. It autonomously follows a designated user, detects obstacles, and offers an affordable solution for object transport. The robot's accurate decision-making algorithm was validated in a real laboratory environment.

