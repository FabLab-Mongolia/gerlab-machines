# Desktop Milling

[← Previous: CNC Mill](cnc-mill.md) · [↑ Machine Library](README.md) · [Next: FDM 3D Printers →](fdm-3d-printers.md)

> **Documentation status:** Draft · **Reviewed:** 2026-07-17 · GerLab verification is still required for photos, approved materials, and tested settings.

This page documents GerLab’s desktop milling machine, including machine information, technical specifications, basic use, materials, safety notes, file preparation, milling workflow, troubleshooting, and maintenance notes.

---

## Machine Information

| Item | Details |
|---|---|
| Machine type | Desktop CNC milling machine |
| Brand | Roland DG |
| Model | monoFab SRM-20 |
| Origin | Japan |
| Quantity | 1 set |
| Category | CNC — Precision |
| Main use | Small-scale precision milling, PCB milling, wax milling, and prototype machining |
| Status | Available |

---

## Photos

> Photo required: full machine, model label, front cover, spindle, collet, worktable, control panel, and tool-storage area.

---

## Technical Specifications

| Specification | Value |
|---|---|
| Machine type | Desktop CNC milling machine |
| Brand | Roland DG |
| Model | monoFab SRM-20 |
| Cuttable materials | Modeling wax, chemical wood, foam, acrylic, poly acetate, ABS, PC board |
| X / Y / Z operation stroke | 203.2 × 152.4 × 60.5 mm |
| Workpiece table size | 232.2 × 156.6 mm |
| Maximum distance from collet tip to table | 130.75 mm |
| Maximum loadable workpiece weight | 2 kg |
| Axis drive system | Stepping motor |
| Operating speed | 6–1,800 mm/min |
| Software resolution | 0.01 mm/step with RML-1, 0.001 mm/step with NC code |
| Mechanical resolution | 0.000998594 mm/step |
| Spindle motor | DC motor Type 380 |
| Spindle rotation speed | Adjustable 3,000–7,000 rpm |
| Cutting tool chuck | Collet method |
| Interface | USB |
| Control command sets | RML-1, NC code |
| Power requirement | Machine: DC 24 V, 2.5 A |
| AC adapter input | AC 100–240 V ±10%, 50/60 Hz |
| Power consumption | Approx. 50 W |
| Operating noise | 65 dB(A) or less when not cutting |
| Standby noise | 45 dB(A) or less |
| External dimensions | 451.0 × 426.6 × 426.2 mm |
| Weight | 19.6 kg |
| Installation environment | 5–40°C, 35–80% RH, no condensation |
| Main software | SRP Player, VPanel, mods / PCB workflow if approved |
| Quantity at GerLab | 1 set |

---

## What this machine is used for

The Roland DG monoFab SRM-20 is a compact desktop CNC milling machine for small, detailed, subtractive manufacturing work.

It removes material using a rotating cutting tool. Unlike 3D printing, which adds material layer by layer, milling cuts material away from a solid block or sheet.

Common uses:

- PCB milling
- Wax mold milling
- Small prototype parts
- Small molds
- Acrylic test parts
- ABS test parts
- Chemical wood models
- Precision educational models
- Small mechanical components
- Surface relief carving
- Fine-detail design experiments
- Material testing before larger CNC work

This machine is useful when a project needs accuracy, smooth material finish, PCB traces, or small machined parts.

---

## Basic Rules

- Use the desktop mill only after instruction or staff permission.
- Use only approved materials.
- Use only approved cutting tools.
- Check that the workpiece is fixed securely.
- Check that the tool is installed correctly.
- Set the origin carefully.
- Keep the front cover closed during cutting.
- Do not touch the spindle while it is moving.
- Do not reach inside the machine during operation.
- Do not cut unknown materials.
- Do not use metal unless GerLab staff specifically approve the setup.
- Stop the job if the tool breaks, material moves, or strange sound appears.
- Clean chips and dust after use.
- Report broken tools, weak cutting, unusual noise, software errors, or machine errors.

---

## Safety Notes

Desktop milling is smaller than large CNC machining, but it still has sharp rotating tools and moving axes.

Main risks:

- Rotating cutting tool
- Sharp end mills
- Moving axes
- Pinch points
- Flying chips
- Broken tool fragments
- Dust from material cutting
- Workpiece coming loose
- Electrical risk if machine or cable is damaged
- Wrong toolpath causing crash

Safe behavior:

- Keep the cover closed during cutting.
- Keep hands away from the spindle and tool.
- Do not touch the tool immediately after cutting.
- Wear safety glasses when setting up, cleaning, or removing chips.
- Secure material properly before cutting.
- Use correct cutting depth.
- Use correct toolpath.
- Use correct tool for the material.
- Stop immediately if the tool sounds bad or the material moves.
- Clean dust and chips carefully.

---

## Personal Protective Equipment

Recommended PPE:

- Safety glasses
- Closed shoes
- Dust mask if material dust requires it
- Gloves only when handling raw material or cleaning, not near moving spindle

Do not wear loose gloves, loose clothing, jewelry, or hanging accessories near the machine.

---

## Approved Materials

Approved material list should be confirmed by GerLab staff.

Common SRM-20 materials may include:

- Modeling wax
- Chemical wood
- Foam
- Acrylic
- Poly acetate
- ABS
- FR-1 PCB board
- Soft plastic sheets or blocks, if approved
- Other machinable model materials approved by GerLab staff

Use only clean, dry, and stable material.

---

## Prohibited or Restricted Materials

Do not use unknown material.

Restricted or prohibited materials may include:

- Steel
- Hardened metal
- Unknown metal
- Glass
- Ceramic
- Stone
- Carbon fiber
- Fiberglass
- Toxic or dusty composite materials
- Wet material
- Dirty or contaminated material
- Brittle material that may shatter
- Material too large for the machine
- Material too heavy for the table
- Material that cannot be fixed securely
- Material that produces unsafe dust or fumes

Aluminum or soft metals should only be used if GerLab staff approve the tool, setup, speed, feed, and workholding.

---

## Cutting Tools

Cutting tools must match the material and operation.

Possible tools:

- Flat end mill
- Ball end mill
- V-bit
- PCB engraving bit
- Drill bit, if approved
- Wax milling tool
- Roughing tool
- Finishing tool

Tool selection depends on:

- Material
- Detail size
- Cutting depth
- Surface finish
- Toolpath type
- Required accuracy
- Available collet size

Do not use damaged or dull tools.

---

## Workholding

The workpiece must not move during cutting.

Possible workholding methods:

- Double-sided tape
- Fixture plate
- Clamps, if compatible
- Sacrificial board
- Wax block fixture
- PCB tape-down method

Before cutting:

- Check that the material is flat.
- Check that the material is fixed firmly.
- Check that the tool will not hit clamps.
- Check that the toolpath fits inside the material.
- Check Z height and origin carefully.

Poor workholding can break the tool or ruin the part.

---

## Software

Common software:

- Roland SRP Player
- Roland VPanel
- mods, if using FabLab PCB workflow
- Fusion 360 CAM, if post-processing is approved
- Other CAM software approved by GerLab staff

Common file formats:

- STL
- DXF
- SVG, for PCB or 2D workflows if converted correctly
- PNG, for PCB traces in mods workflow
- RML
- NC code
- Toolpath files generated by approved CAM software

Recommended workflow:

1. Prepare design or PCB file.
2. Choose material.
3. Choose cutting tool.
4. Generate toolpath.
5. Check toolpath preview.
6. Fix material to table.
7. Install cutting tool.
8. Set X, Y, and Z origin.
9. Start with safe shallow settings.
10. Run the job with cover closed.
11. Watch and listen during the first cut.
12. Stop if anything moves or sounds wrong.
13. Remove finished part.
14. Clean chips and dust.
15. Record useful settings and result.

---

## File Preparation

Before milling:

- Check model size.
- Check units.
- Check material size.
- Check cutting depth.
- Check tool diameter.
- Check tool length.
- Check origin position.
- Check toolpath boundary.
- Check roughing and finishing paths.
- Check if the tool can reach small details.
- Check if the toolpath is too deep or too aggressive.
- Preview the toolpath before cutting.
- Save the file clearly.

For PCB milling:

- Check trace width.
- Check clearance.
- Check board size.
- Check origin.
- Check drill holes.
- Check outline cut.
- Check bit diameter.
- Check copper board flatness.
- Use a sacrificial layer if needed.

---

## Milling Workflow

### 1. Prepare material

Before setup:

- Confirm material is approved.
- Cut material to suitable size.
- Check surface flatness.
- Clean dust or oil.
- Make sure material fits the table and operation stroke.

### 2. Prepare toolpath

In CAM software:

- Select correct tool.
- Set material size.
- Set cutting depth.
- Set step-down.
- Set feed rate.
- Set spindle speed.
- Preview toolpath.
- Check for collisions.

### 3. Fix material

- Place material on the work table.
- Secure it with tape, fixture, or approved method.
- Press firmly if using double-sided tape.
- Confirm it cannot move.

### 4. Install tool

- Install correct cutting tool.
- Tighten collet properly.
- Do not over-tighten.
- Check tool stick-out.
- Make sure tool is not damaged.

### 5. Set origin

Set:

- X origin
- Y origin
- Z origin

Z origin is critical. Wrong Z origin can break the tool or cut too deep.

### 6. Start cutting

- Close the cover.
- Start the job.
- Watch and listen.
- Pause or stop if needed.
- Do not open cover during normal cutting unless machine procedure allows safe pause.

### 7. Remove part

After cutting:

- Wait for spindle to stop.
- Open cover.
- Remove chips carefully.
- Remove part from workholding.
- Inspect the part.
- Clean machine.

---

## PCB Milling Workflow

PCB milling is one of the most common FabLab uses for the SRM-20.

Basic workflow:

1. Design circuit.
2. Export traces and outline.
3. Open files in approved PCB milling workflow.
4. Select trace bit and outline bit.
5. Generate toolpaths.
6. Tape PCB board flat on sacrificial surface.
7. Set XY origin.
8. Set Z origin carefully.
9. Mill traces first.
10. Inspect traces.
11. Change tool if needed.
12. Cut outline.
13. Clean board.
14. Check continuity.
15. Solder components.

Important PCB notes:

- PCB board must be flat.
- Z height must be accurate.
- Tool tip must be sharp.
- Trace isolation depth should be shallow and controlled.
- Too deep cutting can destroy fine traces.
- Too shallow cutting may leave copper connected.
- Always check with multimeter after milling.

---

## Common Starting Notes

Desktop milling settings are not universal.

Good settings depend on:

- Material
- Tool diameter
- Tool length
- Tool sharpness
- Cutting depth
- Step-over
- Feed rate
- Spindle speed
- Workholding strength
- Desired surface finish

Start with shallow cuts and conservative feed rates.

---

## Recommended Beginner Settings

| Item | Suggested starting point |
|---|---|
| First material | Modeling wax or foam |
| First project | Simple relief or small test shape |
| Tool | Small flat end mill approved by staff |
| Cutting depth | Shallow step-down |
| Feed rate | Conservative / slow |
| Workholding | Double-sided tape or approved fixture |
| Toolpath | Simple roughing + finishing |
| First PCB test | Simple trace test pattern |
| First user goal | Learn origin setting and safe workholding |

---

## GerLab Tested Settings Record

Use this table to record real GerLab results.

| Date | Material | Tool | Spindle Speed | Feed Rate | Step-down | Toolpath | Result | Notes | Tested by |
|---|---|---|---:|---:|---:|---|---|---|---|
| YYYY-MM-DD | Modeling wax | TBD | TBD | TBD | TBD | Roughing | TBD | TBD | Name |
| YYYY-MM-DD | Acrylic | TBD | TBD | TBD | TBD | Finishing | TBD | TBD | Name |
| YYYY-MM-DD | FR-1 PCB | V-bit | TBD | TBD | TBD | Trace milling | TBD | TBD | Name |
| YYYY-MM-DD | FR-1 PCB | End mill | TBD | TBD | TBD | Outline cut | TBD | TBD | Name |

---

## Test Result Notes

When recording a test, describe the result clearly.

Useful result words:

- Good cut
- Rough surface
- Smooth finish
- Tool chatter
- Tool broke
- Material moved
- Cut too deep
- Cut too shallow
- Good PCB traces
- PCB traces too thin
- Copper not fully removed
- Board not flat
- Burrs
- Melted plastic
- Dusty cut
- Good result
- Failed result

Example:

| Date | Material | Tool | Result | Notes |
|---|---|---|---|---|
| 2026-07-11 | Modeling wax | 3 mm flat end mill | Good cut | Smooth surface, no vibration |
| 2026-07-11 | FR-1 PCB | V-bit | Cut too shallow | Lower Z origin slightly and retest |

---

## Common Problems and Fixes

| Problem | Possible Cause | Fix |
|---|---|---|
| Tool breaks | Cutting too deep, feed too high, wrong tool, material moved | Reduce depth, reduce feed, check tool and workholding |
| Rough surface | Dull tool, wrong feed, wrong spindle speed, too large step-over | Use sharp tool, adjust feed/speed, reduce step-over |
| Material moves | Weak tape, poor fixture, cutting force too high | Improve workholding, reduce cutting load |
| Cut too deep | Wrong Z origin, wrong toolpath setting | Reset Z origin, check CAM depth |
| Cut too shallow | Wrong Z origin, uneven material, board not flat | Reset Z, flatten material, check board |
| Plastic melts | Spindle/feed mismatch, dull tool, too much heat | Increase chip removal, adjust feed/speed, use correct tool |
| Tool chatter | Tool stick-out too long, feed too aggressive, weak setup | Shorten tool stick-out, reduce feed, improve fixing |
| PCB traces not isolated | Z too high, bit dull, board not flat | Lower Z slightly, use sharp bit, flatten board |
| PCB traces destroyed | Z too low, bit too wide, design too fine | Raise Z, use correct bit, adjust PCB design |
| Machine makes unusual sound | Crash, wrong setup, material movement | Stop job and inspect |
| Software cannot connect | USB/software issue | Check USB, VPanel, driver, machine power |
| Dust buildup | Poor cleaning after jobs | Clean machine carefully after milling |

---

## Maintenance Notes

Possible maintenance items:

- Clean chips after every job.
- Keep work table clean.
- Keep spindle area clean.
- Check tool condition.
- Check collet condition.
- Keep tools organized.
- Check double-sided tape residue.
- Clean dust from machine interior.
- Keep USB cable and power adapter safe.
- Keep cover clean and visible.
- Report unusual sound, vibration, software errors, or mechanical problems.
- Do not disassemble machine without staff permission.

---

## Tool Care Notes

Cutting tools are fragile.

Good tool care:

- Store tools safely.
- Do not drop end mills.
- Do not touch sharp edges unnecessarily.
- Use correct collet.
- Tighten tool properly.
- Do not use bent or chipped tools.
- Replace dull PCB bits.
- Label tool size clearly.

A dull tool can damage material and produce poor surface finish.

---

## Cleaning Notes

After milling:

- Wait for spindle to stop fully.
- Remove large chips carefully.
- Use brush or vacuum method approved by GerLab staff.
- Do not blow dust into electronics.
- Clean table surface.
- Remove tape residue.
- Dispose of chips according to material type.
- Leave machine ready for next user.

Some dusts may be hazardous. Ask staff before cutting materials that create fine dust.

---

## Beginner Workflow

1. Choose approved material.
2. Choose simple design.
3. Generate toolpath.
4. Check toolpath preview.
5. Fix material securely.
6. Install correct tool.
7. Set X/Y origin.
8. Set Z origin carefully.
9. Close machine cover.
10. Start cutting.
11. Watch and listen.
12. Stop if tool breaks or material moves.
13. Remove part after spindle stops.
14. Clean machine.
15. Record useful settings and result.

---

## Good Practice

Before milling:

- Start with wax or foam.
- Use small shallow cuts.
- Preview toolpath.
- Check units.
- Check material size.
- Check origin position.
- Check tool diameter.
- Check workholding.
- Keep tool stick-out short.
- Do not rush Z origin.
- Save successful settings.
- Record failed tests too.

---

## Source

This page is based on GerLab equipment information, GerLab use notes, and official Roland DG monoFab SRM-20 technical information.

Useful references:

- [Roland DG SRM-20 Compact Milling Machine Specifications](https://global.rolanddg.com/products/milling-machines/srm-20-compact-milling-machine/specifications)
- [Roland DG monoFab SRM-20 Support](https://www.rolanddga.com/support/products/milling/monofab-srm-20-compact-milling-machine)

---

**Made with care in Mongolia.**

[← Previous: CNC Mill](cnc-mill.md) · [↑ Machine Library](README.md) · [Next: FDM 3D Printers →](fdm-3d-printers.md)
