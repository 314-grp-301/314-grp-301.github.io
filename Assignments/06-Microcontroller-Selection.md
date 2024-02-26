## Microcontroller Selection

| Feature      | **Option 1** ★ | Option 2     | Option 3     |
|--------------|----------------|--------------|--------------|
| **Part #**   | **PIC16F15354**| PIC16F1517   | PIC18F47K42  |
| **GPIO**     | **22 (21 req)**| 33           | 33           |
| **ADC**      | **24 (1 req)** | 28           | 35           |
| **PWM**      | **4 (1 req)**  | 0            | 4            |
| **I2C/SPI**  | **2/0**        | 1/0          | 2/0          |
| **UART**     | **1 (0 req)**  | 1            | 2            |

**Choice: Option 1**

<img src="https://raw.githubusercontent.com/314-grp-301/314-grp-301.github.io/main/docs/assets/images/06-PIC16F15354.png" width="300">

**Reasons:**

- Low power consumption
- MCC compatible
- Meets project requirements
---
## Design Considerations 

| Feature                                      | Project Requirements | PIC16F15354 | PIC16F1517 | PIC18F47K42 |
|----------------------------------------------|----------------------|-------------|------------|-------------|
| **How many GPIO Pins?**                      | 21                   | 22          | 33         | 33          |
| **Built-in Analog to Digital Converter?**    | 1                    | 24          | 28         | 35          |
| **Built-in Hardware PWM?**                   | 0-1                  | 4           | 0          | 4           |
| **Built-in I2C? SPI?**                       | 2 I2C’s, no SPI’s    | 2           | 1          | 2           |
| **Built-in UART?**                           | 0                    | 1           | 1          | 2           |
| **Other Required Built-In Features?**        | TBD                  |             |            |             |
| **Additional considerations (Low Power Mode?)** | ?                  |             |            |             |

## Microcontroller Considerations

| Information                             | PIC Option 1                                                                 | PIC Option 2                                                               | PIC Option 3                                                               |
|-----------------------------------------|------------------------------------------------------------------------------|----------------------------------------------------------------------------|----------------------------------------------------------------------------|
| **Part Number**                         | PIC16F15354                                                                  | PIC16F1517                                                                 | PIC18F47K42                                                                |
| **Link to product page**                | [Product Page Link](https://www.microchip.com/en-us/product/PIC16F15354)     | [Product Page Link](https://www.microchip.com/en-us/product/pic16f1517)   | [Product Page Link](https://www.microchip.com/en-us/product/pic18f47k42)  |
| **Link to Data Sheets**                 | [Data Sheets](https://www.mouser.com/datasheet/2/268/PIC16F_LF_15354_55_Data_Sheet_40001853D-2885845.pdf) | [Data Sheets](https://ww1.microchip.com/downloads/aemDocuments/documents/OTH/ProductDocuments/DataSheets/40001452F.pdf) | [Data Sheets](https://ww1.microchip.com/downloads/aemDocuments/documents/MCU08/ProductDocuments/DataSheets/PIC18%28L%29F26-27-45-46-47-55-56-57K42-Data-Sheet-40001919G.pdf) |
| **Link to Application Notes**           | [Notes](https://www.microchip.com/en-us/application-notes)                 | [Notes](https://www.microchip.com/en-us/application-notes)               | [Notes](https://www.microchip.com/en-us/application-notes)               |
| **Link to Code Examples**               | [Code Examples](https://www.microchip.com/en-us/code-examples)             | [Code Examples](https://www.microchip.com/en-us/code-examples)           | [Code Examples](https://www.microchip.com/en-us/code-examples)           |
| **Link to External Resources**          | [External Resources](https://www.instructables.com/Programming-PIC-Microcontrollers/) | [External Resources](https://www.instructables.com/Programming-PIC-Microcontrollers/) | [External Resources](https://www.instructables.com/Programming-PIC-Microcontrollers/) |
| **Production Unit Cost**                | $1.39                                                                       | $2.29                                                                     | $3.48                                                                     |
| **Supply Voltage Range**                | Vdd(min) = +2.3V, Vdd(max) = +5.5V                                          | Vdd(min) = +2.3V, vdd(max) = +5.5V                                        | Vdd(min) = +2.3V, vdd(max) = +5.5V                                        |
| **Absolute Maximum Current for entire IC** | Vss = 350 mA, Vdd = 250 mA                                                  | Vss = 350 mA, Vdd = 350 mA                                                | Vss = 350 mA, Vdd = 350 mA                                                |
| **Maximum GPIO Pin Current (Source/Sink)** | ± 40 mA                                                                    | ± 50mA                                                                    | ± 50mA                                                                    |
| **8-bit or 16-bit Architecture**         | 8 bit                                                                       | 8 bit                                                                     | 8 bit                                                                     |
| **Available IC Packages / Footprints**   | S(PDIP), SOIC, SSOP, QFN, UQFN                                              | PDIP, UQFN                                                                | PDIP, UQFN, TQFP, QFN                                                     |
| **Supports External Interrupts?**        | Yes                                                                         | Yes                                                                       | Yes                                                                       |
| **In-System Programming Capability**     | Yes, ICSP                                                                   | Yes, ICSP                                                                 | Yes, ICSP                                                                 |
| **Works with MPLAB® X IDE?**             | Yes                                                                         | Yes                                                                       | Yes                                                                       |
| **Works with Microchip Code Configurator?** | MCC Classic works                                                            | MCC Classic works                                                         | MCC Classic works                                                         |
---
## Microcontroller Detailed Requirements

**GPIO Pins Required: 17** (Excluding debug LED’s!)
- [2] Temperature Sensor (LM75BDP,118) - Digital
  - Serial Data Line (SDA)
  - Serial Data Clock (SCL)
- [2] **Humidity Sensor (HIH6030-021-001)** - Digital
  - Serial Data Line (SDA)
  - Serial Data Clock (SCL)
- [4] **Motor Driver (IFX9201SGAUMA1CT-ND)** - Digital
  - SCK
  - CSN
  - SI
  - SO
- [7] **LCD Screen (3086-MD21605G12W3-BNMLW-VE-ND)** Assuming 8-bit mode:
  - DB0-DB7 (4 pins Data Bus Line)
  - RS (1 pin for Register Select)
  - R/W (1 pin for Read and Write)
  - E (1 pin for Enable)
- [2] **ESP32 Wireless Receiver**
  - RX
  - TX

**Built-in Analog to Digital Converter: 1**
- All sensors and drivers are digital, but including 1 ADC is advisable for potential future needs.

**Built-in Hardware PWM: 1**
- Required for the Motor Driver to control motor speed.

**Built-in I2C & SPI: 2 I2C’s & 0 SPI’s**
- I2C interfaces: 2 (Temp & Humid sensor can be addressed differently through the same bus)
- SPI interfaces: Not required for this project.

**Built-in UART: 0**
- Humid/Temp Sensor: Communicate via I2C or SPI, not UART.
- Motor Driver: Uses digital signals for control, not UART.
- LCD Screen: Uses a parallel or I2C/SPI interface, not UART.

