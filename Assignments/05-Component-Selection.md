## 1 - Motor Driver
- System Lead: Kevis Seymore
- Choice: **(Option 3)** BD6211F-E2
- Rationale: The ROB-12859 motor controller has been recommended for similar use cases and has a thorough datasheet and support around it helping eliminate much of the guesswork when attaching it to a PCB or coding for it.
#### Motor Solution - 1: BD6211F-E2
<img src="/path/to/myimage.png" width="200">
**Cost:** $2.19 per unit

| Pros                                       | Cons                 |
|--------------------------------------------|----------------------|
| Extensive datasheet                        | Costly per unit      |
| Utilizes standard SPI                      | Footprint not provided |
| Additional support files provided          |                      |
| High precision sensorless motor load detection |                    |

#### Motor Solution - 2: BD6210F-E2
<img src="/path/to/myimage.png" width="200">
**Cost:** $2.46 per unit

| Pros                                         | Cons                  |
|----------------------------------------------|-----------------------|
| Daughter board comes soldered                | Costly per unit       |
| Built-in thermal shutdown                    | Datasheet is minimalistic |
| CW/CCW/short-brake/stop motor control modes  | Footprint provided    |

#### Motor Solution - 3: ROB-12859
<img src="/path/to/myimage.png" width="200">
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

#### Motor Solution - 1: ROB-10846
<img src="/path/to/myimage.png" width="200">
- **Cost:** $19.50 per unit

| Pros                                     | Cons                             |
|------------------------------------------|----------------------------------|
| Recommended for use with ROB-12859       | Minimalistic datasheet           |
| High resolution steps (400 per revolution) | Round shaft requires press fit or clamp |
| Low voltage required                     |                                  |

#### Motor Solution - 2: ROB-09238
<img src="/path/to/myimage.png" width="200">
- **Cost:** $18.79 per unit

| Pros                                  | Cons                                  |
|---------------------------------------|---------------------------------------|
| Slightly lower price compared to ROB-10846 | Minimalistic datasheet              |
| 18.76 gcm^2 rotor inertia             | Lower resolution (200)               |
|                                       | High voltage required (12V)           |
|                                       | Round shaft requires press fit or clamp |

#### Motor Solution - 3: FIT0278
<img src="/path/to/myimage.png" width="200">
- **Cost:** $13.95 per unit

| Pros                                      | Cons                                     |
|-------------------------------------------|------------------------------------------|
| Low voltage required                      | Schematic not provided in datasheet      |
| Termination with connector and leads provided allowing for removal and/or easier installation and maintenance | Round shaft requires press fit or clamp |

#### Motor Solution - 4: 4641
<img src="/path/to/myimage.png" width="200">
- **Cost:** $12.50 per unit

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

#### Temp Sensor Solution - 1: TPIS 1S 1385 / 5029
<img src="/path/to/myimage.png" width="200">
**Cost:** $13.63 per unit

| Pros                                  | Cons                                         |
|---------------------------------------|----------------------------------------------|
| Power Range: 2.6V ~ 3.6V              | Expensive                                    |
| Digital, IR                           | Many features outside the scope of the project and not required |
| Ambient and/or object heat detection  |                                              |

#### Temp Sensor Solution - 2: AT30TSE004A-MAA5M-T
<img src="/path/to/myimage.png" width="200">
**Cost:** $1.32 per unit

| Pros                                     | Cons                                         |
|------------------------------------------|----------------------------------------------|
| ±1C accuracy (40-90F)                    | Accuracy degrades after 95F                  |
| Temp Conditional Emergency Alarm/Shutoff | ±3.0°C accuracy (maximum) over the -20°C to +125°C range |

#### Temp Sensor Solution - 3: LM75BDP,118
<img src="/path/to/myimage.png" width="200">
**Cost:** $0.91 per unit

| Pros                                  | Cons                              |
|---------------------------------------|-----------------------------------|
| Cheap price point                     | Accuracy degrades after 100F      |
| Extensive Data sheet and support documents |                                  |
| 2.8-5V operating range                |                                   |
| ±2C accuracy                          |                                   |



