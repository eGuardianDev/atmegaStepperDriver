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

## Current Development
### Hardware
#### Power
- [X] Power supply for the chip
- [X] Sepreate connection for power for the motor
- [X] Pins for power
#### Main system
- [X] H-bridge configuration
- [ ] Connect the pins to the transistor of H-bridge
- [X] Calculate transistor resistor values
#### Communication
- [ ] Pins for communication
- [ ] I2C pins
- [ ] Address Changer
- [ ] Step mode
#### Protection
- [X] Add capacitor before transitor for smooth curves, but don't test it
- [X] Flyback protection (with ziner diode) 
- [ ] Power supply smoothing and return diode
- [ ] Fulling test protection system
#### Misc.
- [X] Change diode foot print

## Notes
Not sure if the 16 bit timer is going to be used.
</div>

