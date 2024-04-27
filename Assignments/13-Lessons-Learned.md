[Previous](https://github.com/314-grp-301/314-grp-301.github.io/blob/main/Assignments/12-System-Verification.md) - [Main Page](../README.md) - [Next](https://github.com/314-grp-301/314-grp-301.github.io/blob/main/Assignments/14-Recommendations.md)<br>
[Navigation](https://github.com/314-grp-301/314-grp-301.github.io/blob/main/docs/Navigation.md)<br><br>

# Lessons Learned

- When selecting a microcontroller, make sure you have a solid understanding of all the pins' capabilities in I2C and SPI.
- Prioritize using components the person in charge of them has had experience using before or has similarities to components they have experience with.
- Due to individual device addresses, multiple I2C devices can effectively communicate along the same input and output pins.
- Having as many device inputs and outputs print to Putty can dramatically increase the effectiveness of the debugging stage of development.
- Ensure dimensions of parts are checked thoroughly before being ordered as parts being too small may be an issue when soldering.
- The layout of a PCB can be kept cleaner by designating layers as the primary horizontal or vertical movement layers and using via to transition between them.
- When noise is not a significant issue, you can minimize trace length by centralizing power buses to be used by various components.
- Separate components in PCB layout enough to make soldering simple, while meeting total PCB size restrictions.
- Group subsystem components in the PCB layout for better clarity and eases of recognition when soldering and testing subsystem connectivity.
- If noise is a potential issue for a problem that arises, try jumping to a breadboard and adding different size capacitors to pull some of it to ground. If that works, implement the changes for a cleaner signal.
<br><br>

[Previous](https://github.com/314-grp-301/314-grp-301.github.io/blob/main/Assignments/12-System-Verification.md) - [Main Page](../README.md) - [Next](https://github.com/314-grp-301/314-grp-301.github.io/blob/main/Assignments/14-Recommendations.md)
