<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works

This project is a combinational circuit that decodes BCD code to a 7-segment display. The circuit counts from 0 to 15, displaying the values in decimal (0–9) and hexadecimal (0–F). Additionally, an extra bit is included to control the decimal point (DP) on the 7-segment display.

## How to test
1. Apply power to the circuit.

2. Feed the BCD inputs (4 bits) with values from 0000 to 1111 (0 to 15).

3. Observe the 7-segment display: it should show 0–9 for the first ten combinations and A–F for the remaining six.

4. Toggle the extra control bit to turn the decimal point on and off.

5. Verify that each input combination produces the correct segment pattern on the display.

## External hardware

* 7-segment display (common anode or common cathode, depending on your design)

* BCD input switches or signal source (4 bits)

* 1 extra control bit (switch or signal) for the decimal point

* Current-limiting resistors for the 7-segment display

* (Optional) PMOD or FPGA board, if applicable
