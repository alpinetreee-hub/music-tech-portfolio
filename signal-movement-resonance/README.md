# Signal, Movement, Resonance (2026)

A percussion instrument makes sound when something strikes a resonating surface. In this project I replaced the drumstick with digital impulses: my movements, tracked by a camera, trigger synthesized sounds that play through physical resonators instead of speakers.

**Demo video:** [Watch on YouTube](https://youtu.be/IPb4N0b2-nk)

## How it works
- **Amount of motion:** an algorithm measures pixel changes between video frames (frame differencing). Little motion keeps the hi-hat at half tempo with the melody muted; more motion doubles the hi-hat and brings in the melody.
- **Left-wrist height:** MediaPipe pose tracking in Max follows my left wrist. Three height zones (low, middle, high) choose the melody's pitch range.
- **Sound design:** three percussive sounds built from noise, plus one FM-synthesis melodic instrument, all in Max/MSP.
- **Resonators:** made from recycled materials (cardboard boxes, a $5 secondhand guitar body, and a tambourine), each with a speaker attached and driven by a power amplifier.

## Files
- `max-patches/`: Max/MSP and Jitter patches
- [`SignalMovementResonance_AmberShi.pdf`](SignalMovementResonance_AmberShi.pdf): project one-pager

## My role
I designed and built the whole project: the concept, the motion-tracking logic, the sound design, and the resonators.
