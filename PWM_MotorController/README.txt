Controls the power provided to a DC motor through PWM control.  There are two
halves to the circuit, the digital half records the speed-setting and allows 
the user to increment it, the other half is the analog circuit that allows a 
digital input to modify pulse width.  This means no microcontroller is used
and a single digital oscillator can provide a number of different pulse 
widths (also some fine-tuning is possible through resistor values).
