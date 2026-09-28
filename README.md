# ESP32 WiFi Connect

## Project Description

This project demonstrates how to connect an ESP32 to a WiFi network and display the assigned IP address using the Serial Monitor.

The ESP32 connects to the Wokwi-GUEST WiFi network. After successful connection, the assigned IP address is displayed in the Serial Monitor.

## Components Used

- ESP32
- WiFi Network
- Wokwi Simulator

## Connections

No external components are required for this project.

The ESP32 connects to the WiFi network through its built-in WiFi module.

## Working

1. The WiFi library is included in the program.
2. The WiFi SSID and password are defined.
3. ESP32 starts connecting to the WiFi network.
4. The program waits until the ESP32 is connected.
5. After successful connection, the IP address is obtained.
6. The assigned IP address is displayed in the Serial Monitor.
7. The connection status is also displayed in the Serial Monitor.

## WiFi

WiFi is a wireless communication technology used to connect devices to a network.

The ESP32 has built-in WiFi capability, which allows it to connect to wireless networks and communicate with other devices.

## Applications

- IoT projects
- Smart home systems
- Wireless monitoring
- Remote control systems
- Web server projects
- Internet-connected embedded systems

## Simulation

This project was created and tested using the Wokwi ESP32 Simulator.

### Wokwi Project

https://wokwi.com/projects/476378309646626817
