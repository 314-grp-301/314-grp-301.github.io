[Main Page](../Title.md)<br><br>
![image](https://github.com/314-grp-301/314-grp-301.github.io/assets/157048263/d787d03a-a66c-4c5f-943a-97104f14dbef)
# Block Diagram

## Key Components and Their Functions
### ESP32 Wifi Module
This module enables wireless connectivity, allowing the system to connect to the internet or a local network. This satisfies user needs for remote monitoring and control, and also meets the requirement for IoT connectivity.
### MQTT Server
Utilizing MQTT protocol for lightweight messaging facilitates efficient data transfer between devices and the server. This is crucial for applications where timely and reliable communication is needed, such as in automation or remote control environments.
### Temperature and Humidity Sensors
The integration of temperature (TC74A4-3.3VCTTR) and humidity (HIH6030-021-001) sensors meets the need for environmental monitoring. This feature is particularly beneficial in scenarios such as climate control in smart buildings or agricultural monitoring.
### Motor Driver (IFX9201SGAUMA1) and Brushed DC Motor (LS-00028)
These components are essential for actuation in robotic applications or any system requiring physical movement. They address requirements for mechanical operations controlled via software, which could include adjusting vents, windows, or other moving parts based on sensor inputs.
### Power Supply (9 Volt battery)
Providing a stable 3.3V power supply ensures that all low-power components operate reliably. This aligns with the need for efficient power management, crucial in portable or remote applications.
### High and Low Temperature Indicator Lights (HT_LED, LT_LED)
Indicator lights for temperature thresholds offer immediate visual feedback about the system state, which enhances usability and safety, meeting the user requirement for straightforward status indicators.
### Communication Protocols (I2C, SPI, UART)
Multiple communication protocols like I2C, SPI, and UART enable the system to interface with various peripherals and sensors efficiently. This flexibility in communication ensures that the system can be expanded or modified to meet changing user requirements or to integrate new technologies.
### PC1604 (LCD Display)
An LCD display to show real-time data or system statuses addresses the user need for interactive and accessible information. This is essential in environments where real-time feedback is crucial, such as in process control industries.
## Fulfillment of User Needs and Product Requirements
The block diagram shows a comprehensive approach to system design by incorporating sensors, actuators, communication modules, and user interfaces. Each component is chosen to ensure robust functionality that aligns with specific user needs:

### Remote Monitoring and Control: 
Through the ESP32 Wifi module and MQTT server, users can monitor and control the system remotely, which is vital for modern IoT applications.
### Environmental Sensing: 
The temperature and humidity sensors fulfill the requirement for environmental monitoring, crucial for maintaining optimal conditions in sensitive settings.
### User Interaction: 
The LCD display and indicator lights provide the user with immediate feedback and control, enhancing the system's usability and accessibility.
### Flexibility and Scalability: 
The use of standard communication protocols and modular components ensures that the system can be easily expanded or modified, providing scalability and adaptability to meet future needs.
In summary, the block diagram of Team 301's system is thoughtfully designed to address both the functional requirements of the product and the practical needs of the users. By integrating a range of sensors, actuators, and communication technologies, it provides a versatile and user-friendly solution.
