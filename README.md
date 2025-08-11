# Atlas Scientific EZO Carrier Board

## Overview
A professional carrier board designed for Atlas Scientific EZO circuit boards, featuring full electrical isolation and integrated SMA connectors for reliable sensor connectivity.

Based on the [Atlas Scientific Electrically Isolated EZO Carrier Board Gen 2](https://atlas-scientific.com/carrier-boards/electrically-isolated-ezo-carrier-board-gen-2/), this design provides enhanced isolation and connectivity features for demanding applications.

### Design Improvements
This prototype incorporates several component upgrades from the reference design:
- **SI8600AC-B-ISR digital isolators** for improved signal integrity and isolation performance
- **RFM-0505S power modules** for reliable isolated power delivery
- **1206 package components** for easier hand assembly and prototype testing

## Features
- **4 EZO Circuit Slots**: Supports up to 4 Atlas Scientific EZO circuit boards simultaneously
- **Full Electrical Isolation**: Complete galvanic isolation between each EZO circuit to prevent ground loops and interference
- **Integrated SMA Connectors**: Professional-grade SMA connectors for secure and reliable probe connections
- **Modular Design**: Easy installation and removal of EZO circuits without soldering

## Supported EZO Circuits
This carrier board is compatible with the full range of Atlas Scientific EZO circuits including:
- pH
- ORP (Oxidation-Reduction Potential)
- Dissolved Oxygen
- Conductivity
- Temperature (RTD)
- Flow
- CO2
- Pressure
- Humidity
- And more...

## Technical Specifications
- **Isolation**: Full galvanic isolation between channels
  - **Digital Isolator**: SI8600AC-B-ISR (Silicon Labs) - High-speed digital isolator for I2C/UART signals (4x units)
  - **Power Isolation**: RFM-0505S - Isolated DC/DC converter module (5V to 5V, 4x units)
- **Connectors**: 
  - SMA female connectors (132289) for probe connections (4x)
  - JST XH 4-pin connector for I2C input
  - Pin headers for EZO circuit connections
- **Communication**: I2C/UART pass-through for each isolated channel
- **Power**: Isolated power supply for each EZO circuit
- **Protection**: BVSS138LT1G MOSFETs for level shifting and protection (4x)
- **Component Package**: 1206 series resistors and capacitors for easier prototype assembly and testing
  - 10kΩ pull-up resistors (10x)
  - 1MΩ resistors (8x)
  - 1µF capacitors (8x)
  - 470Ω LED resistor with power indicator

## Applications
- Water quality monitoring systems
- Hydroponics and aquaponics automation
- Industrial process control
- Environmental monitoring stations
- Research and development
- Educational laboratories

## Design Files
This repository contains:
- PCB design files (KiCad)
- Schematic diagrams
- [Bill of Materials (BOM)](Atlas_Scientific_Carrier_Board.csv) - Complete component list with quantities and specifications
- 3D models
- Manufacturing files (Gerbers)

## Safety & Compliance
- Designed with electrical safety in mind
- Full isolation prevents ground loops
- Protected against cross-channel interference
- Industrial-grade components

## License
[License information to be added]

## References & Documentation
- [Atlas Scientific Electrically Isolated EZO Carrier Board Gen 2](https://atlas-scientific.com/carrier-boards/electrically-isolated-ezo-carrier-board-gen-2/) - Original carrier board reference
- [Carrier Board Technical Datasheet (PDF)](https://files.atlas-scientific.com/electrically-isolated-ezo-carrier-board.pdf) - Detailed specifications and wiring diagrams
- [Atlas Scientific EZO Circuit Documentation](https://atlas-scientific.com/circuits/) - Complete EZO circuit specifications
- [Atlas Scientific Support](https://atlas-scientific.com/support/) - Technical support and resources

## Contact
For questions, support, or custom modifications, please open an issue in this repository.

---
*Professional carrier board solution for Atlas Scientific EZO circuits with enhanced isolation and connectivity*
