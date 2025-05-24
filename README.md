# Three-Phase-Full-Bridge-Inverter
Three-Phase Full-Bridge Inverter Simulation Using SPWM Modulation
This project simulates a three-phase full-bridge inverter using Sinusoidal Pulse Width Modulation (SPWM).

Control voltage frequency is set to 47.619 Hz.

Switching frequency is set to 1 kHz.

Thus, the modulation frequency ratio (fm) is 21, which only affects the harmonic frequencies, not their amplitude.

In our results:

Harmonic components at orders 1, 19, and 23 had amplitudes of 0.105, 0.0325, and 0.0336, respectively.

Increasing the switching frequency reduced the amplitude of the 1st harmonic and shifted the 19th and 23rd harmonics to higher frequencies, making them less visible.

(Note: At higher frequencies, the sawtooth waveform loses its ideal shape.)

Line density increased with switching frequency, resulting in more sinusoidal voltage outputs and lower current ripple.

When the modulation amplitude was increased to 1 (since the amplitude of the sawtooth waveform is 1, increasing the control voltage amplitude was sufficient):

Both output voltage and 1st harmonic amplitude increased.

Some transients appeared in the initial current cycle due to the sinusoidal reference exceeding the sawtooth waveform.

When the modulation amplitude exceeded 1, harmonics at 17 and 25 appeared with amplitudes of 0.0104 and 0.01028, respectively (at a 1 kHz switching frequency).
