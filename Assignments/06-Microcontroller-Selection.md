**Microcontroller Selection**

| Feature | **Option 1** ★ | Option 2    | Option 3    |
|---------|----------------|-------------|-------------|
| Part #  | **PIC16F15354**| PIC16F1517  | PIC18F47K42 |
| GPIO (21)    | **22**         | 33          | 33          |
| ADC (1)    | **24**         | 28          | 35          |
| PWM (1)    | **4**          | 0           | 4           |
| I2C (2)     | **2**          | 1           | 2           |
| UART (0)    | **1**          | 1           | 2           |

Choice: Option 1

Reasons:

- Low power consumption
- MCC compatible
- Meets project requirements


| Feature                                          | Project Requirements | PIC16F15354 | PIC16F1517 | PIC18F47K42 |
|--------------------------------------------------|----------------------|-------------|------------|-------------|
| How many GPIO Pins?                              | 21                   | 22          | 33         | 33          |
| Built-in Analog to Digital Converter? How many?  | 1                    | 24          | 28         | 35          |
| Built-in Hardware PWM? How many?                 | 0-1                  | 4           | 0          | 4           |
| Built-in I2C? SPI? How many?                     | (2 I2C’s), no SPI’s  | 2           | 1          | 2           |
| Built-in UART? How many?                         | 0                    | 1           | 1          | 2           |
| Other Required Built-In Features? (optional)    | TBD                  |             |            |             |
| Additional considerations specific to your project specifications (optional) | Low Power Mode? |  |  |  |

| Information                                 | PIC Option 1     | PIC Option 2 | PIC Option 3 |
|---------------------------------------------|------------------|--------------|--------------|
| Part Number                                 | PIC16F15354      | PIC16F1517   | PIC18F47K42   |
| Link to product page                        | [Product Page Link](www.google.com) | [Product Page Link]() | [Product Page Link]() |
| Link to Data Sheets                         | [Data Sheets]()  | [Data Sheets]() | [Data Sheets]() |
| Link to Application Notes                   | [Notes]()        | [Notes]()    | [Notes]()    |
| Link to Code Examples                       | [Code Examples]()| [Code Examples]() | [Code Examples]() |
| Link to External Resources                  | [External Resources]() | [External Resources]() | [External Resources]() |
| Production Unit Cost                        | $1.39            | $2.29        | $3.48        |
| Supply Voltage Range                        | Vdd(min) = +2.3V, Vdd(max) = +5.5V | Vdd(min) = +2.3V, vdd(max) = +5.5V | Vdd(min) = +2.3V, vdd(max) = +5.5V |
| Absolute Maximum Current for entire IC      | Vss = 350 mA, Vdd = 250 mA | Vss = 350 mA, Vdd = 350 mA | Vss = 350 mA, Vdd = 350 mA |
| Maximum GPIO Pin Current (Source/Sink)      | ± 40 mA          | ± 50mA       | ± 50mA       |
| 8-bit or 16-bit Architecture                | 8 bit            | 8 bit        | 8 bit        |
| Available IC Packages / Footprints          | S(PDIP), SOIC, SSOP, QFN, UQFN | PDIP, UQFN | PDIP, UQFN, TQFP, QFN |
| Supports External Interrupts?               | Yes              | Yes          | Yes          |
| In-System Programming Capability and Type   | Yes, ICSP        | Yes, ICSP    | Yes, ICSP    |
| Works with MPLAB® X Integrated Development Environment (IDE)? | Yes | Yes | Yes |
| Works with Microchip Code Configurator?     | MCC Classic works | MCC Classic works | MCC Classic works |

