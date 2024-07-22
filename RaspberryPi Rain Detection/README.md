# Raspberry Pi Node-RED Rain Sensor Project

## Overview

This project utilizes Node-RED on a Raspberry Pi to integrate a rain sensor with a servo motor and a buzzer. The system is designed to:

- **Rain Detection**: When the rain sensor detects rain, the servo motor moves to a 45-degree position to press a switch.
- **Alert**: Simultaneously, the buzzer is activated to notify the owner of the rain event.

## Components

- **Rain Sensor**: Connected to GPIO pin 18.
- **Homing Sensor**: Connected to GPIO pin 23.
- **Servo Motor**: Connected to GPIO pin 17 (PWM output).
- **Buzzer**: Connected to GPIO pin 27.

## Files

- **Flow File**: [flow.json](./flow.json) - Import this file into your Node-RED environment to set up the project.
- **Pin Configurations**: [pin-config.jpeg](./pin-config.jpeg) - Image showing GPIO pin connections and configurations.

## Getting Started

1. **Install Node-RED**: Follow the instructions on the [Node-RED website](https://nodered.org/docs/getting-started/) to install Node-RED on your Raspberry Pi.
2. **Import Flow**: Open Node-RED and import the `flow.json` file.
3. **Connect Components**: Connect the rain sensor, servo motor, and buzzer to the specified GPIO pins on the Raspberry Pi as shown in `pin_config.png`.
4. **Deploy**: Deploy the flow in Node-RED.

## Usage

When the rain sensor detects rain, the flow will:

1. Move the servo motor to a 45-degree position to press the switch.
2. Activate the buzzer for 5 seconds to alert the owner.

## License

This project is licensed under the MIT License. See the [LICENSE](../LICENSE) file for more details.

## Support

For support or questions, please open an issue in the repository.

