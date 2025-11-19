# STM32F4 - L3GD20 SPI Communication

## Overview
This project implements SPI communication between the STM32F4 microcontroller and the L3GD20 gyroscope module. It enables real-time acquisition of angular rate data and includes calibration and noise filtering, making it suitable for stabilization systems in drones and robotics.

## Features
- SPI communication with L3GD20 gyroscope
- Real-time angular rate data acquisition
- Calibration routines for accurate measurements
- Noise filtering for stable readings
- Designed for use in drone and robotic stabilization systems

## Project Structure

## Hardware Requirements
- STM32F4 Discovery board or compatible STM32F4 MCU
- L3GD20 gyroscope module
- SPI connection wires

## Software Requirements
- STM32CubeMX (optional, for project initialization)
- STM32CubeIDE or Keil uVision
- HAL drivers for SPI and GPIO

## Usage
1. Connect the L3GD20 to the STM32 via SPI (MOSI, MISO, SCK, CS).
2. Configure the SPI peripheral in the STM32 firmware.
3. Compile and flash the firmware to the STM32.
4. Read angular rate data from the gyroscope through SPI.

## License
This project is open-source and available under the MIT License.

