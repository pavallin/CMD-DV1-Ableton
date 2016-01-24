DV1_For_Ableton

A basic Script for the Behringer DV-1 on Ableton 9.5.

It is mostly based on the DC-1 script and is far from optimized. It contains several unused .py files and lots of commented code from the DC-1 script; I chose to keep everything, in order to make things more easily improved.

This is a Work In Progress, mostly experimental! Be warned :)

HOW IT WORKS:

The DV-1 behaves as an 8-track mixer. It displays and controls an 8x1 box of clips in Ableton.

FX1, FX2, FX3 and FX4 switch banks for the encoders and On/SEL / 1 / 2 / 3 buttons directly beneath each. This is hard coded: the encoders send different MIDI CC depending on which FX button is lit up.

FX1 encoders are for volume controls. FX2 and FX3 encoders are for respectively Send A and Send B controls. FX4 encoders are not assigned. You can freely manually map them, although they are low resolution and will be very slow.

ON/SEL, 1, 2 and 3 are not assigned. You can easily manually map them.

Focus, Master and Double also switch banks for the A, B, C and D buttons, hard coded as well.

When Focus is blue, A, B, C, D are for moving the box around. The selected tracks are modified by the encoders. When Master or Double is blue, the A, B, C, D buttons are not assigned.

Quantize buttons are not assigned (yet?). Slice, Erase, Store, Phrase are not assigned.

1, 2, 3, 4, 5, 6, 7, 8 are clip launchers corresponding to the box.

I would like to thank M. Piraux, who came up with the updated DC-1 script for 9.5! https://github.com/mpiraux/CMD-DC-1-Ableton-9-Control-Surface-Script

Enjoy! P.-A. Vallin

Known bugs:
 - The encoders rings don't light up when switching FX banks
 
 TODO :
  - Find a way to make the remaining encoders usable
  - Quantization
