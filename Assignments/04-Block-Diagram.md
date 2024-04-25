[Main Page](../Title.md)<br><br>
# Block Diagram
Depicted is a diagram of all the key subsystems of the the weather pod device. The determining factors for the setup were the devices chosen and the communication types for said devices. We needed the temperature sensor, humidity sensor, and motor driver to communicate with the microcontroller's limited I2C and SPI pins. This proved difficult, originally, as while the MCU had the capability to support two I2C devices and an SPI device to do so required multiple devices to share a pin. This was resolved on the software side by recognizing and communicating with different addresses for the devices.<br>

![My Image](https://raw.githubusercontent.com/314-grp-301/314-grp-301.github.io/main/docs/assets/images/Block%20Diagram%20Draft.png)


