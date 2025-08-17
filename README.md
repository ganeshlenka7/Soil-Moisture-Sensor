Soil Moisture Monitoring using Arduino

This project demonstrates the use of a soil moisture sensor with Arduino to measure and display soil moisture levels. It helps in understanding analog sensor interfacing and interpreting sensor values through the Serial Monitor.

Components

Arduino Uno

Soil Moisture Sensor (Analog Output)

Jumper wires

Breadboard

Features

Reads real-time soil moisture values from the sensor.

Displays raw analog values on the Serial Monitor.

Indicates soil condition as either "WET" or "DRY" based on sensor readings.

How It Works

The soil moisture sensor outputs an analog signal corresponding to the moisture level in the soil.

Arduino reads this value using the analogRead() function.

If the value is ≥ 500, the soil is considered dry.

If the value is < 500, the soil is considered wet.

The results are displayed on the Serial Monitor every 2 seconds.

Wiring

Sensor Analog Pin → Arduino A0

VCC & GND → Arduino 5V & GND

![Soil Moisture Sensor](Soil%20Moisture%20Sensor.png)

Code

The Arduino sketch handles the pulse generation, distance calculation, and LED control using simple digitalWrite, pinMode, and pulseIn functions.
