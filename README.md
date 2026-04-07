# Power Distribution Board

A PCB designed to accept 12V DC input and provide regulated 5V and 3.3V 
outputs with real-time current sensing. Designed from scratch using KiCad.

## Features
- 12V input with reverse polarity protection
- 5V / 2A output via buck converter
- 3.3V / 500mA output via LDO regulator
- Real-time current sensing on 5V rail via INA219 over I2C

## Project Status
- [x] Requirements defined
- [ ] Schematic complete
- [ ] PCB layout complete
- [ ] Gerbers submitted for fabrication
- [ ] Board assembled and tested

## Tools Used
- KiCad 8 — schematic and PCB layout
- Python — INA219 readout script
- JLCPCB — PCB fabrication

## Motivation
Designed as a portfolio project to demonstrate full hardware life-cycle 
experience: requirements capture, schematic design, PCB layout, fabrication, 
bring-up, and test.