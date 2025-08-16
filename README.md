# SensESP meets HSM

Combine Quantum Leaps Hierarchical State Machine qm technology with SensESP project. This project merges
the HSM Demo app from Quantum Leaps with the SensESP Project Template to demonstrate how the two technologies
can be combined to provide an efficient platform for Marine Instrumentation development.

## SensESP Project Template

This repository provides a template for [SensESP](https://github.com/SignalK/SensESP/) projects.
Fork, clone or download the repository and try building and uploading the project to an ESP32 device.
You should immediately see output on the serial monitor! Similarly, you should be able to connect to
the WiFi access point with the same name as the device. The password is `thisisfine`.

To customize the template for your own purposes, edit the `src/main.cpp` and `platformio.ini` files.

Comprehensive documentation for SensESP, including how to get started with your own project, is available at the [SensESP documentation site](https://signalk.org/SensESP/).

## Quantum Leaps hsmtst project

The Quantum Leaps Hierarchical State Machine test project demonstrates the principles of 
Hierarchical State Machines and the Quantum Modelling tool (qm).

The qm tool is used to develop a hsm using graphical methods. qm then generates all the necessary
code to implement the hsm in C++. The graphical model also contains all source code necessary to
integrate the SensESP project template to yield a fully functional demo application with embedded hsm.

