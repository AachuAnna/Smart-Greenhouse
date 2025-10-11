# Smart Greenhouse Monitoring and Control System

## Description
An IoT-based smart greenhouse system using an ESP8266 NodeMCU microcontroller. The system integrates a DHT22 temperature and humidity sensor, a soil moisture sensor, a relay to control a fan and water pump, a buzzer for alerts, and an LCD for real-time monitoring. It automates irrigation and climate control to optimize plant growth by continuously monitoring environmental conditions. Sensor data is sent to the ThingSpeak cloud platform for remote monitoring and analytics.

## Components
- ESP8266 NodeMCU
- DHT22 Temperature and Humidity Sensor
- Soil Moisture Sensor
- Relay Module (Fan and Water Pump Control)
- Buzzer (Alert System)
- LCD Display (I2C)
- Fan and Water Pump

## Wiring Details
- *DHT22:* VCC to 3V, Data to D2, GND to G
- *Soil Moisture Sensor:* VCC to 3V, AO to A0, GND to G
- *Relay:* VCC to Vin, IN to D5, GND to G
- *Buzzer:* Positive to D7, Negative to G
- *Fan and Pump:* Negative to G, Positive to NO on relay
- *LCD:* VCC to 3.3V, GND to G, SDA to D2, SCL to D1

## Features
- Real-time temperature, humidity, and soil moisture monitoring
- Automatic switching of fan and pump based on sensor readings
- Audible alert on sensor thresholds breach
- Data display on LCD for easy status visualization
- Cloud data logging and remote monitoring via ThingSpeak IoT platform

## Usage
- Upload the provided Arduino sketch to the ESP8266 using Arduino IDE
- Connect sensors and actuators as per wiring instructions
- Configure WiFi credentials and ThingSpeak API key in the code
- Power the system and monitor live environment data locally and remotely on ThingSpeak
- Adjust sensor thresholds to customize automation as per your greenhouse needs

## Author
Aachu Anna Sony
