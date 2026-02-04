# Logic Gate–Based Digital Visitor Counter

## Overview
This project is a Digital Visitor Counter designed using pure digital logic circuits without any microcontroller.  
The system automatically detects and counts visitors entering or exiting a monitored area using laser and LDR sensor pairs and displays the count in real time.

## Objective
- Automatically count visitors entering and exiting a space
- Display the visitor count using 7-segment displays
- Provide visual indicators for Entry, Exit, and Full conditions
- Replace manual counting with a reliable electronic system

## System Description
- Laser–LDR sensor pairs detect beam interruptions for entry and exit
- Sensor signals are conditioned using a Schmitt trigger to reduce noise
- Up/down counter ICs increment or decrement the visitor count
- 7-segment displays show the current number of visitors
- LEDs indicate Entry, Exit, and Full capacity conditions
- A regulated 5V DC supply powers the entire system

## Components Used
- CD40110 Up/Down Counter IC
- CD4093 Quad NAND Schmitt Trigger IC
- Logic Gate ICs (AND / NAND)
- Laser modules
- LDR sensors
- Common cathode 7-segment displays
- LEDs (Entry, Exit, Full)
- 7805 voltage regulator
- Resistors and capacitors

## Tools & Software
- EasyEDA – schematic and PCB design
- Proteus – circuit simulation
- TinkerCAD – basic simulation
- Multimeter – testing and validation

## Testing & Results
- Tested under different ambient lighting conditions
- Verified correct increment and decrement operation
- Confirmed stable signal processing using Schmitt triggers
- Validated LED indicators for Entry, Exit, and Full states

## Challenges & Solutions
- Sensor noise reduced using signal conditioning
- Ambient light interference minimized by proper sensor placement
- Power stability improved using decoupling capacitors

## Future Improvements
- Add wireless communication for remote monitoring
- Expand system to support multiple entry and exit points
- Integrate data logging functionality

## My Contribution
- Circuit design and logic implementation
- Sensor calibration and testing
- Signal conditioning and troubleshooting
- Technical documentation

## Project Status
Completed
