# HD-SDI Cable Equalizer — PCB Design

A 4-layer PCB designed in Autodesk EAGLE for an adaptive cable
equalizer circuit, intended to condition HD-SDI (broadcast video)
signals carried over coaxial cable.

**Scope:** this is a design exercise — schematic capture, layout,
impedance calculation, design-rule checking, and Gerber export. The
board was not physically fabricated or assembled.

## Design details

- **Core component:** GS3440 Adaptive Cable Equalizer IC
- **RF interfaces:**
  - SMA end-launch connectors, 50Ω impedance-matched traces
  - HD-BNC connector, 75Ω impedance-matched trace (standard for
    broadcast video/SDI)
- **Stackup:** 4 copper layers (Top, two inner routing layers, Bottom),
  ~1.63mm total board thickness
- **Trace impedance:** calculated using surface microstrip formulas
  (FR4 dielectric, Er = 4.2) to match connector impedance specs

## Files

| Folder | Contents |
|---|---|
| `schematic/` | EAGLE schematic (`.sch`) |
| `board/` | EAGLE board/layout file (`.brd`) |
| `gerbers/` | Fabrication-ready Gerber files (copper, soldermask, silkscreen, solder paste, drill/profile) |
| `BOM.txt` | Bill of materials exported from EAGLE |

## Tools

Autodesk EAGLE 9.6.2.
