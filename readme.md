<img src="images/microchiptechnologyinc.png" height="60">

# AVR128DA48 LED Dimming with PWM Example

This repository provides an Atmel Studio solution with a bare metal code example for an LED dimming implemented using a PWM signal.

The example demonstrates the basic functionality of the PWM peripheral. The output waveform is connected to the on-board LED. The PWM duty cycle value is incremented continuously until it reaches the maximum value and then is reloaded to 0. This produces the dimming effect of the LED.

## Configurations

- PC6 - configured as digital output (the on-board user LED)
- TCA1:
  * Single-slope PWM Mode
  * Compare channel 2 enabled
  * Input clock 4Mhz

<img src="images/AVR128DA48_CNANO_instructions.PNG" height="250">

## Required Tools

- Atmel Studio 7.0.2397 or newer
- AVR-Dx 1.0.18 or newer Device Pack
- AVR128DA48 Curiosity Nano (DM164151)

## Compatibility
The source code is compatible with the following devices: AVR128DA28, AVR128DA32, AVR128DA48, and AVR128DA64.
