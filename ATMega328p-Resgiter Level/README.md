
# ATMega328p Register Level Sensor Integration

## Overview
This project demonstrates the integration of sensors at the register level using an ATMega328p microcontroller. The setup includes an ultrasonic sensor, LED, buzzer, and a slide switch. The project is simulated and tested using Wokwi, an online Arduino simulator.

## Components
- **Arduino Uno (ATMega328p)**
- **Ultrasonic Sensor (HC-SR04)**
- **220 Ohm Resistor**
- **Red LED**
- **Buzzer**
- **Slide Switch**

## Connections
### Ultrasonic Sensor
- **GND** to Arduino GND
- **VCC** to Arduino 5V
- **ECHO** to Arduino Pin 2
- **TRIG** to Arduino Pin 3

### LED
- **Cathode (C)** to Arduino GND
- **Anode (A)** through a 220-ohm resistor to Arduino Pin 4

### Buzzer
- **Negative terminal** to Arduino GND
- **Positive terminal** to Arduino Pin 5

### Slide Switch
- **Terminal 1** to Arduino GND
- **Terminal 2** to Arduino Pin 6
- **Terminal 3** to Arduino 5V

## Project Functionality
- **Ultrasonic Sensor:** Measures distance and outputs the value.
- **LED and Buzzer:** Controlled based on the distance measured by the ultrasonic sensor.
- **Slide Switch:** Toggles between different modes of operation.

## Libraries Used
- **AVR Standard C Time Library**

## Simulation
You can simulate this project on Wokwi using the following link: [Wokwi Project Simulation](https://wokwi.com/projects/290056311044833800).

## File Structure
- **Source Files/main.ino:** Contains the main program logic.
- **Source Files/diagram.json:** Used to mantain wire connections on Wokwi simulator.
- **Results/Output.png:** This shows the output obtained on Wokwi.
- **Results/Project_Report.pdf:** This file, containing project Report.
- **README.md:** This file, containing project overview and instructions.

## Getting Started
### Prerequisites
- **Wokwi Account:** To simulate the project online.
- **AVR-GCC Toolchain:** To compile the code if testing on hardware.

## License
This project is licensed under the MIT License. See the LICENSE file for more details.
