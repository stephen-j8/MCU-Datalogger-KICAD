# MCU-Datalogger-KICAD

## PROJECT OVERVIEW
MCU Datalogger — ATmega328P-based data logging PCB with DS1307 real-time clock, dual I²C EEPROM storage (24LC025 + 24LC1025), battery backup, UART/SPI/I²C breakout headers, and ICSP programming port. Designed in KiCad 10 on a 4-layer stackup. Includes full schematic, PCB layout, and Gerber files.

## CIRCUIT DETAILS
- ATmega328P-AU — 8-bit AVR MCU, 32KB Flash, 2KB SRAM, 1KB internal EEPROM
- DS1307 RTC — Real-time clock with battery backup (CR2032), accurate timekeeping even when power is off
- Dual I²C EEPROM — 24LC025 (2 Kbit) for config + 24LC1025 (1 Mbit / 128 KB) for data logging
- 16 MHz crystal — External clock for stable UART and precise timing
- 32.768 kHz crystal — Dedicated RTC oscillator (2¹⁵ Hz → 1 Hz via internal counter)
- Full I/O breakout — GPIO, UART, I²C, SPI headers for easy sensor/peripheral connection
- ICSP header — In-circuit programming without a bootloader
- 4-layer PCB — F.Cu / In1.Cu / In2.Cu / B.Cu stackup for clean power and signal integrity
- 4× mounting holes — M3, corner-placed for enclosure or standoff mounting

## TOOLS USED
  - SIMULATION-LTSpice
  - PCB(Schematic and layout capture)-KICAD
  - FABRICATION-JLCPCB

## FILES INCLUDED
  - GERBER FILES
  - LICENSE
  - PDF FILES
  - SCREENSHOTS
  - SOURCE FILES
  
## PCB PREVIEW
<img width="943" height="610" alt="Screenshot 2026-06-04 173231" src="https://github.com/user-attachments/assets/4b396605-57d0-4036-91cc-dffd080dfd5a" />

## SCHEMATIC PREVIEW
<img width="1912" height="1012" alt="Screenshot 2026-06-04 184722" src="https://github.com/user-attachments/assets/dc4fce05-097e-4af3-8ef1-c1761a4c792f" />

## BOM
<img width="326" height="415" alt="Screenshot 2026-06-04 194020" src="https://github.com/user-attachments/assets/78613c01-9b66-4ddf-8174-b8daf6ec102b" />

## STATUS
 - Schematic Captured  
 - PCB Layout Captured
 - GERBERS Generated
   
## AUTHOR

STEPHEN.J - PCB DESIGN ENGINEER
