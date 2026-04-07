	# Power Distribution Board — Requirements

## Overview
A power distribution board that accepts 12V input and provides regulated 
5V and 3.3V outputs with current sensing on the 5V rail.

## Electrical Requirements
- Input voltage: 12V DC
- Output 1: 5V / 2A (buck converter)
- Output 2: 3.3V / 500mA (LDO regulator)
- Current sensing: INA219 on 5V rail

## Protection
- Reverse polarity protection on input
- Thermal shutdown via IC

## Physical Requirements
- Form factor: ~50mm x 70mm
- Connectors: screw terminals (input), pin headers (output)

## Success Criteria
- [ ] 5V output within ±2% under load
- [ ] 3.3V output within ±2% under load
- [ ] Current sensing readable over I2C
- [ ] Board survives 1A continuous on 5V rail for 10 minutes