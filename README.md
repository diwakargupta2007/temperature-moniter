# Temperature Monitor (IoT)

An IoT-based project to measure and monitor temperature and humidity using a microcontroller and a DHT sensor.

## Components Used
- ESP32 or Arduino Uno
- DHT11 or DHT22 Temperature and Humidity Sensor
- Breadboard and Jumper wires

## Circuit Connections

| DHT11 Pin | Microcontroller Pin |
| :--- | :--- |
| VCC | 3.3V / 5V |
| GND | GND |
| DATA | GPIO 4 |

## How to use this project
1. Upload the provided code (`dhtmoniter.ino.ino`) to your microcontroller using the Arduino IDE.
2. Ensure you have installed the "DHT sensor library" in the Arduino IDE.
3. Open the Serial Monitor at 115200 baud to view the temperature and humidity readings.
