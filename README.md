# ADF4158 + HMC391 PCB

This project is a PCB that contains an
[ADF4158](https://www.analog.com/en/products/adf4158.html) direct
modulation/waveform generating fractional-N frequency synthesizer and a
[HMC391](https://www.analog.com/en/products/hmc391.html) 3.9 - 4.45 GHz VCO. The
board is primarily intended as an LO source for a 10 GHz FMCW radar inspired by
the
[ADALM-PHASER](https://wiki.analog.com/resources/eval/user-guides/circuits-from-the-lab/cn0566/overview_setup). The
VCO output can be used with a subharmonic mixer and an IF around 1.6 GHz to
cover the 10 - 10.5 GHz amateur radio band.

The board runs from a 12 - 16 VDC supply, exposes all the control pins of the
ADF4158 in a 2.58 mm pin header (3.3V logic) and includes an optional 10 MHz
reference input. The BOM cost is around 45€.
