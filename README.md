# QAZ Build Guide Rev 1.0
## Introduction
{{ Insert nice intro to QAZ here }}

Important notes to keep in mind:

 - The side of the PCB with art on it is the "back" side of the PCB

## Materials
### Required
| Material | Qty |
|--|--|
| QAZ PCB | 1 |
| QAZ Switch Plate | 1 |
| QAZ Back Plate | 1 |
| Diodes (Through-hole or SMD)| 36
| ProMicro (or ProMicro Equivalent) | 1
| MX Switches | 35 or 36
| Stabilizers | 2x2u or 1x6.25u
| Standoffs | 4
| M2 Screws | 8
| M2 Washers | 4
| MX Compatible Keycaps | 35 or 36

### Optional
| Material | Qty |
| -- | -- |
| MillMax Sockets | 20
| MillMax Pins | 20
| Painter's Tape | 1

![Materials](static/IMG_1362.HEIC)

## Preparations
### Diodes
If you are using through-hole diodes, you will want to clip the diodes from the roll that they're on. You can do so using flush-cutters (highly recommended) or any cutting tool.

Once you have clipped the diodes, bend the legs at a 90 degree angle.

### (Optional) MillMax Sockets
Although you do not need to socket your ProMicro, it is highly recommended to do so. This will allow you to avoid having to desolder the entire MCU if the port breaks off. Typically, these sockets come in rows of 64. As such, you will want to clip two sections off - one 12 socket row and one 8 socket row.

## Building
### Place the diodes
Although this guide uses through-hole diodes, the steps here are the same for SMD diodes.

**Please make sure that you are placing these diodes in the correct orientation.** 

This is, probably, one of the most common issues when building a keyboard. In the following image, you can see the appropriate orientation of the diode.

As can be seen above, the black bar on the diode **must** be pointing towards the **square** pad. Please be careful when placing the diodes and make sure that you are following this rule for every diode. 

**The square pad is not always to the right of the diode.**

For SMD diodes, you can solder the diode directly to the diode footprint.

For through-hole diodes, feed the legs through the holes to the left and the right of the diode footprint.  As can be seen in the following photo, you should bend the legs of the through-hole diodes so that they are held in place while you place more diodes.

Once you have placed a row (or more) of diodes, solder the legs of said diodes diodes on the front-side of the PCB.

Repeat until you have soldered all of the diodes in place.

### MCU (ProMicro) soldering
This guide uses MillMax sockets; however, you can replace these with the regular MCU headers if you choose to do so. The most important thing to keep in mind here is that the four holes on the bottom-left of the MCU footprint should be left free. Otherwise, you may run into issues with soldering switches in place.


