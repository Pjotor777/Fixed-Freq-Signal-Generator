# Fixed Frequency Signal Generator
## Abstract
A basic analog signal generator circuit that generates the 4 fundamental waveforms (Square, Sine, Triangular and Sawtooth). The generator was built using only passive components (resistors, capacitors and diodes) and operational amplifiers. The generator has a fixed frequency (phase locked) at 1 kHz.

The project has 3 phases (no pun intended!): 
1. Theoretical learning and design via LTspice (Current phase, 99% complete).
2. Prototyping in a laboratory environment.
3. Developing the hardware as a PCB via KiCad.

### Contents
There are 2 files containing the circut. The first one: 'multi-wave-osc' is the basic 'default' circuit built with LTspice's Universal Opamp 2 components. The second one 'multi-wave-sc-lt1364' is the 'main' circuit for testing and prototyping. Fundamentally, they are the same circuit but with some minor differences to account for the behavior of the op-amps used.

Work in progress: more info will be added shortly along with the project updates.

## Functionality
### Square Wave Generator
Work in progress
### Sine Wave Generator
Work in progress
### Triangle Wave Generator
Work in progress
### Sawtooth Wave Generator
Work in progress

## Images
All relevant images can be found in the 'images' folder. The folder contains images of the 2 circuits, the waveform outputs of each oscillator (outputs based off the 'main circuit') and the spectrum analysis (FFT plots) of all waveforms together.

## Future Work
Once the project is (at least, mostly) complete, I plan on possibly making a 'version 2' of the signal generator, including more robust methods of waveform generation, using potentiometers to allow for lower and higher frequencies (and amplitudes? if that is even possible) and more advanced waveforms found in modern signal generators.