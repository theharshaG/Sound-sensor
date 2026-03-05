# Sound-sensor
# Sound Sensor LED Control using ESP32
## Project Overview
This project demonstrates how to use a **sound sensor with ESP32** to detect voice or noise.  
When the sensor detects sound, an **LED turns ON**. When there is no sound, the **LED turns OFF**
This simple project helps beginners understand **digital sensors and basic automation using ESP32**.

## Components Used
- ESP32
- Sound Sensor Module
- LED
- 220Ω Resistor
- Breadboard
- Jumper Wires

## Pin Connections

Component---->ESP32 Pin 
Sound Sensor OUT---->GPIO 27
LED Positive---->GPIO 2
LED Negative---->GND 
Sound Sensor VCC---->3.3V
Sound Sensor GND---->GND

## How It Works
1. The **sound sensor detects sound or voice** in the environment.
2. The sensor sends a **digital signal** to the ESP32.
3. ESP32 reads the signal using `digitalRead()`.
4. If sound is detected:
   - LED turns **ON**
   - Serial Monitor shows **"Voice Detected"**
5. If no sound is detected:
   - LED turns **OFF**
   - Serial Monitor shows **"No Voice"**

## How to Run the Project
1. Connect all components according to the circuit.
2. Open **Arduino IDE**.
3. Select **ESP32 board**.
4. Upload the code to ESP32.
5. Open **Serial Monitor (9600 baud)**.
6. Make a sound near the sensor and observe the LED response.

## Concepts Learned
- Digital sensor interfacing
- Using `digitalRead()` in ESP32
- Controlling output devices
- Serial communication for debugging
- Basic sound detection system
  
## Author
Harsha G  
Learning **Python, Embedded Systems, and IoT**
