# KiCad Projects Repository

This repository contains a collection of KiCad PCB design projects covering various electronics applications from power supplies to microcontroller boards and automation systems.

## Projects Overview

### Power and Control Systems

#### [8 Channel Relay](8_ChannelRelay/)
An 8-channel relay board for controlling multiple high-power devices, suitable for home automation and industrial control applications.

#### [ACDC Convertor](ACDC_Convertor/)
AC-to-DC converter circuit with rectification, filtering, and voltage regulation for stable DC power output from AC sources.

#### [Buck Convertor 4-Layer Board](Buck_Convertor_4_layers/)
4-layer PCB design for a buck convertor (step-down DC-DC convertor) with enhanced thermal management and EMI performance for efficient power supply applications.

#### [Battery Power Management Board 4-Layer](Battery_Power_Management_Board_4_layers/)
4-layer PCB design for a complete lithium-ion/polymer battery management system featuring TP4056 charger IC and DW01A protection IC with USB Type-C charging interface for portable electronics and IoT applications.

#### [Simple Power Supply Board](Simple_power_supply_board/)
A regulated DC power supply with filtering and protection circuitry for powering electronic projects.

#### [Motor Driver 4-Layer Board](Motor_Driver_4_layer/)
4-layer PCB design for a brushed DC motor driver featuring DRV8871DDA H-bridge driver with PWM control, supporting up to 45V and 3.6A with current limiting protection for efficient motor control applications.

#### [Stepper Motor Driver 4-Layer Board](Stepper_Motor_Driver_4_layers/)
4-layer PCB design for a stepper motor driver featuring A4988 driver IC with microstepping support (up to 1/16 step), supporting up to 35V and 2A per coil with built-in protection for CNC machines, 3D printers, and robotics applications.

### Microcontroller Boards

#### [ESP32 Dev Board Clone](ESP32%20Dev%20Board%20Clone/)
Custom ESP32 development board with Wi-Fi and Bluetooth capabilities for IoT applications.

#### [ESP32 I²C Sensor Hub](ESP32%20I²C%20Sensor%20Hub/)
ESP32-based sensor hub for aggregating data from multiple I²C sensors with wireless transmission capability.

#### [ESP32S3 4-Layer USB-C Board](ESP32S3_4Layer_USB_C/)
Advanced 4-layer PCB design featuring ESP32-WROOM-32 module with USB-C connectivity for professional embedded and IoT applications with improved signal integrity and EMC performance.

#### [ESP32 Memory Display Board](ESP32_mem_display/)
ESP32-based board with integrated ILI9341 320x240 SPI TFT LCD display and W25Q128JVS external SPI flash memory for IoT applications requiring user interface and data logging capabilities.

### Industrial Automation

#### [Conveyor Belt Main Board](Conveyor_Belt_Main_Board/)
Complete control board for automated conveyor systems featuring ATmega328P, stepper motor driver, I2C multiplexer, and IR sensor support.

#### [Conveyor Belt Arduino Mega Board](Conveyor_Belt_Arduino_mega_board/)
Arduino Mega interface board for conveyor belt control with integrated power and signal conditioning.

### Sensors and Monitoring

#### [Car Battery Level Detector](CarBatteryLevelDetector/)
12V automotive battery voltage monitoring circuit with state of charge indication.

#### [Sensor and Display Module](Sensor%20and%20Display%20Module/)
Integrated board combining sensor inputs with display output for real-time data visualization.

### Audio and Visual

#### [Stereo Audio Processing Board](Stereo_Audio_Processing_Board/)
Stereo audio signal processing board for amplification and filtering with left/right channel support.

#### [Chaser Board](Chaser%20Board/)
LED chaser circuit creating sequential lighting effects for decorative and indicator applications.

### Other Projects

#### [Mosquito Repellant](MosquitoRepellant/)
Electronic mosquito repellent device providing chemical-free pest control.

## Tools Used

All projects are designed using **KiCad**, an open-source electronics design automation suite.

## Project Structure

Each project directory contains:
- KiCad project files (`.kicad_pro`, `.kicad_sch`, `.kicad_pcb`)
- README.md with project description and features
- PCB preview images
- Additional documentation where applicable

## Getting Started

1. Install [KiCad](https://www.kicad.org/) (version 6.0 or later recommended)
2. Clone this repository
3. Open any project by double-clicking the `.kicad_pro` file
4. Review the schematic and PCB layout
5. Modify as needed for your application

## License

Please check individual project directories for specific licensing information.

## Contributing

This is a personal project repository. Feel free to use these designs as reference for your own projects.
