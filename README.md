<div align="center">

# atmegaStepperDriver  
  Open source stepper driver powered by Atmega chip

## Quick Description
This project was design to be used in my [Modul3D](https://github.com/eGuardianDev/Modul3D) project.
Now It has its own project.  
The idea to have simple, cheap, open source stepper driver for stepper motor

## Features and design   
- Powered by Atmega chip (at the moment Atmega328)  
- H-Bridge design  
- Flyback Voltage protection  
- Standart stepper driver communication  
- I2C communcation interface
- Fan controll


<img src="PCB/Schematic Design.png">
<img src="PCB/3D View.png">

## Current Development
### Firmware
 - [ ] Todo...
### Hardware
#### Power
- [X] Power supply for the chip
- [X] Sepreate connection for power for the motor
- [X] Pins for power
#### Main system
- [X] H-bridge configuration
- [X] Connect the pins to the transistor of H-bridge
- [X] Calculate transistor resistor values
#### Communication
- [X] Pins for communication
- [X] I2C pins
- [X] Address Changer
- [ ] Step mode (maybe in next version or firmware based)
#### Protection
- [X] Add capacitor before transitor for smooth curves, but don't test it
- [X] Flyback protection (with ziner diode) 
- [X] Power supply smoothing and return diode
- [ ] Fully test protection system
#### Misc.
- [X] Change diode foot print

## Notes
Not sure if the 16 bit timer is going to be used.
Failed 2 orders ;-;
</div>

