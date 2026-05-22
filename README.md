# blinky
Little led board that uses a 555 timer to clock a decade counter.

## Functionality
The NE555 is in AStable mode which creates a PWM signal that feeds into the CD4017, the PWM output is adjustable through the potentiometer, the CD4017 has 10 output pins which turn on sequentially every time it recieves a clock pulse, on our PCB this means that the leds will turn on after another in a circular pattern.

## BOM
- 1x NE555 Timer
- 1x CD4017 Decade counter
- 1x Potentiometer
- 2x Capacitors
- 2x Resistors
- 10x LED's

## Photos

<img width="1821" height="1163" alt="image" src="https://github.com/user-attachments/assets/d7c25726-66b3-42b1-a951-63f9f9437b6b" />

<img width="1968" height="1351" alt="image" src="https://github.com/user-attachments/assets/f09e840e-cc4d-4695-a3dc-54bd4045ff19" />



