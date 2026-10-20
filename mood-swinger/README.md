# Mood Swinger (2026)

A 3D-printed brain model that works as a music controller. Research suggests the two hemispheres contribute differently to how we hear music; Mood Swinger turns a simplified version of that idea into an instrument: the left hemisphere plays rhythm and the right plays melody.

**Demo video:** [Watch on YouTube](https://youtu.be/d3exvBy8LnI)

## How it works
- **Inputs:** capacitive touch sensors on the brain turn the drums and melody voices on and off. Three knobs control the mood (happy, angry, confused), the tempo, and the cutoff of a low-pass filter.
- **Hardware:** the controls are wired to a Seeed Studio XIAO ESP32-S3, programmed in the Arduino IDE, which sends the data to Max/MSP over serial.
- **Sound:** each mood has two melody voices with its own waveform (triangle, square, sine) and harmony interval, plus its own kick and hi-hat from Ableton Live's sample library.
- **Light:** an LED changes color with the mood and blinks with the tempo.

## Files
- `arduino/`: microcontroller code
- `max-patches/`: Max/MSP patches
- [`MoodSwinger_AmberShi.pdf`](MoodSwinger_AmberShi.pdf): project poster with signal-flow diagram

## My role
I designed the concept, programmed the microcontroller and the Max/MSP system, and built the hardware.
