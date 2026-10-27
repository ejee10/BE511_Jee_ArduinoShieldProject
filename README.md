<!-- kicad_template/README.md -->

# BE511 Arduino Analog Shield

KiCad 10 schematic and PCB layout for a 4-channel analog I/O shield for the Arduino Uno, designed for BE511 Biomedical Instrumentation (Fall 2026, Boston University).

## Design Summary

- **Analog inputs (4):** MCP3204 12-bit ADC, 0–5 V range, each input with a 1 kΩ / 3 nF RC low-pass filter (~50 kHz cutoff)
- **Analog outputs (4):** two MCP4922 12-bit dual DACs, 0–5 V range
- **Interface:** SPI to the Arduino Uno (SCK, COPI, CIPO, CS0–CS2, LDAC, SHDN)
- **Connectors:** screw terminals and 2x5 headers for inputs and outputs

## File Structure

- `/kicad/` contains the KiCad 10 project files
- `/datasheets/` contains datasheets for key components
- `/calculations/` contains component value calculations
- `/cad/` contains mechanical files, if any

## Author

Elisa Jee

*Project template courtesy of E. Hazen / BU Mars Rover Club.*
