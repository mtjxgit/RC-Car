# **Bluetooth Remote-Controlled Car Project**

## Project Overview
This project is a Bluetooth remote-controlled car built with an STM32F411 microcontroller. It allows users to control the car via an Android app using Bluetooth connectivity. The car integrates essential components for motor control, obstacle detection, and wireless communication, along with a custom-designed chassis created in AutoCAD and printed with a 3D printer.

## **Components Used**
- **Microcontroller**: STM32F411
- **Motor Driver**: L293D
- **Bluetooth Module**: HC-05
- **IR Sensor**: Obstacle detection
- **Car Chassis and Motors**: Custom chassis, designed in AutoCAD and Laser Cut
- **Android App**: Remote control interface

## **Features**
- **Bluetooth Control**: Android app sends commands via Bluetooth.
- **Obstacle Detection**: IR sensor prevents collisions.
- **Motor Control**: L293D driver controls the car’s motors for movement.
- **Custom Design**: The car chassis was custom-designed using AutoCAD and manufactured with a 3D printer.

## **Development Environment**
- **IDE**: Keil uVision 5
- **Programming Language**: Embedded C for STM32F411

## **Setup and Usage**
1. Flash the firmware onto the STM32F411 using Keil uVision.
2. Connect to the HC-05 Bluetooth module via the Android app.
3. Use the app interface to control the car’s movement.
