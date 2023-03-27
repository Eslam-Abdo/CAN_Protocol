# STM32f103c8 CAN Driver
This repository contains a CAN driver implementation for the STM32f103c8 microcontroller. The driver provides a low-level interface for transmitting and receiving CAN messages using the MCP2551 CAN transceiver IC.

## Getting Started
To get started with using the driver in your project, you will need to have the following software and hardware:

### Software
- Your preferred ARM development environment (e.g. Keil, IAR, GCC)
- STM32f103c8 board support package (BSP)
### Hardware
- STM32f103c8 development board
- MCP2551 CAN transceiver IC
- CAN bus cables
- ST Link V2 Programmer

## Installing the Driver
To install the driver in your project, follow these steps:

1. Clone this repository to your local machine.
2. Add the files in the "Driver" folder to your project in your preferred development environment.
3. Configure your development environment to use the STM32f103c8 as the target microcontroller.
4. Build the project to ensure that the driver is properly integrated.

## Using the Driver
To use the driver in your code, include the relevant header files and call the driver functions as needed. Refer to the documentation in the header files for more information on the available functions.

A simple example is provided in the "Example" folder, which demonstrates how to send and receive data using the driver. In this example, four LEDs are turned on based on the data received over the CAN bus.

## Contributing
If you find a bug or have a feature request, please open an issue in the repository. Pull requests are also welcome.

## License
This driver implementation is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgments
- [STMicroelectronics](https://www.st.com/) for providing the STM32f103c8 microcontroller and development tools.
- [Microchip](https://www.microchip.com/) for providing the MCP2551 CAN transceiver IC.
