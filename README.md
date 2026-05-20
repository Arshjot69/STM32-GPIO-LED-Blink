STM32 GPIO LED Blinking

This project demonstrates how to configure a GPIO pin as a digital output on an STM32 microcontroller and implement LED blinking functionality. The objective is to illustrate the basic operation of an embedded edge node, including hardware initialization, GPIO control, and periodic task execution.

Features
GPIO pin configuration as digital output
LED blinking with programmable delay
STM32CubeMX project configuration
STM32CubeIDE compatible source code
Simple embedded firmware example for beginners
Project Overview

The firmware initializes the STM32 microcontroller and configures a selected GPIO pin connected to an onboard or external LED. The LED is toggled continuously with a fixed delay, demonstrating basic input/output control and real-time embedded operation.

This project serves as a foundational example for:

Embedded systems programming
Edge-node device development
GPIO peripheral handling
STM32 HAL library usage
Hardware Requirements
STM32 Development Board
LED (Onboard or External)
USB Cable for programming and power
Software Requirements
STM32CubeIDE
STM32CubeMX
Working Principle
System clock and peripherals are initialized.
GPIO pin is configured in output mode.
The LED state is toggled inside an infinite loop.
A delay is added between toggles to create the blinking effect.
Applications
Basic embedded system learning
Edge-node operation demonstration
GPIO peripheral testing
IoT device prototyping
Real-time firmware development
