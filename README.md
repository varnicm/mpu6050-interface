# MPU6050 Sensor Interface Project

## Description
This project provides a Python script for interfacing with the MPU6050 sensor to continuously read accelerometer data. It's designed to run on a Raspberry Pi and communicates with the MPU6050 via the I2C protocol.

## Features
- Continuous data reading from MPU6050 accelerometer.
- Easy integration with Raspberry Pi.
- Simple and clear Python code for beginners and enthusiasts.

## Hardware Requirements
- Raspberry Pi (any model with GPIO pins).
- MPU6050 sensor.
- Connection wires.

## Software Requirements
- Python 3.x
- smbus library for I2C communication.

## Installation
1. Clone the repository:
git clone https://github.com/varnicm/mpu6050-interface.git
2. Navigate to the project directory:
cd mpu6050-interface

## Setup and Configuration
1. Connect the MPU6050 to your Raspberry Pi using I2C pins.
2. Enable I2C on the Raspberry Pi using `raspi-config`.
3. Install the `smbus` library:
pip install smbus

## Usage
Run the script with:
python mpu6050_script.py
The script will start reading data from the sensor and display it in the console.

## Contributing
Contributions to this project are welcome! Please fork the repository and submit a pull request with your changes.

## Project Status
This project is currently in its development stage and open to enhancements.

