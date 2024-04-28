[Previous](https://github.com/314-grp-301/314-grp-301.github.io/blob/main/Assignments/03-Design-Ideation.md) - [Main Page](../README.md) - [Next](https://github.com/314-grp-301/314-grp-301.github.io/blob/main/Assignments/05-Component-Selection.md)<br>
[Navigation](https://github.com/314-grp-301/314-grp-301.github.io/blob/main/docs/Navigation.md)<br><br>
# Block Diagram
A block diagram is a visual representation of the components and connections within a system or device. It is illustrated through simplified blocks and lines allowing for quick interpretation of how different subsystems rely upon one another. In the context of our Weather Pod project, the block diagram provides a comprehensive overview of the key subsystems and their interconnections.

The diagram illustrates all the key subsystems of the Weather Pod device. The setup was determined by the selected sensor components and their communication protocols. We needed the temperature sensor, humidity sensor, and motor driver to communicate with the microcontroller's limited availability of I2C and SPI pins. Initially, this posed a challenge as the MCU could only support two I2C devices and an SPI device, necessitating multiple devices to share a pin. However, this issue was resolved through software and coding solutions by implementing recognition and communication with different addresses for the devices.
<br>

![My Image](https://github.com/314-grp-301/314-grp-301.github.io/blob/94c1ec2a3d79e22bc545b0e7d56bc2cf8a57e224/docs/assets/images/04-Block%20Diagram.png)<br><br>

[Previous](https://github.com/314-grp-301/314-grp-301.github.io/blob/main/Assignments/03-Design-Ideation.md) - [Main Page](../README.md) - [Next](https://github.com/314-grp-301/314-grp-301.github.io/blob/main/Assignments/05-Component-Selection.md)


