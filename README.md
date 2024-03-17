# Smart Bin Project

This project is about creating a smart bin using an ESP32 camera module. The bin is equipped with a camera and motors, and it can be controlled over WiFi.

## Dependencies

The code uses the following libraries:
- `esp_camera.h`: For controlling the ESP32 camera.
- `Arduino.h`: Standard Arduino library.
- `WiFi.h`: For WiFi connectivity.
- `AsyncTCP.h`: For asynchronous TCP communication.
- `ESPAsyncWebServer.h`: For creating an asynchronous web server.
- `iostream`: Standard C++ library for input/output operations.
- `sstream`: Standard C++ library for string stream operations.
- `ESP32Servo.h`: For controlling the servo motors.

## Hardware

The hardware components of the project include:
- ESP32 Camera Module
- Servo Motors
- DC Motors
- LEDs

## Software

The software part of the project includes setting up a WiFi server and handling the incoming requests to control the bin's movements and camera.

## Setup

1. Install the required libraries in your Arduino IDE.
2. Connect the hardware as per the defined pin configurations in the code.
3. Upload the code to your ESP32 board.
4. Connect to the WiFi network created by the ESP32 board. The SSID is "RRBot" and the password is "12345678".
5. Open a web browser and go to the IP address of the ESP32 board to access the control interface.

## Usage

The bin can be controlled using the arrow keys on the keyboard. The camera feed can be viewed on the web interface.

## Note

This is a work in progress and the code is subject to change.
