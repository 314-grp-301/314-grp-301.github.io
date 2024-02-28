## Meet Team 301

<table>
  <tr>
    <td><img src="https://raw.githubusercontent.com/314-grp-301/314-grp-301.github.io/main/docs/assets/images/01-IMG_5207.jpg" width="75%" /></td>
    <td><img src="https://raw.githubusercontent.com/314-grp-301/314-grp-301.github.io/main/docs/assets/images/01-IMG_5204.jpg" width="75%" /></td>
  </tr>
  <tr>
    <td align="center">Brian Wegner [Electrical Systems & Organizational Leadership] </td>
    <td align="center">Fynn Meyerhoff [Robotics]</td>
  </tr>
  <tr>
    <td><img src="https://raw.githubusercontent.com/314-grp-301/314-grp-301.github.io/main/docs/assets/images/01-IMG_5205.jpg" width="75%" /></td>
    <td><img src="https://raw.githubusercontent.com/314-grp-301/314-grp-301.github.io/main/docs/assets/images/01-IMG_5206.jpg" width="75%" /></td>
  </tr>
  <tr>
    <td align="center">Xzekiel Trevino [Electrical Systems] </td>
    <td align="center">Kevis Seymore [Electrical Systems]</td>
  </tr>
</table>

## Problem Statement 
- In today's fast-paced world, companies have responded to the demand for real-time weather information, crucial for planning daily activities, by crowdsourcing data from numerous weather stations, which can result in varying accuracy depending on the user's location.

## Concept Design (Portable Weather POD)

![alt text](https://raw.githubusercontent.com/314-grp-301/314-grp-301.github.io/main/docs/assets/images/03-Concept_4.png)

**Description**

This portable weather pod accurately displays temperature and humdidity at a hyperlocal level in real time. The design is compact and strong, ensuring longevity and robustness even in demanding conditions.
The onboard LCD screen displays data from the two environmental sensors. 

:zap: **Key Features**

- **Portable:** Easy to move and install in various locations.
- **Weatherproof:** Designed to withstand harsh environmental conditions.
- **LCD Display:** Clear and informative data presentation.
- **WIFI Capable:** Uses the ESP32 chipset to transmit data to the net.
- **2 Key Sensors:** Multi-functional sensor for comprehensive environmental data.
  - **Temperature:** Measures ambient temperature accurately.
  - **Humidity:** Monitors air moisture levels.

## Selected Components

### 1 - Motor Driver(IFX9201SGAUMA1)
<img src="https://raw.githubusercontent.com/314-grp-301/314-grp-301.github.io/main/docs/assets/images/05-IFX9201SGAUMA1.jpg" width="500">

- System Lead: Kevis Seymore
- Rationale: The IFX9201SGAUMA1 motor controller has been recommended for similar use cases and has a thorough datasheet and support around it helping eliminate much of the guesswork when attaching it to a PCB or coding for it.

### 2 - Motor (LS-00028)
<img src="https://raw.githubusercontent.com/314-grp-301/314-grp-301.github.io/main/docs/assets/images/05-LS-00028.jpg" width="500">

- System Lead: Kevis Seymore
- Rationale: The LS-00028 motor offers the perfect balance of compact size and high efficiency, making it an excellent choice for our small scale project.

### 3 - Temperature Sensor (TC74A4)
<img src="https://raw.githubusercontent.com/314-grp-301/314-grp-301.github.io/main/docs/assets/images/05-TC74A4-3.3VCTTR.jpg" width="500">

- System Lead: Xzekiel Trevino
- Rationale: The TC74A4 temperature sensor is the ideal for our project based on price point, supporting documentation and fits within the expected voltage operating range of the project. While the sensor degrades in accuracy after 100F, the drop off is negligible within ranges it will be operating within.

### 4 - Humdidity Sensor (HIH6030)
<img src="https://raw.githubusercontent.com/314-grp-301/314-grp-301.github.io/main/docs/assets/images/05-HIH6030-021-001.jpg" width="500">

- System Lead: Brian Wegner
- Rationale: The HIH6030 Humidity Sensor was determined to be the best choice of the three components based on meeting all project requirements. This particular component further set itself apart from the crowd by having an extensive data sheet with example code, different schematic configurations, and having online support.

### 5 - LCD Screen (NHD-0216SZ-NSW-BBW-33V3)
<img src="https://raw.githubusercontent.com/314-grp-301/314-grp-301.github.io/main/docs/assets/images/05-MFG_NHD-0216SZ-NSW-BBW-33V3.jpg" width="500">

- System Lead: Brian Wegner/Xzekiel Trevino
- Rationale: Due to the simplistic nature and low voltage requirements, we believe this can display all our information in a small form factor. 

### 6 - Voltage Regulator (LM2575-3.3WU-TR)
<img src="https://raw.githubusercontent.com/314-grp-301/314-grp-301.github.io/main/docs/assets/images/05-LM2575-3.3WU-TR.jpg" width="500">

- System Lead: Fynn Meyerhoff 
- Rationale: The LM2575-3.3WU-TR is a good option because it offers a reliable 3.3V suitable for most microcontrollers. This was also the same regualtor used in an in-class activity. 

## Microcontroller Selection

| Feature      | **Option 1** :star: | Option 2     | Option 3     |
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

## Block Diagram
- Still Working on it...

## Schematic 
<img src="" width="500">

## Software Diagram

<img src="https://raw.githubusercontent.com/314-grp-301/314-grp-301.github.io/main/docs/assets/images/07-Software%20Proposal.png" width="1500">

## Questions

1. Question 1
2. Question 2
3. Question 3





