SmartBank Project<a name="TOP"></a>
===================

## Table of Contents
* [Introduction](#Introduction)
* [Specifications](#Specifications)
* [Unique Features](#Unique-Features)
* [Microcontroller Specifications](#Microcontroller-Specifications)
* [Power Bank SoC Specifications](#Power-Bank-SoC-Specifications)
* [Tools Used](#Tools-Used)
  * [EasyEDA](#EasyEDA)
  * [Arduino IDE](#Arduino-IDE)
  * [Fritzing](#Fritzing)
  * [Autodesk Fusion 360](#Autodesk-Fusion-360)
* [Reference SoC Circuit Diagram](#Reference-SoC-Circuit-Diagram)

## Introduction
Smart bank is a connected power bank which has various features like two-way adaptive fast charging, 12 – layer protection, find my device, simultaneous fast charging support, and it is also integrated with Qualcomm’s Quick Charge 3.0 technology. It has Bluetooth LE 5.0 connectivity with a mobile application through which the device’s parameters like battery status, battery temperature, charge discharge cycles, time left till 0%, etc. can be monitored.

## Specifications
* Qualcomm’s Quick Charge 3.0 technology
* Supports upto 18W Fast Charging
* 12 - layer ciruit protection
* Bluetooth LE 5.0 connectivity with SmartBank Connect App
* Find my device feature (Similar to apple's air tag)
* Compatible protocols (QC2.0/QC3.0, FCP, AFC, USBC DRP, BC1.2, and many more)
* USB Power Delivery (PD3.0/PD2.0)
* 20000 mAh battery capacity
* USB-A, Type-C and Micro USB support for input and output
* Simultaneous fast charging (13W per port)
* Built in high brightness flash

## Unique Features
* Find My Device
* Bluetooth Low Energy v5.0 connectivity
* Device parameter monitoring using SmartBank Connect App

## Microcontroller Specifications
* Espressif System's ESP32-C3FH4
* 32-bit RISC-V single-core processor
* Clock speed up to 160 MHz
* 384 KB ROM
* 400 KB SRAM (16 KB for cache)
* WiFi - IEEE 802.11 b/g/n-compliant
* Bluetooth LE: (Speed: 125 Kbps, 500 Kbps, 1 Mbps, 2 Mbps)
  * Bluetooth 5
  * Bluetooth mesh
* Peripherals: 
  * GPIO, SPI, UART, I2C, I2S, LED PWM controller, USB Serial/JTAG controller,Temperature sensor, SAR ADC
* Antenna: On-board PCB antenna (ESP32-C3-MINI-1)

## Power Bank SoC Specifications
* Injoinic Technology IP5328P with Fully Integrated Bi directional PD3.0 and Fast Charge Power Bank SOC
* QFN-48 Package
* Support 5V, 9V, 12V voltage input/output
* Integrated USB Power Delivery (PD2.0/PD2.0) protocol
* Up to 5.0A charging current at battery port
* Adaptive charging current adjustment
* Discharge: 5V/3.1A (15W) 9V/2.0A (18W) 12V/1.5A (18W)
* I2C interface for flexible and low cost customized solution
* Single inductor for charging and discharging
* Output overcurrent, overvoltage and short circuit protection
* Battery overcharge, over discharge and overcurrent protection
* Over temperature protection
* Battery NTC protection

## Tools Used
#### EasyEDA
EasyEDA is a web-based EDA tool suite that enables hardware engineers to design, simulate, share publicly and privately and discuss schematics, simulations and printed circuit boards.
For more details refer: <https://easyeda.com/>

#### Arduino IDE 
Arduino Integrated Development Environment or Arduino Software (IDE) contains a text editor for writing code, a message area, a text console, a toolbar with buttons for common functions and a series of menus. It connects to the Arduino hardware to upload programs and communicate with them. For more details refer: <https://www.arduino.cc/en/software>

#### Fritzing
Fritzing is an open-source hardware initiative that makes electronics accessible as a creative material for anyone. We offer a software tool, a community website and services in the spirit of Processing and Arduino, fostering a creative ecosystem that allows users to document their prototypes, share them with others, teach electronics in a classroom, and layout and manufacture professional PCBs. For more details refer: <https://fritzing.org/>

####Autodesk Fusion 360
Fusion 360 is a cloud-based 3D modeling, CAD, CAM, CAE, and PCB software platform for professional product design and manufacturing. For more details refer: <https://www.autodesk.in/products/fusion-360/overview>

## Reference SoC Circuit Diagram
