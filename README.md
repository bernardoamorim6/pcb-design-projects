# PCB Design Projects

Two PCB design projects completed during my Electronics and Computer
Engineering studies (KU Leuven exchange). Both were taken through
schematic capture, layout, and design-rule checking in Autodesk EAGLE,
with fabrication-ready Gerber files generated as the final output.

**Note:** these were coursework design exercises. Neither board was
physically fabricated or assembled as part of the coursework — the
work here covers design and verification (schematic, layout, DRC,
Gerber export), not hardware build or bring-up.

| Project | Focus | Layers |
|---|---|---|
| [HD-SDI Cable Equalizer](./hd-sdi-cable-equalizer) | RF/high-speed signal design | 4 |
| [PCB Manufacturing Exercise](./pcb-manufacturing-exercise) | Fabrication design-rules & via optimization | 4 |

---

## HD-SDI Cable Equalizer

A 4-layer PCB design for an adaptive cable equalizer circuit, used to
condition HD-SDI (broadcast video) signals. Includes:

- Schematic built around a GS3440 Adaptive Cable Equalizer IC
- Impedance-controlled microstrip trace design: 50Ω traces for SMA
  connectors, 75Ω traces for HD-BNC connectors
- Full 4-layer stackup (top, two inner routing layers, bottom)
- Complete Gerber output set (copper, soldermask, silkscreen,
  solder paste, drill/profile)

## PCB Manufacturing Exercise

A design exercise focused on PCB fabrication constraints rather than
circuit function: working through plated-through-hole size classes
(per Eurocircuits manufacturing classes) and via teardrop optimization
for manufacturability.

---

### Tools

Designed in [Autodesk EAGLE](https://www.autodesk.com/products/eagle/overview)
9.6.2. Files are provided in their native `.sch`/`.brd` format alongside
exported Gerbers.
