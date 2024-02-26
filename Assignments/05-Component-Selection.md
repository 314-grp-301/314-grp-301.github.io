## 1 - Motor Driver
- System Lead: Kevis Seymore
- Choice: **(Option 3)** BD6211F-E2
- Rationale: The ROB-12859 motor controller has been recommended for similar use cases and has a thorough datasheet and support around it helping eliminate much of the guesswork when attaching it to a PCB or coding for it.
### Driver Solution - 1: BD6211F-E2
<img src="https://raw.githubusercontent.com/314-grp-301/314-grp-301.github.io/main/docs/assets/images/05-BD6211F-E2.jpg" width="200">
**Cost:** $2.19 per unit

| Pros                                       | Cons                 |
|--------------------------------------------|----------------------|
| Extensive datasheet                        | Costly per unit      |
| Utilizes standard SPI                      | Footprint not provided |
| Additional support files provided          |                      |
| High precision sensorless motor load detection |                    |

### Driver Solution - 2: BD6210F-E2
<img src="https://raw.githubusercontent.com/314-grp-301/314-grp-301.github.io/main/docs/assets/images/05-bd6210f-e2.jpg" width="200">
**Cost:** $2.46 per unit

| Pros                                         | Cons                  |
|----------------------------------------------|-----------------------|
| Daughter board comes soldered                | Costly per unit       |
| Built-in thermal shutdown                    | Datasheet is minimalistic |
| CW/CCW/short-brake/stop motor control modes  | Footprint provided    |

### Driver Solution - 3: ROB-12859
<img src="https://raw.githubusercontent.com/314-grp-301/314-grp-301.github.io/main/docs/assets/images/05-ROB-12859.jpg" width="200">
**Cost:** $21.50 per unit

| Pros                                         | Cons                         |
|----------------------------------------------|------------------------------|
| Recommended by Digikey support for I2C stepper motor use | Costly per unit              |
| Extensive documentation                      | Would take up more space than needed on PCB |
| Built-in thermal shutdown                    |                              |
| Short to ground protected                    |                              |
---

## Component 2 - Motor
- System Lead: Kevis Seymore
- Choice: Option 1: ROB-10846
- Rationale: All the motors listed are appropriate 2-phase steppers, but option 1 comes recommended and has the highest accuracy in steps per revolution.

### Motor Solution - 1: ROB-10846
<img src="https://raw.githubusercontent.com/314-grp-301/314-grp-301.github.io/main/docs/assets/images/05-ROB-10846.jpg" width="200">
**Cost:** $19.50 per unit

| Pros                                     | Cons                             |
|------------------------------------------|----------------------------------|
| Recommended for use with ROB-12859       | Minimalistic datasheet           |
| High resolution steps (400 per revolution) | Round shaft requires press fit or clamp |
| Low voltage required                     |                                  |

### Motor Solution - 2: ROB-09238
<img src="https://raw.githubusercontent.com/314-grp-301/314-grp-301.github.io/main/docs/assets/images/05-ROB-09238.jpg" width="200">
**Cost:** $18.79 per unit

| Pros                                  | Cons                                  |
|---------------------------------------|---------------------------------------|
| Slightly lower price compared to ROB-10846 | Minimalistic datasheet              |
| 18.76 gcm^2 rotor inertia             | Lower resolution (200)               |
|                                       | High voltage required (12V)           |
|                                       | Round shaft requires press fit or clamp |

### Motor Solution - 3: FIT0278
<img src="https://raw.githubusercontent.com/314-grp-301/314-grp-301.github.io/main/docs/assets/images/05-FIT0278.jpg" width="200">
**Cost:** $13.95 per unit

| Pros                                      | Cons                                     |
|-------------------------------------------|------------------------------------------|
| Low voltage required                      | Schematic not provided in datasheet      |
| Termination with connector and leads provided allowing for removal and/or easier installation and maintenance | Round shaft requires press fit or clamp |

### Motor Solution - 4: 4641
<img src="https://raw.githubusercontent.com/314-grp-301/314-grp-301.github.io/main/docs/assets/images/05-4641.jpg" width="200">
**Cost:** $12.50 per unit

| Pros                                      | Cons                                     |
|-------------------------------------------|------------------------------------------|
| Compact: Ideal for space-limited applications. | Limited Torque: May struggle with high power or heavy loads. |
| Precision Control: Offers fine adjustments in speed and torque. | Wear and Tear: Gearbox can wear out, especially under heavy use. |
| Energy Efficient: Suitable for battery-powered projects. | Noise: Gear meshing can produce undesirable noise. |
---
## Component 3 - Temperature Sensor
- System Lead: Xzekiel Trevino
- Choice: Option 3: M75BDP,118
- Rationale: The LM75BDP,118 temperature sensor is the ideal for our project based on price point, supporting documentation and fits within the expected voltage operating range of the project. While the sensor degrades in accuracy after 100F, the drop off is negligible within ranges it will be operating within.

### Temp Sensor Solution - 1: TPIS 1S 1385 / 5029
<img src="https://raw.githubusercontent.com/314-grp-301/314-grp-301.github.io/main/docs/assets/images/05-TPIS-1S-1385.jpg" width="200">
**Cost:** $13.63 per unit

| Pros                                  | Cons                                         |
|---------------------------------------|----------------------------------------------|
| Power Range: 2.6V ~ 3.6V              | Expensive                                    |
| Digital, IR                           | Many features outside the scope of the project and not required |
| Ambient and/or object heat detection  |                                              |

### Temp Sensor Solution - 2: AT30TSE004A-MAA5M-T
<img src="https://raw.githubusercontent.com/314-grp-301/314-grp-301.github.io/main/docs/assets/images/05-AT30TSE004A-MAA5M-T.jpg" width="200">
**Cost:** $1.32 per unit

| Pros                                     | Cons                                         |
|------------------------------------------|----------------------------------------------|
| ±1C accuracy (40-90F)                    | Accuracy degrades after 95F                  |
| Temp Conditional Emergency Alarm/Shutoff | ±3.0°C accuracy (maximum) over the -20°C to +125°C range |

### Temp Sensor Solution - 3: LM75BDP,118
<img src="https://raw.githubusercontent.com/314-grp-301/314-grp-301.github.io/main/docs/assets/images/05-LM75BDP.jpg" width="200">
**Cost:** $0.91 per unit

| Pros                                  | Cons                              |
|---------------------------------------|-----------------------------------|
| Cheap price point                     | Accuracy degrades after 100F      |
| Extensive Data sheet and support documents |  ±2C accuracy                                |
| 2.8-5V operating range                |                           |
---
## Component 4 - Humidity Sensor
- System Lead: Brian Wegner
- Choice: Option 2: BPS240-D2P0-S10E
- Rationale: The HIH6030 Humidity Sensor was determined to be the best choice of the three components based on meeting all project requirements. This particular component further set itself apart from the crowd by having an extensive data sheet with example code, different schematic configurations, and having online support.

### Humidity Sensor Solution - 1: SHT40-AD1B-R2
<img src="https://raw.githubusercontent.com/314-grp-301/314-grp-301.github.io/main/docs/assets/images/05-SHT40-AD1B-R2.jpg" width="200">
**Cost:** $2.58 per unit

| Pros                                       | Cons                                       |
|--------------------------------------------|--------------------------------------------|
| Accurate ±1.8%                             | Will require power converters if system operates higher than 3.6V |
| Low Power 1.08v - 3.6V                     | Small Component                            |
| Surface Mount                              |                                            |
| Digital Sensor                             |                                            |
| Operates in AZ extreme heat conditions     |                                            |
| I2C Serial                                 |                                            |
| GitHub Support                             |                                            |

### Humidity Sensor Solution - 2: BPS240-D2P0-S10E
<img src="https://raw.githubusercontent.com/314-grp-301/314-grp-301.github.io/main/docs/assets/images/05-BPS240-D2P0-S10E.jpg" width="200">
**Cost:** $5.78 per unit

| Pros                                      | Cons                                     |
|-------------------------------------------|------------------------------------------|
| Surface Mount                             | Higher Power Requirement 1.62v - 5.5v    |
| Digital Sensor                            | 30 second response time                  |
| Operates in AZ extreme heat conditions    |                                          |
| I2C Serial                                |                                          |
| GitHub Support                            |                                          |

### Humidity Sensor Solution - 3: HIH6030
<img src="https://raw.githubusercontent.com/314-grp-301/314-grp-301.github.io/main/docs/assets/images/05-HIH6030-021-001.jpg" width="200">
**Cost:** $13.43 per unit

| Pros                                      | Cons                                     |
|-------------------------------------------|------------------------------------------|
| Surface Mount                             | Expensive                                |
| Most Accurate                             | Higher Power Requirement 2.7v - 5.5v     |
| Example code and setup in Data Sheet      |                                          |
---
## Component 5 - LCD Screen
- System Lead: Brian Wegner/Xzekiel Trevino
- Choice: Option 3: MD21605G12W3-BNMLW-VE
- Rationale: Due to the simplistic nature and close acquaintance with this component, we believe this can display all our information without the headache of learning other complex display layouts in the short timeframe. It also has a relatively small form factor and low cost. 

### LCD Solution - 1: 64128K COG FA BW
<img src="https://raw.githubusercontent.com/314-grp-301/314-grp-301.github.io/main/docs/assets/images/05-64128K%20COG%20FA%20BW.jpg" width="200">
**Cost:** $12.28 per unit

| Pros                            | Cons                                    |
|---------------------------------|-----------------------------------------|
| 128 x 64 display                | Tight pin layout, difficult soldering   |
| Small (56 x 39 x 8.5mm)         | May require additional drivers          |
| Light Weight: 1 oz              | Expensive solution                      |
| Power: 3V                       |                                         |

### LCD Solution - 2: NHD-C12864LZ-FSW
<img src="/path/to/myimage.png" width="200">
**Cost:** $17.64 per unit

| Pros                                     | Cons                                 |
|------------------------------------------|--------------------------------------|
| 128 x 64 display                         | Bad Resolution                       |
| Fastest Response Time/least lag from input to screen update | Most Expensive Solution             |
| Largest Viewing Area: 70 x 40 mm         | High backlighting may require more power |

### LCD Solution - 3: MD21605G12W3-BNMLW-VE
<img src="/path/to/myimage.png" width="200">
**Cost:** $4.77 per unit (min order 5)

| Pros                       | Cons                                   |
|----------------------------|----------------------------------------|
| Easy to program            | Limited to 2x16 characters             |
| Sample Code Available      | No images                              |
| Can make custom fonts      | Unable to order small batch (2-3 units)|
---
## Component 6 - Power Switch Regulator (Microcontroller)
- System Lead: Fynn Meyerhoff
- Choice: Option 1: LM2575T-3.3
- Rationale: The LM2575T-3.3 is a good option  because it offers adjustable voltage, including the very common 3.3V, which is great for lots of electronics. This makes it versatile since we can have flexibility with other components. Plus, we've already built a voltage regulator with this part so we know how it works. 

### Power Regulator Solution - 1: LM2575-3.3WU-TR
<img src="/path/to/myimage.png" width="200">
**Cost:** $3.77 per unit


| Pros                                              | Cons                                        |
|---------------------------------------------------|---------------------------------------------|
| Versatile with a wide input voltage range.        | Lower current capacity compared to some newer designs. |
| Capable of driving a 1.0A load.                   | Requires several external components.       |
| Available in various fixed and adjustable output versions. | Might be less efficient than newer alternatives. |

### Power Regulator Solution - 2: LM2596S-5.0
<img src="/path/to/myimage.png" width="200">
**Cost:** $6.81 per unit

| Pros                                          | Cons                                          |
|-----------------------------------------------|-----------------------------------------------|
| Reliable performance with good thermal management. | Larger size compared to newer regulators.     |
| Wide input voltage range.                     | Lower switching frequency might not be ideal for all applications. |
| Built-in thermal shutdown and current limit features. | Fixed 5.0V output limits flexibility unless using an adjustable version. |

### Power Regulator Solution - 3: MP1584EN-LF-Z
<img src="/path/to/myimage.png" width="200">
**Cost:** $2.81 per unit

| Pros                                      | Cons                                             |
|-------------------------------------------|--------------------------------------------------|
| High efficiency in conversion.            | Potentially noisier output due to high switching frequency. |
| Compact size, suitable for space-constrained applications. | Might require additional filtering for sensitive applications. |
| High current capability (up to 3A).       | Limited by a maximum input voltage of 28V.        |

