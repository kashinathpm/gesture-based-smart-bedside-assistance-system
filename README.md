# gesture-based-smart-bedside-assistance-system

## Project Overview
The Gesture-Based Smart Bedside Assistance System is an assistive embedded system designed for differently abled and bedridden individuals. The system enables users to communicate essential needs such as food, water, medicine, help, and emergency assistance using simple hand gestures.

The project is developed using the Myosa ESP-based development board, MPU6500 motion sensor, OLED display, and active buzzer module. Motion gestures are detected using the MPU6500 accelerometer and gyroscope sensor, processed by the ESP-based controller, and converted into predefined assistance requests.

The OLED display provides visual feedback while the buzzer generates unique audio alert patterns for each request, making the system effective for real-time bedside communication and emergency assistance.
## Features
Real-time gesture detection

OLED visual feedback system

Audio alert generation using buzzer

Emergency alert mode

Assistive communication support

Low-cost embedded implementation

Simple and user-friendly interaction

Gesture-based request system

Real-time motion sensing using MPU6500
## Hardware Components
Myosa ESP-based Controller
MPU6500 Motion Sensor
OLED Display
Active Buzzer
Breadboard
Jumper Wires
USB Power Supply

## Software and Technologies Used
Arduino IDE
Embedded C++
Wire Library
Adafruit GFX Library
Adafruit SSD1306 Library
I2C Communication Protocol

## Circuit Connections
MPU6500 SDA  → SDA Pin
MPU6500 SCL  → SCL Pin
MPU6500 VCC  → 3.3V / 5V
MPU6500 GND  → GND

OLED SDA     → SDA Pin
OLED SCL     → SCL Pin
OLED VCC     → 3.3V / 5V
OLED GND     → GND

Buzzer (+)   → GPIO 25
Buzzer (-)   → GND
## Gesture Mapping
| Gesture | Output Message | Buzzer Pattern |
|---|---|---|
| Left Tilt | FOOD | Single Beep |
| Right Tilt | WATER | Double Beep |
| Forward Tilt | HELP | Triple Beep |
| Backward Tilt | MEDICINE | Long Beep |
| Strong Shake | EMERGENCY | Rapid Alert Beeps |
## Working Principle
The MPU6500 sensor continuously reads acceleration and motion data from the system. Based on the tilt direction and motion intensity, predefined gesture conditions are detected.

When a gesture is identified, the ESP-based Myosa controller processes the input and displays the corresponding message on the OLED screen. At the same time, the buzzer generates a unique alert pattern for each request.

Different gestures are assigned for different assistance requests such as water, food, medicine, help, and emergency alerts. This enables simple and effective bedside communication using motion-based interaction.
## Applications
Hospitals
Elderly Care Systems
Smart Bedside Assistance Systems
Assistive Communication Devices
Emergency Alert Systems
Wearable Healthcare Systems
## Future Improvements
Wireless nurse notification system

IoT-based remote monitoring

Mobile application connectivity

Voice assistance integration

Cloud-based emergency alert system

Battery-powered portable version

AI-based gesture recognition

Wireless communication using Bluetooth or Wi-Fi

Integration with hospital automation systems

Real-time patient monitoring features

Smart wearable implementation

Multi-language audio feedback system
## Usage Instructions
1. Power the Myosa ESP-based controller.
2. Hold the device in hand.
3. Perform gesture movements.
4. Observe the OLED display and buzzer alerts.
5. Use different gestures for different assistance requests.
## Demo Video
Use this Google drive link to access the demo video:
https://drive.google.com/drive/folders/1-ij4-cbTT140rmAECP4C3A7zGD0cQbMa?usp=sharing
## Conclusion
The Gesture-Based Smart Bedside Assistance System demonstrates a low-cost and effective assistive embedded solution for differently abled and bedridden individuals.

The project combines gesture recognition, sensor interfacing, OLED visualization, and audio alert generation to create a real-time communication system using the Myosa platform.

This system can be further expanded for healthcare, hospital automation, and smart assistive technology applications.
