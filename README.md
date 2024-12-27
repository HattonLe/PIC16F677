# PIC16F677
A Free PIC16F677 Development platform

Don't throw out that FireAngel CO-9B Carbon Monoxide Alarm
just because its died due to its 7 year expiry date for the gas sensor.

Instead use it as a development platform for a PIC16F677 project!

I have reversed engineered the circuit schematic using Kicad 8.

A few of the ICs are unknown as I have been unable to identify the
SMD marking codes for them (so my schematic shows current best guesses
for those SOT-23-5 packages).

I'm still trying to figure out how the actual detection mechanism works
so the upper half of the schematic isn't quite laid out logically as it should be.

The PIC16F677 is recognised by a PicKit-4 interface.
It just needs PicKit pins 1-5 connecting to the pads on the PCB. The manufacturer
has kindly silk screened the required pads already!
Note desolder the pad bridge silk screened as "PR".

The microcontrollers firmware is code locked so you can't download it.
(The included firmware intel hex file just contains all zeros).

For info, the expired gas sensor I have measured at ~29k Ohms.
