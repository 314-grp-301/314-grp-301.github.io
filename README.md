// Delete this section upon all tasks completion
- 07 Discuss how the software proposal functions and meets the needs of the product requirements
- 08 Discuss how the functionality of this schematic satisfies user needs and product requirements though an in depth discussion of function. Discuss your team's design and decision making process related to this section. Include the team's bill of materials in the appendix.
- 09
- 10
- 12
- 13
- 14
- Update code in code repository, [Code-Repository](https://github.com/314-grp-301/Team301Code/tree/main/folder) and put it in the appendix, bottom of the report.
- *Less important* Reorganize readme and table of contents into a more report style format.
- For Google Drive, ensure the appropriate files are in each assignment folder.
<br>// Delete this section upon all tasks completion
<br>
This is evidence of a recent commit for Checkpoint 3. Committed 0939 on 20240423.

## Table of Contents
[01-Team-Organization](https://github.com/314-grp-301/314-grp-301.github.io/blob/main/Assignments/01-Team-Organization-Charter.md)

[02-User-Needs-Benchmarking-and-Requirements](https://github.com/314-grp-301/314-grp-301.github.io/blob/main/Assignments/02-User-Needs-Benchmarking-and-Requirements.md)

[03-Design-Ideation](https://github.com/314-grp-301/314-grp-301.github.io/blob/main/Assignments/03-Design-Ideation.md)

[04-Block-Diagram](https://github.com/314-grp-301/314-grp-301.github.io/blob/main/Assignments/04-Block-Diagram.md)

[05-Component-Selection](https://github.com/314-grp-301/314-grp-301.github.io/blob/main/Assignments/05-Component-Selection.md)

[06-Microcontroller-Selection](https://github.com/314-grp-301/314-grp-301.github.io/blob/main/Assignments/06-Microcontroller-Selection.md)

[07-Software-Proposal](https://github.com/314-grp-301/314-grp-301.github.io/blob/main/Assignments/07-Software-Proposal.md)

[08-Hardware-Proposal](https://github.com/314-grp-301/314-grp-301.github.io/blob/main/Assignments/08-Hardware-Proposal.md)

[09-Hardware-Implementation](https://github.com/314-grp-301/314-grp-301.github.io/blob/main/Assignments/09-Hardware-Implementation.md)

[10-Software-Implementation](https://github.com/314-grp-301/314-grp-301.github.io/blob/main/Assignments/10-Software-Implementation.md)

[11-Innovation-Showcase-Poster](https://github.com/314-grp-301/314-grp-301.github.io/blob/main/Assignments/11-Innovation-Showcase-Poster.md)

[12-System-Verification](https://github.com/314-grp-301/314-grp-301.github.io/blob/main/Assignments/12-System-Verification.md)

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

### Introduction
This report serves as an interim status update for the ongoing progress of Team 301’s Portable Weather Station for EGR-314’s Spring 2024 semester. A documentary analysis of several past assignments have been condensed into a single source document for ease of reference. A more detailed breakout of each topic can be found by clicking the hyperlink headings for each chapter. Furthermore, a collection of past multimedia exhibits have been consolidated below.

### Problem Statement 
In today's fast-paced world, companies have responded to the demand for real-time weather information, crucial for planning daily activities, by crowdsourcing data from numerous weather stations, which can result in varying accuracy depending on the user's location.

## Concept Design (Portable Weather POD)

![alt text](https://raw.githubusercontent.com/314-grp-301/314-grp-301.github.io/main/docs/assets/images/03-Concept_4.png)

### Description:

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

### 1 - Motor Driver (IFX9201SGAUMA1)
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

## Power Budget

<img src="https://raw.githubusercontent.com/314-grp-301/314-grp-301.github.io/main/docs/assets/images/05-Power_Budget.PNG" width="1000">

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
<img src="https://raw.githubusercontent.com/314-grp-301/314-grp-301.github.io/main/docs/assets/images/Block%20Diagram%20Draft.png" width="1000">

## Schematic 
<img src="https://raw.githubusercontent.com/314-grp-301/314-grp-301.github.io/main/docs/assets/images/Team301Schematic-1.png" width="1000">

## Software Diagram

<img src="https://raw.githubusercontent.com/314-grp-301/314-grp-301.github.io/main/docs/assets/images/07-Software%20Proposal.png" width="1500">
