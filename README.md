# OtterBoard-V2

![OtterBoard-V2 Image](https://github.com/Vishal01Mehra/OtterBoard-V2/blob/main/Images/OtterBoardV2%20Background%20Removed.png?raw=true)

**OtterBoard-V2** is an open-source hardware board designed for a wide range of embedded applications, leveraging the powerful ESP32-WROOM module. It offers extensive connectivity, GPIO, and peripheral support, making it suitable for IoT, automation, and other embedded systems projects.

## Features

### GPIO and Peripheral Features

- **16 Multifunctional GPIO pins** for general-purpose use.
- **Up to 13** 12-bit ADC channels for analog input.
- **Up to 2** DAC channels for digital-to-analog conversion.
- **Up to 16** PWM outputs for motor control or LED dimming.
- **Up to 8** capacitive touch pins for touch-sensitive applications.
- **Up to 3 SPI busses** (1 SPI bus pre-configured for the Arduino IDE).
- **I2S Audio Output** available for digital audio communication.
- **Up to 2 I2C busses** (1 I2C bus pre-configured for the Arduino IDE).
- **Up to 3 UARTs** (2 UARTs pre-configured for Arduino IDE; 1 used for bootloading/debugging).

### LED Indicators

- **PWR**: Red power LED.
- **CHG**: Yellow battery charging indicator.
- **STAT**: Blue status LED.
- **WS2812**: RGB LED for custom visual feedback.

### Buttons

- **BOOT**: Boot button.
- **RST**: Reset button.

### ESP32-WROOM General Features

- **Operating Voltage**: 2.3V to 3.6V.
- **Deep Sleep Current**: 2.5 µA.
- **Average Operating Current**: 80 mA.
- **Operating Temperature Range**: -40°C to 85°C.
- **Xtensa® Single-Core 32-bit LX6 Microprocessor** running up to 240MHz.
- **448KB of ROM and 520KB SRAM** for program storage and execution.
- **16MB of Embedded SPI Flash** for data storage.
- **Integrated 802.11b/g/n Wi-Fi** 2.4GHz transceiver for wireless connectivity.
- **Integrated Dual-Mode Bluetooth®** (Classic and BLE®) for communication.
- **Hardware-Accelerated Encryption**: AES, SHA2, ECC, RSA-4096 for secure data transmission.

### Sensor Features

- **MPU6050**: 6-axis accelerometer and gyroscope sensor for motion tracking.
  - **3-axis gyroscope** and **3-axis accelerometer**.
  - Motion sensing for applications like gesture detection and device orientation.
  - Programmable accelerometer and gyroscope ranges.
  
- **APDS9600**: Proximity and ambient light sensor.
  - **High-resolution proximity sensing** for accurate distance measurement.
  - **Ambient light sensing** for adjusting brightness in displays and devices.
  - Integrated IR emitter for proximity sensing.

## Schematic & PCB Design

The board is designed using **KiCad 8.99**, and all design files are included in the repository:

- **Schematic**: `https://github.com/Vishal01Mehra/OtterBoard-V2/blob/main/Schematics/OtterBoardV2.pdf`
- **PCB Layout**: `https://github.com/Vishal01Mehra/OtterBoard-V2/blob/main/PCB/OtterBoardV2-F_Cu.pdf`

## Getting Started

### Requirements

Before using the OtterBoard-V2, ensure you have the following:

- **Power Supply**: 2.3V to 3.6V.
- **Programming Software**: Arduino IDE or PlatformIO (with ESP32 support).
- **Additional Hardware**: USB-to-UART module for flashing, if necessary.

### Installation and Setup

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Vishal01Mehra/OtterBoard-V2.git
