# Arduino-automatic-LED-Control

This project demonstrates an Automatic LED Control System using an Arduino Uno and a Light Dependent Resistor (LDR). The system continuously monitors the surrounding light intensity through the LDR and automatically controls an LED based on a predefined threshold value.

When the ambient light level falls below the threshold (dark environment), the Arduino turns the LED ON. When sufficient light is detected (bright environment), the LED is turned OFF. This project introduces the basic concept of sensor-based automation, which is widely used in real-world applications such as street lights, corridor lighting, garden lights, and energy-saving lighting systems.

Features

- Automatic LED switching based on ambient light
- Uses an LDR as a light sensor
- Reads analog values using the Arduino ADC
- Threshold-based decision making
- Simple and beginner-friendly embedded systems project

Components Used

- Arduino Uno
- LDR (Light Dependent Resistor)
- LED
- 220Ω Resistor
- 10kΩ Resistor
- Breadboard
- Jumper Wires

Working Principle

The LDR forms a voltage divider circuit whose output voltage changes with light intensity. The Arduino reads this voltage using an analog input pin. If the measured value is below the selected threshold, the LED is switched ON; otherwise, it remains OFF.

This project helps in understanding analog sensor interfacing, ADC (Analog-to-Digital Conversion), conditional statements, and basic embedded programming in C/C++ using the Arduino platform.
