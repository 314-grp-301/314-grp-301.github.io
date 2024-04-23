[Main Page](../Title.md)<br><br>
![image](https://github.com/314-grp-301/314-grp-301.github.io/assets/157048263/fcb4f8ad-a3de-492a-8247-efdf7fee3705)

# Software Diagram

## Key Functions and Processes
### Initialization and Setup
The system begins with an initialization phase where it configures various communication protocols (I2C2, SPI1, EUSART1) and sets up initial variables. This ensures that all components are ready to function correctly, providing a stable starting point which is critical for reliable operations.
### Temperature and Humidity Sensing
Temperature and humidity sensors collect environmental data. The temperature data is converted to Fahrenheit, and humidity data is translated into relative humidity (RH), which are standard units easily understandable and useful for most applications, satisfying the need for intuitive data presentation.
### Data Processing and Transmission
Once collected, the sensor data is sent to the main controller (MC), where it is further processed and formatted as a string. This data is then transmitted through EUSART to the ESP32 module, allowing for remote data monitoring and analysis, catering to the need for accessibility and connectivity in modern systems.
### Motor Control System
The motor's operation is directly linked to temperature readings. If the temperature is 85°F or higher, the motor is turned on (presumably to activate cooling mechanisms), and if it's below 85°F, the motor is turned off. This automated response system is crucial for maintaining optimal conditions automatically, reducing manual intervention and increasing system efficiency.
### Indicator Lights
High temperature indicator light (HT_LED) is controlled based on temperature thresholds: set high when the temperature is 85°F or above and low otherwise. This visual feedback is vital for immediate status recognition, enhancing the user interaction with the system.
### Error Handling and Feedback Loop
The system includes mechanisms to continuously check and respond to the operational parameters. This loop ensures the system behaves as expected and can handle errors or unexpected changes in environmental conditions effectively.

## Fulfillment of User Needs and Product Requirements
The software diagram demonstrates a comprehensive approach to integrating various technologies to meet both user needs and technical product requirements:

### Automated Environmental Control: 
The system automatically adjusts its operations (e.g., turning the motor on/off) based on real-time temperature data, ensuring maintenance of desired environmental conditions.
### Real-Time Monitoring and Alerts: 
Through sensors and indicator lights, the system provides real-time feedback, crucial for applications requiring constant monitoring, such as in agricultural or industrial settings.
### Remote Access and Control: 
Data transmission capabilities to the ESP32 module allow for remote monitoring and adjustments, which is a significant advantage in enhancing system accessibility and usability, especially in distributed networks.
### Reliability and Stability: 
The initialization and continuous operational checks ensure the system remains stable and reliable, which is essential for critical applications where errors can have significant consequences.
In conclusion, the functionality described in Team 301's software proposal effectively addresses specific user needs such as automated environmental control, real-time data monitoring, remote system access, and reliability. By leveraging modern sensors, communication protocols, and control mechanisms, the system achieves a high level of efficiency and user-friendliness, meeting the overarching goals of the product requirements.

### Revisions to Software Diagram (Previous --> Current)

- Removed toggle button interrupt 
- Removed Fahrenheit to Celsius conversion
- Removed motor hatch logic  
- Added Humidity and Temp sensor to the while(1) loop
- Added HT and LT LED logic 
- Display updates every 2.5 seconds instead of 15

# Version 2.0
For a "Version 2.0" of the software design, we can focus on enhancing modularity, maintainability, efficiency, and robustness. Here’s how we might consider updating the software flow based on the existing UML diagram:

## Modular Code Design
### Functional Decomposition: 
Divide the code into more functions, each handling a specific task. For instance, have separate functions for sensor data acquisition, data processing, communication, motor control, and indicator management. This approach not only makes the code more readable but also easier to debug and test.

## Improved Debuggability
### Logging System: 
Implement a logging system that captures detailed operational data and errors. This could include timestamped entries for sensor readings, system states, errors, and actions taken by the control systems.
### Self-Diagnostics: 
Build in self-test routines that check the status of sensors and other peripherals at startup and during operation, reporting any malfunctions.

## Protocol Design Improvements
### Standard Protocols: 
Where possible, use standard communication protocols and libraries to ensure compatibility and reliability.
### Communication Timeouts: 
Implement timeouts and retries for communication protocols to handle lost connections or failed transmissions gracefully.

## System Stability and Functionality
### State Machine: 
Implement a finite state machine for managing system states and transitions, which can simplify the control logic and make the system's operation more predictable.

## Graphical Representation of the Updated Software Flow
The updated software flow could be represented using a state diagram or flowchart. This would visually describe the system states, transitions based on events (like temperature thresholds), and the actions taken in each state.

In conclusion, improving the software design for Version 2.0 involves enhancing the modularity of the code, introducing a robust error-handling and logging system, utilizing system peripherals for increased reliability, and refining the communication protocols. These improvements would make the software more robust, stable, and maintainable, leading to a system that can meet the demands of its intended use more effectively.
