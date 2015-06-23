# picstick_27j53
PIC18F27J53 Pinguino compatible USB stick

Construction
------------

![Completed PCB](https://github.com/kaza007/picstick_27j53/blob/master/construction/picstick_27j53_v1_construction_final.jpg)

[Components](https://github.com/kaza007/picstick_27j53/blob/master/construction/picstick_27j53_v1_components.jpg) are to be placed and soldered in the following order to make construction as easy as possible. 

![PartsOrder](https://github.com/kaza007/picstick_27j53/blob/master/construction/picstick_27j53_v1_construction.jpg)

Follow the image for the order of placement where each number corresponds to the instruction below.

For components that are not polarised, place them so that you can still read their markings. Resistors can be placed with colour codes reading left to right.

1. Place SW1, switch on the top side of the PCB. It does not matter in which direction it is placed. Solder.
2. Place C3, the polarised 10uF electrolytic capacitor on the top side of the PCB. The long lead of the component is the positive (+), and must be at the side of the plus sign on the PCB silkscreen (next to the X1 crystal). Also the white or black stripe on the side of the capacitor must be facing the switch. Solder and trim the leads.
3. Place X1, 8MHz crystal on the top side of the PCB.  It does not matter in which direction it is placed. Solder and trim the leads.
4. Place X2, 32.768kHz crystal on the bottom side of the PCB. Solder and trim the leads. At Step 9, Glue the crystal in a position where it does not contact the leads of X1.
5. Place C7, 10pF capacitor on the bottom side of the PCB. It does not matter in which direction it is placed. Solder and trim the leads.
6. Place U1, MCP1700 on the top side of the PCB. Ensure it is oriented as indicated by the PCB silkscreen. Also ensure its leads are bent so that the top of the component is as close as possible to the PCB. Solder and trim the leads.
7. Place one side of the pin-header connectors for U2 on the bottom side of the PCB. Solder.
8. Place the other side of the pin-header connectors for U2 on the bottom side of the PCB. Solder.
9. Glue the [X2 crystal in a position](https://github.com/kaza007/picstick_27j53/blob/master/construction/picstick_27j53_v1_X2_position.jpg)
 where it does not contact the leads of X1. Up against the side of the pin-header is a good position.
10. Place R2, 10K resistor on the top side of the PCB. It does not matter in which direction it is placed. Solder and trim the leads.
11. Place R3, 100R resistor on the top side of the PCB. Solder and trim the leads.
12. Place D1, Red LED on the top side of the PCB. The LED is a polarised part so the long lead must face the R4 resistor. Solder and trim the leads.
13. Place C1, 100nF capacitor on the top side of the PCB. It does not matter in which direction it is placed. Solder and trim the leads.
14. Place R1, 470R resistor on the top side of the PCB. Solder and trim the leads.
15. Place C4, 22pF capacitor on the top side of the PCB. It does not matter in which direction it is placed. Solder and trim the leads.
16. Place C5, 22pF capacitor on the top side of the PCB. It does not matter in which direction it is placed. Solder and trim the leads.
17. Place C6, 10pF capacitor on the top side of the PCB. It does not matter in which direction it is placed. Solder and trim the leads.
18. Place C2, 100nF capacitor on the top side of the PCB. It does not matter in which direction it is placed. Solder and trim the leads.
19. Place JP2, 14 way pin header on the top side of the PCB. Solder the leads.
20. Place JP1, 14 way pin header on the top side of the PCB. Solder the leads.
21. Place U2, the PIC18F27J53 microcontroller in its socket on the bottom side of the PCB. This will be easier if you first bend the two rows of pins a little bit in towards each other. Note that the microcontroller chip has a notch at one end. This notch must be at the end where the U2 is on the PCB silkscreen.
