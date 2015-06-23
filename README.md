# picstick_27j53
PIC18F27J53 Pinguino compatible USB stick

Background
------------

The picstick_27j53 is a small PCB that can be connected directly into a USB connector. It is based on the [LeoStick (Arduino Compatible)](http://www.freetronics.com.au/products/leostick#.VWqnws-qpHw) form factor and the hardware is identical to the [PIC18F47J53 Pinguino](http://wiki.pinguino.cc/index.php/PIC18F47J53_Pinguino) except that the 28pin PIC is used instead of the 40pin.

The picstick_27j53 was created to add to the ever growing choice of PIC alternatives to Arduino. There are no surface mount components, so the picstick_27j53 is easy to build.

Construction
-----------------
Parts are to be placed and soldered in the following order to make construction as easy as possible.

1. Place SW1, switch on the top side of the PCB. It does not matter in which direction it is placed. Solder.
2. Place C3, the polarised 10uF electrolytic capacitor on the top side of the PCB. The long lead of the component is the positive (+), and must be at the side of the plus sign on the PCB silkscreen (next to the X1 crystal). Also the white or black stripe on the side of the capacitor must be facing the switch. Solder and trim the leads.
3. Place X1, 8MHz crystal on the top side of the PCB. Solder and trim the leads.
4. Place X2, 32.768kHz crystal on the bottom side of the PCB. Solder and trim the leads. Glue the crystal in a position where it does not contact the leads of X1.
5. Place C7, 10pF capacitor on the bottom side of the PCB. This capacitor is not polarised, so it does not matter in which direction it is placed, but it makes sense to place it so that you can still read its markings. Solder and trim the leads.
6. Place U1, MCP1700 on the top side of the PCB. Ensure it is oriented as indicated by the PCB silkscreen. Also ensure its leads are bent so that the top of the component is as close as possible to the PCB. Solder and trim the leads.
7. Place one side of the pin-header connectors for U2 on the bottom side of the PCB. Solder.
8. Place the other side of the pin-header connectors for U2 on the bottom side of the PCB. Solder
9. Place R3, 10K resistor on the top side of the PCB. This resistor is not polarised, so it does not matter in which direction it is placed, but it makes sense to place it so that you can still read its markings. Solder and trim the leads.
10. Place R4, 100R resistor on the top side of the PCB. Solder and trim the leads.
11. Place D1, Red LED on the top side of the PCB. The LED is a polarised part so the long lead must face the R4 resistor. Solder and trim the leads.
12. Place C1, 100nF capacitor on the top side of the PCB. This capacitor is not polarised, so it does not matter in which direction it is placed. Solder and trim the leads.
13. Place R2, 470R resistor on the top side of the PCB. Solder and trim the leads.
14. Place C4, 22pF capacitor on the top side of the PCB. This capacitor is not polarised, so it does not matter in which direction it is placed. Solder and trim the leads.
15. Place C5, 22pF capacitor on the top side of the PCB. This capacitor is not polarised, so it does not matter in which direction it is placed. Solder and trim the leads.
16. Place C6, 10pF capacitor on the top side of the PCB. This capacitor is not polarised, so it does not matter in which direction it is placed. Solder and trim the leads.
17. Place C2, 100nF capacitor on the top side of the PCB. This capacitor is not polarised, so it does not matter in which direction it is placed. Solder and trim the leads.
18. Place JP2, 14 way pin header on the top side of the PCB. Solder the leads.
19. Place JP1, 14 way pin header on the top side of the PCB. Solder the leads.
20. Place the PIC18F27J53 microcontroller in its socket on the bottom side of the PCB. This will be easier if you first bend the two rows of pins a little bit in towards each other. Note that the microcontroller chip has a notch at one end. This notch must be at the end where the U2 is on the PCB silkscreen.

PIC Bootloader
-----------------
The PIC18F27J53 must be programmed with the Pinguino Bootloader as described in the Pinguino [Basics](http://wiki.pinguino.cc/index.php/Basics#Bootloader) page.

Design Software
-----------------
This project was designed with [Eagle](http://www.cadsoftusa.com/) 7.2.0, [Sketchup](http://www.sketchup.com/) 15.3.331 and [EagleUp](http://eagleup.wordpress.com) 4.5.

License
-------
![CC-BY-SA Logo](https://i.creativecommons.org/l/by-sa/4.0/88x31.png)

This work is licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License](<http://creativecommons.org/licenses/by-sa/4.0/).

Original design by: [Pinguino](http://www.pinguino.cc/).

Modified by: [*https://github.com/kaza007*](https://github.com/kaza007)