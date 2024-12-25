Water Level Monitoring System Project

A Water Level Monitoring System is an embedded solution designed to monitor the water level in storage tanks, reservoirs, or any other water storage system. This system can automate the process of managing water levels, reducing human intervention and preventing issues like water wastage or pump damage due to dry running. It is widely used in households, agriculture, industries, and municipal water systems.

Objective
The primary aim is to:
1. Monitor water levels accurately.
2. Automate the pump operation based on water levels.
3. Prevent overflow or dry running.
4. Provide visual and audible alerts when necessary.

System Description

The project consists of  components like :
Sensing Unit:
The ultrasonic sensor measures the distance between the water surface and the sensor. This data is used to calculate the water level.

 Processing Unit:
A microcontroller (e.g., Arduino) processes the data from the sensor. It determines the water level and controls the pump  based on preset thresholds.
A relay module operates the water pump automatically.

Components Used 
1. Ultrasonic Sensor (HC-SR04)
2. Arduino Uno
3. Relay Module
4. Water Pump
5. Power Supply

Working Principle
1. Measurement:
The ultrasonic sensor sends a sound wave that reflects off the water surface and returns to the sensor.
The time taken for the sound wave to return is used to calculate the distance.

2. Water Level Calculation:
The total height of the tank is known.
Water level = Total height - Distance measured by the sensor.

3. Data Processing:
The microcontroller processes the distance data to calculate the water level percentage 

4. Automation:
If the water level is below the lower threshold, the pump turns on automatically.
If the water level reaches the upper threshold, the pump turns off automatically

Advantages
1. Prevents water overflow and wastage.
2. Automates water management, saving time and effort.
3. Avoids pump damage due to dry running.
4. Reduces manual monitoring.
5. Low-cost and easy to implement.

Applications
1. Domestic Use
2. Agriculture
3.  3.Industrial Use
4. Smart Cities
