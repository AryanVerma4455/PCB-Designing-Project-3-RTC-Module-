# PCB-Designing-Project-3(RTC Module)
In this series for beginners, we continue learning PCB designing using KiCad with our next project: an RTC (Real-Time Clock) Module. This project focuses on designing an accurate time-keeping circuit from scratch, starting from schematic capture to PCB layout. The RTC module is designed to maintain precise date and time even during power failure using a backup battery.

The design includes a two-layer PCB and follows basic PCB designing principles. It covers proper component selection (such as an RTC IC like DS3231/DS1307, crystal oscillator if required, coin cell holder for backup battery, pull-up resistors for I²C communication), schematic connections, footprint assignment, component placement, and routing to ensure stable communication and minimal noise. Special attention is given to crystal placement and power routing for accurate timekeeping performance.

All components are clearly referenced, and standard PCB design keywords and conventions are followed. In this project, we also explain how to generate manufacturing files (Gerber files, drill files, BOM) and how to order the PCB from manufacturers such as JLCPCB and EasyEDA, with options for different board colors, with or without component soldering, and full customization according to project requirements.

This project helps beginners understand low-power design, I²C communication layout considerations, and battery-backed circuit design while improving practical PCB designing skills.

keyword

1.Gerber File
A Gerber file is the standard file format used to manufacture PCBs. It contains detailed information about each PCB layer (copper, solder mask, silkscreen, etc.) and is sent to the PCB manufacturer for fabrication.

2️.Ground Plane
A Ground Plane is a large copper area connected to GND on the PCB. It helps reduce electrical noise, improve signal integrity, and provide a low-resistance return path for current.

3️.Trace Width
Trace Width refers to the width of copper tracks on the PCB. It is important because it determines how much current a trace can safely carry without overheating.

key Components:

1.Component
| component     | quantity |   
|---------------|----------|
| Temp Sensor   | 01       |   
| conn 1x5      | 01       |  
| +5            | 04       |   
| GND           | 06       |   
| Crystal       | 01       |   
| SDA           | 01       |   
| SCL           | 01       |   
| AT24C501-55HM | 01       |   
| CR2032        | 01       |   
| resister      | 02       |   
|                          |

2.Schematic Diagram

3.Footprint Assignment

4.PCB Routing

5.Component Placement

6.Routing

7.Final PCB in 3d viewer

8.Gerber File and Drill file

9.Ordering PCBs from manufacturers such as JLCPCB and EasyEDA, with full customization options (board color, soldering, and assembly)
