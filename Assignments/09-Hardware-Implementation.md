[Previous](https://github.com/314-grp-301/314-grp-301.github.io/blob/main/Assignments/06-Microcontroller-Selection.md) - [Main Page](../README.md) - [Next](https://github.com/314-grp-301/314-grp-301.github.io/blob/main/Assignments/10-Software-Implementation.md)<br>
[Navigation](https://github.com/314-grp-301/314-grp-301.github.io/blob/main/docs/Navigation.md)<br><br>

# Hardware Implementation
## Introduction
In this section, we delve into the Hardware Implementation of the Portable Weather Station, outlining the intricate details of the physical components and assembly processes used in our project. We will explore the selection of sensors, circuit design, and integration techniques that enable the reliable collection and transmission of meteorological data. Additionally, this chapter provides a step-by-step guide on the assembly of the hardware components, accompanied by troubleshooting tips and considerations for enhancing device robustness and efficiency. Through detailed diagrams and practical insights, we aim to illuminate the technical foundation that supports the functionality of our weather station.

## Final Schematic
![Alt text](https://raw.githubusercontent.com/314-grp-301/314-grp-301.github.io/main/docs/assets/images/Team301Schematic-1.png)<br><br>
This schematic diagram represents the electrical blueprint for a Weather Pod, detailing the connections and components required for its operation. It is divided into sections, each attributed to a team member, suggesting a collaborative design effort:

### Temperature Sensor 
Zeke Trevino: This section outlines the connection of a temperature sensor, including a resistor for the sensor and connections for the power supply and data outputs.
### Humidity Sensor 
Brian Wegner: This part of the circuit features a humidity sensor with its own power connections, capacitors for stabilization, and data lines.
### Microcontroller PIC16F15354-FM1 & ESP32 WiFi 
Fynn Meyerhoff: The core of the system, the microcontroller, is responsible for processing the data from the sensors. It is connected to an ESP32 WiFi module, which likely enables wireless communication for data transmission.
### Voltage Regulator 
This section includes a voltage regulator circuit that steps down the voltage from a 9V battery to a 3.3V output, using components like capacitors, an inductor, and a diode for power management.
### Motor Driver 
Kevis Seymore: A motor driver circuit with an H-bridge design is included for controlling a motor's direction and speed, possibly for moving parts of the weather station, like an anemometer or a wind vane.

## Final Layout
![Alt text](https://raw.githubusercontent.com/314-grp-301/314-grp-301.github.io/main/docs/assets/images/09-TeamPCBFinal.jpg)<br><br>
For better clarity of the top layout:<br>
(Bottom is mainly vertical connections by vias.)
### Top View
![image](https://github.com/314-grp-301/314-grp-301.github.io/assets/157048263/db2b12fa-09c0-40cf-a767-ec3c0fa53c64)

### Bottom View
![image](https://github.com/314-grp-301/314-grp-301.github.io/assets/157048263/8e617c77-c672-421d-b754-771e8cbdbf9e)




## DRC and Submissions for Manufacturing
![Alt text](https://raw.githubusercontent.com/314-grp-301/314-grp-301.github.io/main/docs/assets/images/09-Hardware%20Implementation.png)

## Cadence Screenshots of Final Team PCB
### Top View
![image](https://github.com/314-grp-301/314-grp-301.github.io/assets/157048263/1bb6312c-ce68-41f1-9e45-f6968db91e7f)
### Bottom View
![image](https://github.com/314-grp-301/314-grp-301.github.io/assets/157048263/3401403d-61e7-4be7-8671-d780e9d2e08c)

# Version 2.0
When analyzing the schematic for potential improvements in a "Version 2.0" of the hardware design, several areas can be considered to enhance functionality, reliability, and scalability. Here are some suggestions:

NEED TO ADD MORE HERE

1. Adding more ground headers, this would have helped connect any accessories to ground.
3. Mount the ESP32 onto the PCB. This would have given us a more secure and reliable connection.

## Power Supply Management
### Battery Life Optimization: 
While a 9V battery is currently used with a voltage regulator to power the circuit, battery life may be a limitation for long-term use. For Version 2.0, implementing a more efficient power management system with a rechargeable battery and a power-saving mode can significantly improve the device's operational time.

## Sensor Integration and Signal Conditioning
### Noise Reduction on Sensor Inputs: 
The temperature and humidity sensor signals could be susceptible to noise, particularly if the device is used in an industrial environment. Adding filters or shielded cabling could improve the accuracy and reliability of sensor readings.

## Communication Protocols
### Wi-Fi Signal Strength: 
If the ESP32 module experiences weak Wi-Fi signals in its operating environment, adding an external antenna connector could improve connectivity.

## Motor Driver and Control
### Current Sensing: 
Adding a current sensing circuit could provide feedback on the motor's health and workload, which would be useful for predictive maintenance.

## User Interface
### User Interface: 
If the current design does not include it, consider adding buttons or switches for manual override or control, which could be useful if wireless communication is temporarily unavailable.

## Documentation and Traceability
### Clear Labeling: 
Ensure all components are clearly labeled with their reference designators and values, which can be particularly important during assembly and troubleshooting.


By addressing these potential improvements, "Version 2.0" of the hardware design would likely be more robust, efficient, and user-friendly. Each change should be carefully considered in the context of the device's intended use, the environment it operates in, and the needs of the users to ensure that the modifications align with the overall goals of the project.<br><br>

[Previous](https://github.com/314-grp-301/314-grp-301.github.io/blob/main/Assignments/06-Microcontroller-Selection.md) - [Main Page](../README.md) - [Next](https://github.com/314-grp-301/314-grp-301.github.io/blob/main/Assignments/10-Software-Implementation.md)
