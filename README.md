# Dynamixel Gokart

## Description
A project that sends position data to dynamixel servo, receives the current motor position, velocity, current, voltage, error status and allocates it in a class ready to send to ROS as packets.

## Table of Contents
- [Description](#description)
- [Table of Contents](#table-of-contents)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Operations](#operations)
- [Author](#author)
- [License](#license)

## Requirements
- Visual Studio 2022 Community Edition
- Dynamixel SDK library

## Installation
To install the required tools and libraries, follow these steps:

1. Clone the repository:
   git clone https://github.com/BrudneDupsko/dynamixelgokart
2. Navigate to the project directory:
   cd project_name
3. Open the project in Visual Studio 2022 Community Edition.
4. Install the Dynamixel SDK library following the instructions on the Dynamixel SDK website.

## Usage

To run the script, follow these steps:

1. Ensure that the Dynamixel motor is connected to the computer on port COM3 (or modify the DEVICENAME macro in the code if you are using a different port).
2. Build the project in Visual Studio.
3. Run the executable.
4. Follow the instructions displayed in the console to enter the motor's goal position.

## Operations

1. Opens the communication port.
2. Sets the communication speed (baud rate).
3. Enables the motor's torque.
4. Allows the user to enter the motor's goal position.
5. Sends the goal position to the motor.
6. Reads and displays the current motor position, velocity, current, voltage and error status.
7. Inputs the read data into a class.
8. Disables the motor's torque after operation.
9. Closes the communication port.

## Author 
Tymon Stankiewicz

#License 
Academic Free License
