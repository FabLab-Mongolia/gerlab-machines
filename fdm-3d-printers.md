# FDM 3D Printers

[← Previous: Desktop Milling](desktop-milling.md) · [↑ Machine Library](README.md) · [Next: Resin 3D Printers →](resin-3d-printer.md)

> **Documentation status:** Draft · **Reviewed:** 2026-07-17 · GerLab verification is still required for photos, approved materials, and tested settings.

This page documents GerLab’s FDM 3D printers, including machine information, technical specifications, basic use, materials, file preparation, tested settings, troubleshooting, and maintenance notes.

---

## Machine Information

| Item | Details |
|---|---|
| Machine type | FDM / FFF 3D printer |
| Brand | Prusa Research |
| Model | Prusa i3 MK4 FDM Printer |
| Origin | Czech Republic |
| Quantity | 8 sets |
| Category | 3D Printing — FDM |
| Main use | Layer-by-layer plastic object creation |
| Status | Available |

---

## Photos

> Photo required: printer group, individual model label, control panel, Nextruder, build plate, filament path, and printer-number labels.

---

## Technical Specifications

| Specification | Value |
|---|---|
| Machine type | FDM / FFF 3D printer |
| Brand | Prusa Research |
| Model | Prusa i3 MK4 |
| Build volume | 250 × 210 × 220 mm |
| Filament diameter | 1.75 mm |
| Standard nozzle | 0.4 mm |
| Layer height range | 0.05–0.30 mm |
| Extruder type | Direct drive |
| Maximum nozzle temperature | Up to 290°C |
| Maximum heatbed temperature | Up to 120°C |
| Main software | PrusaSlicer |
| Common input files | STL, 3MF, OBJ |
| Printer output file | G-code |
| Quantity at GerLab | 8 sets |

---

## What this machine is used for

FDM 3D printers create plastic objects by melting filament and depositing it layer by layer.

Common uses:

- Prototypes
- Educational models
- Mechanical parts
- Enclosures
- Jigs and fixtures
- Replacement parts
- Design tests
- Student projects
- Small product samples
- Fast iteration before final fabrication
- Mongolian culture-inspired models and patterns

FDM printing is usually one of the best first machines for beginners because it is accessible, visual, and useful for learning design through physical testing.

---

## Basic Rules

- Use the printer only after instruction or staff permission.
- Check the bed before printing.
- Use the correct filament type.
- Use the correct nozzle and bed temperature.
- Do not touch the nozzle while hot.
- Do not touch the heated bed while hot.
- Do not forcefully remove prints from the bed.
- Do not leave failed prints running.
- Stop the print if the first layer fails badly.
- Clean the printer area after use.
- Report nozzle clogging, strange sound, bed adhesion problems, or printer errors.

---

## Safety Notes

FDM printers are generally safe, but they still include hot, moving, and electrical parts.

Main risks:

- Hot nozzle
- Hot bed
- Moving axes
- Pinch points
- Sharp scraper tools
- Filament fumes depending on material
- Failed print causing spaghetti or machine obstruction
- Electrical risk if machine is damaged or modified incorrectly

Safe behavior:

- Keep fingers away from moving parts.
- Do not touch the hotend or heated bed during operation.
- Wait for the bed to cool before removing prints.
- Use tools carefully when removing prints.
- Keep filament spools mounted correctly.
- Stop the print if the first layer fails badly.
- Ask GerLab staff before using unfamiliar filament.

---

## Personal Protective Equipment

- Closed shoes are required in the workshop.
- Wear safety glasses when cutting or removing brittle supports if fragments may fly.
- Wear heat-resistant gloves only for an approved maintenance task after the printer is isolated.
- Use respiratory protection only where GerLab's material assessment requires it.

Do not touch the nozzle, heater block, or build plate to test whether it is hot.

---

## Approved Materials

Approved material list should be confirmed by GerLab staff.

Common FDM materials may include:

- PLA
- PETG
- TPU
- ABS
- ASA
- Support materials, if approved

---

## Prohibited or Restricted Materials

Do not use unknown filament.

Restricted materials may include:

- Very high-temperature engineering plastics
- Abrasive filaments without hardened nozzle
- Unknown recycled filament
- Wet or brittle filament
- Filaments with strong fumes unless ventilation is approved
- Carbon fiber or glass fiber filled filament unless nozzle and printer setup are approved

---

## Software

Common software:

- PrusaSlicer
- Fusion 360
- SolidWorks
- Blender
- FreeCAD
- Tinkercad
- Onshape

Common file formats:

- STL
- 3MF
- OBJ
- G-code

Recommended workflow:

1. Design or download model.
2. Check model scale and units.
3. Export as STL or 3MF.
4. Open in PrusaSlicer.
5. Choose correct printer profile.
6. Choose correct filament profile.
7. Choose print quality / layer height.
8. Slice model.
9. Check preview.
10. Export G-code.
11. Start print.
12. Watch first layer.
13. Record useful settings if needed.

---

## File Preparation

Before printing:

- Check model size.
- Check model orientation.
- Check if the model is printable.
- Use supports only when needed.
- Add brim if bed adhesion is weak.
- Check infill percentage.
- Check wall / perimeter count.
- Check layer height.
- Preview toolpath before printing.
- Make sure print time and filament use are acceptable.
- Rename the file clearly before printing.

---

## Common Starting Settings

These are general starting points. Final settings depend on filament brand, nozzle size, printer condition, model shape, and required strength.

| Material | Nozzle Temp | Bed Temp | Notes |
|---|---:|---:|---|
| PLA | 200–220°C | 50–60°C | Easy beginner material |
| PETG | 230–250°C | 70–90°C | Stronger and more heat-resistant than PLA |
| TPU | 210–240°C | 40–60°C | Flexible material, print slowly |
| ABS | 240–260°C | 90–110°C | Needs enclosure / ventilation control |
| ASA | 240–260°C | 90–110°C | UV-resistant, needs controlled environment |

---

## Recommended Beginner Settings

| Setting | Suggested value |
|---|---|
| Nozzle | 0.4 mm |
| Layer height | 0.20 mm |
| Infill | 10–20% |
| Perimeters / walls | 2–3 |
| Top layers | 4–5 |
| Bottom layers | 4–5 |
| Supports | Only when needed |
| Brim | Use when adhesion is weak |
| Material for first users | PLA |

---

## GerLab Tested Settings Record

Use this table to record real GerLab results.

| Date | Printer | Material | Nozzle | Layer Height | Nozzle Temp | Bed Temp | Speed | Result | Notes | Tested by |
|---|---|---|---:|---:|---:|---:|---:|---|---|---|
| YYYY-MM-DD | Prusa MK4 | PLA | 0.4 mm | 0.2 mm | TBD | TBD | TBD | TBD | TBD | Name |
| YYYY-MM-DD | Prusa MK4 | PETG | 0.4 mm | 0.2 mm | TBD | TBD | TBD | TBD | TBD | Name |
| YYYY-MM-DD | Prusa MK4 | TPU | 0.4 mm | 0.2 mm | TBD | TBD | TBD | TBD | TBD | Name |
| YYYY-MM-DD | Prusa MK4 | ABS | 0.4 mm | 0.2 mm | TBD | TBD | TBD | TBD | TBD | Name |

---

## Test Result Notes

When recording a test, describe the result clearly.

Useful result words:

- Good first layer
- Poor first layer
- Warping
- Stringing
- Under-extrusion
- Over-extrusion
- Layer shift
- Rough surface
- Weak layer bonding
- Good surface finish
- Supports hard to remove
- Supports removed cleanly
- Print successful
- Print failed

Example:

| Date | Material | Layer Height | Nozzle Temp | Bed Temp | Result | Notes |
|---|---|---:|---:|---:|---|---|
| 2026-07-11 | PLA | 0.2 mm | 215°C | 60°C | Good print | Clean first layer, no warping |
| 2026-07-11 | PETG | 0.2 mm | 245°C | 85°C | Stringing | Try lower nozzle temp or dry filament |

---

## Common Problems and Fixes

| Problem | Possible Cause | Fix |
|---|---|---|
| First layer not sticking | Dirty bed, wrong Z offset, low bed temp | Clean bed, check first layer, adjust settings |
| Warping | Poor adhesion, material shrinkage, low bed temp | Use brim, increase bed temp, avoid drafts |
| Stringing | Nozzle too hot, retraction issue, wet filament | Lower temp, dry filament, adjust retraction |
| Under-extrusion | Clogged nozzle, filament issue, wrong temp | Check nozzle, increase temp, check filament path |
| Over-extrusion | Flow too high, wrong filament diameter, slicer issue | Check slicer profile and flow |
| Layer shift | Belt issue, collision, high speed | Stop print, inspect axes, reduce speed |
| Spaghetti print | Part detached from bed | Stop print, clean bed, restart with better adhesion |
| Rough surface | Temperature, speed, cooling, filament issue | Tune temp, slow down, check cooling |
| Weak part | Low infill, poor layer bonding, bad orientation | Increase walls, infill, temperature, or change orientation |
| Supports hard to remove | Support distance too small, wrong settings | Adjust support interface and Z distance |
| Nozzle clog | Dusty filament, burnt material, low temp | Clean nozzle, unload/reload filament, use dry filament |

---

## Maintenance Notes

Possible maintenance items:

- Clean print bed.
- Remove filament debris.
- Check nozzle condition.
- Check belts and rods.
- Check filament path.
- Keep filament dry.
- Check spool movement.
- Update slicer profiles carefully.
- Report repeated failures.
- Do not disassemble printer without staff permission.

---

## Beginner Workflow

1. Choose material.
2. Load filament.
3. Clean bed.
4. Prepare file in PrusaSlicer.
5. Choose correct printer and filament profile.
6. Slice and preview.
7. Start print.
8. Watch the first layer.
9. Let print finish.
10. Wait before removing part.
11. Remove part carefully.
12. Clean bed and workspace.
13. Record useful settings.

---

## Good Practice

Before printing:

- Start with PLA if you are a beginner.
- Use 0.2 mm layer height for general prints.
- Avoid unnecessary supports.
- Keep the flat side on the bed when possible.
- Use brim for tall, thin, or warp-prone parts.
- Do not print huge objects before testing small versions.
- Label important files clearly.
- Save successful slicer settings when useful.

---

## Source

This page is based on GerLab equipment information, GerLab use notes, and official Prusa technical information.

Useful references:

- [Original Prusa MK4 Documentation](https://help.prusa3d.com/tag/mk4)
- [PrusaSlicer Documentation](https://help.prusa3d.com/category/prusaslicer_204)

---

**Made with care in Mongolia.**

[← Previous: Desktop Milling](desktop-milling.md) · [↑ Machine Library](README.md) · [Next: Resin 3D Printers →](resin-3d-printer.md)
