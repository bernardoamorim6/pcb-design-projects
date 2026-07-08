# PCB Manufacturing Design-Rule Exercise

A PCB design exercise focused on manufacturing constraints and
fabrication classes, rather than circuit function — working through
how design choices map to real fabrication tolerances.

**Scope:** this is a design exercise — schematic, layout, and Gerber
export. The board was not physically fabricated or assembled.

## What this covers

- Plated-through-hole (PTH) sizing against Eurocircuits fabrication
  classes (e.g. minimum PTH diameter for Class 6C)
- Via teardrop optimization for manufacturability (`via_teardrops1.ulp`,
  applied via `lab2h_AddTearDrops.scr`)
- 4-layer board design and layout in EAGLE

## Files

| Folder | Contents |
|---|---|
| `schematic/` | EAGLE schematic (`.sch`) |
| `board/` | EAGLE board/layout file (`.brd`), teardrop script and ULP |
| `gerbers/` | Fabrication-ready Gerber files |

## Tools

Autodesk EAGLE 9.6.2.
