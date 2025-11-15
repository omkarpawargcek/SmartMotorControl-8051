# SmartMotorControl-8051
🌡️ Temperature-Based DC Motor Speed Control
Using 8051 Microcontroller and ADC0804
📘 Overview
This project demonstrates a simple and cost-effective system for regulating DC motor speed based on ambient temperature. It uses an LM35 temperature sensor, ADC0804 for analog-to-digital conversion, and an 8051 microcontroller to process the data and control motor speed via an L293D driver. An LCD displays real-time temperature and motor speed levels.
🔧 Components Used
- 8051 Microcontroller
- LM35 Temperature Sensor
- ADC0804 – Analog to Digital Converter
- L293D – Motor Driver IC
- DC Motor
- 16x2 LCD Display
- Power Supply & Supporting Circuitry
⚙️ Working Principle
- LM35 senses ambient temperature and outputs a proportional analog voltage.
- ADC0804 converts this analog signal into a digital value.
- The 8051 reads the digital temperature data and adjusts PWM signals to control motor speed.
- The LCD displays current temperature and motor speed level.
🎯 Applications
- Industrial cooling systems
- Smart exhaust fans
- Domestic appliances with thermal regulation
