An opamp board with attenuating pots on inputs to:

* scale -5/+5V control voltage signals down to a voltage-referenced 0-2.5v range for reading by a Teensy's ADCs.
* scale up output from Teensy's DAC (and a Teensy PWM output with a low-pass RC filter) to -5/+5V range.

![Schematic](/teensy-cv-schematic.png)

![PCB](/teensy-cv-pcb.png)

Note: output op amp configuration is inverting, which must be compensated for in code.
