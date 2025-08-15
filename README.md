# Nanoka DC-DC Power Module

![KiCad 3D render](assets/3d-render.png)

This is a power module designed for Project Nanoka. It's based on a Low-Dropout 5V regulator because of its noise-filtering properties, which is important for audio.

It has a very basic circuit. A simple tantalum filtering capacitor, a TVS diode for clamping voltage spikes, a regular rectifying diode for backflow protection, a buffer capacitor at the output, and of course, the regulator itself.

This is not user friendly in anyway, and it's intended for my own personal use only. If you do decide to reproduce it, you do so **at your own responsibility**.

Theoretically, when used with a heatsink, this module can output one amps of five volts, so 5W total. The regulator is capable of one and a half amps but the rectifying diode is rated for 1 amp, so this is the limit.


