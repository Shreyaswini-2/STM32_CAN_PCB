# STM32 CAN Node PCB

## Overview
Custom STM32-based CAN communication PCB designed using KiCad.

## The project integrates:
- STM32F103 microcontroller
- TCAN1043-Q1 CAN transceiver
- Voltage sensing circuit
- NTC temperature sensing
- AMS1117 5V and 3.3V regulation
- SWD programming interface

## Features
- CAN communication interface
- ADC voltage monitoring
- Temperature monitoring
- 2-layer PCB design
- Automotive electronics oriented architecture

## Tools Used
- KiCad
- LTspice
- DigiKey
- STM32 ecosystem

## Hardware Components
- STM32F103C8T6
- TCAN1043-Q1
- AMS1117-5.0
- AMS1117-3.3
- NTC Thermistor

## Current Status
## Current Status

Hardware:

* Schematic completed
* 2-layer PCB layout completed
* Component selection in progress

Firmware:

* ADC1 battery voltage acquisition implemented
* ADC2 thermistor acquisition implemented
* NTC temperature calculation implemented
* CAN message transmission implemented
* STM32CubeMX and STM32CubeIDE project builds successfully

## CAN Message Structure

| Bytes | Description           |
| ----- | --------------------- |
| 0-1   | Battery Voltage (mV)  |
| 2-3   | Temperature (°C × 10) |

## Future Improvements

* CAN receive functionality
* Fault detection (over-temperature / under-voltage)
* ADC filtering
* Hardware validation on physical PCB

## Schematic

![Schematic](Screenshot%202026-05-25%20173953.png)

## PCB Layout

![PCB Layout](Screenshot%202026-05-25%20192437.png)
