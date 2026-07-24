# Autonomous Robot Movement

This project implements an embedded control system for an autonomous robot.  
The project includes schematic and PCB design, as well as embedded C firmware for sensor acquisition, motor control and basic robot movement logic.

## Project Description

The goal of the project was to design and implement a simple autonomous robot system capable of reading sensor data and controlling movement based on the detected environment.

The project covers both hardware and software parts of an embedded system.  
The hardware part includes schematic design and PCB layout, while the software part includes embedded C code for reading inputs, controlling outputs and handling robot behavior.

## Technologies Used

- Embedded C
- Altium Designer
- Schematic design
- PCB layout
- Microcontroller programming
- Sensor interfacing
- Motor control
- Digital and analog signals
- Basic debugging and testing

## Hardware Design

The hardware part of the project was designed in Altium Designer.  
It included creating the schematic, selecting and placing components, routing the PCB and preparing the board for implementation.

The PCB was designed for an autonomous robot control system and included the required connections for the microcontroller, sensors, motor driver and supporting electronic components.

## Firmware

The firmware was written in embedded C.  
The program is responsible for reading sensor values, processing input signals and controlling the robot movement.

The main firmware tasks include:

- Sensor data acquisition
- Motor control
- Movement decision logic
- Input/output pin control
- Basic system initialization
- Communication handling, if required by the system

## System Operation

The robot reads data from connected sensors and uses this information to determine how it should move.  
Based on the sensor input, the microcontroller controls the motors and adjusts the robot movement.

The system demonstrates a basic embedded control loop:

```text
Sensors → Microcontroller → Decision logic → Motor control → Robot movement
