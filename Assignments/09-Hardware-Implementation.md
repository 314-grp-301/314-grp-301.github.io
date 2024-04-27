[Previous](https://github.com/314-grp-301/314-grp-301.github.io/blob/main/Assignments/06-Microcontroller-Selection.md) - [Main Page](../Title.md) - [Next](https://github.com/314-grp-301/314-grp-301.github.io/blob/main/Assignments/10-Software-Implementation.md)<br><br>

# Hardware Implementation

## Final Schematic
![Alt text](https://raw.githubusercontent.com/314-grp-301/314-grp-301.github.io/main/docs/assets/images/Team301Schematic-1.png)<br><br>

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

[Previous](https://github.com/314-grp-301/314-grp-301.github.io/blob/main/Assignments/06-Microcontroller-Selection.md) - [Main Page](../Title.md) - [Next](https://github.com/314-grp-301/314-grp-301.github.io/blob/main/Assignments/10-Software-Implementation.md)
