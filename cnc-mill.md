# CNC Mill

This page documents GerLab’s CNC mill, including machine information, technical specifications, basic use, materials, safety notes, file preparation, CAM workflow, machining workflow, troubleshooting, and maintenance notes.

---

## Machine Information

| Item | Details |
|---|---|
| Machine type | CNC vertical milling machine |
| Brand | Tormach |
| Model | PCNC 1100MX CNC Mill |
| Origin | USA |
| Quantity | 1 set |
| Category | CNC — Metal |
| Main use | Precision milling, drilling, slotting, facing, pocketing, and machining of engineering parts |
| Status | Available |

---

## Photos


---

## Technical Specifications

| Specification | Value |
|---|---|
| Machine type | CNC vertical milling machine |
| Brand | Tormach |
| Model | PCNC 1100MX |
| X-axis travel | 18 in / 457 mm |
| Y-axis travel | 11 in / 279 mm |
| Z-axis travel | 16.25 in / 413 mm |
| Spindle-to-table maximum clearance | 18 in / 457 mm |
| Spindle centerline to machine column | 11 in / 279 mm |
| Spindle power | 2 hp / 1.5 kW |
| Spindle maximum speed | 10,000 rpm |
| Spindle speed range, low | 70–2,000 rpm |
| Spindle speed range, high | 250–10,000 rpm |
| Transmission | Poly-V belt |
| Spindle taper | BT30 |
| Thread machining | Tension/compression tapping, rigid tapping, thread milling |
| Maximum feed rate, X/Y | 300 IPM / 2.7 m/min |
| Maximum feed rate, Z | 230 IPM / 2.2 m/min |
| Axis motors | Servo driven |
| Motion resolution | 0.0001 in |
| Ball screw positional accuracy | ≤ 0.0006 in/ft |
| Positional accuracy | ≤ 0.0013 in/ft |
| Table size | 34 × 9.5 in / 864 × 241 mm |
| T-slot size | 5/8 in / 15.9 mm |
| Number of T-slots | 3 |
| Maximum table load | 500 lb / approx. 227 kg |
| Primary power | Single-phase 230 V AC, 50/60 Hz |
| Recommended circuit | Dedicated 20 A breaker |
| Machine size | 69 × 56 in / 1.8 × 1.4 m |
| Overall system height | 96 in / 2.4 m |
| Typical system weight | 1600 lb / 726 kg |
| Common control software | PathPilot |
| Common CAM software | Fusion 360, SolidWorks CAM, FreeCAD CAM, or other approved CAM software |
| Common tool holders | BT30 tool holders |
| Quantity at GerLab | 1 set |

---

## What this machine is used for

The CNC mill is a precision subtractive manufacturing machine.

It removes material from a solid workpiece using rotating cutting tools. Compared with the CNC router, the CNC mill is more suitable for rigid materials, accurate parts, metal machining, and small engineering components.

Common uses:

- Aluminum parts
- Steel parts, if approved
- Brass parts
- Plastic engineering parts
- Mechanical components
- Fixtures
- Jigs
- Tooling parts
- Prototype parts
- Small molds
- Drilling accurate holes
- Pocketing
- Facing
- Slotting
- Thread milling
- Tapping
- Engineering education
- Precision machining practice

The CNC mill is one of the most technical machines in GerLab. It requires careful setup, correct tooling, safe workholding, CAM knowledge, and machining judgment.

---

## Basic Rules

- Use the CNC mill only after training or staff permission.
- Use only approved materials.
- Use only approved cutting tools and tool holders.
- Check material size before machining.
- Check that the workpiece is clamped securely.
- Check that the tool is installed correctly.
- Check that the toolpath is correct.
- Check spindle speed and feed rate before cutting.
- Check coolant or lubrication method before cutting.
- Set X, Y, and Z origin carefully.
- Keep the machine door / enclosure closed during machining.
- Keep hands away from the spindle and cutting area.
- Do not reach into the machine while the spindle is rotating.
- Stop the machine if the tool breaks, material moves, coolant fails, or strange sound occurs.
- Clean chips after use.
- Report broken tools, tool crashes, coolant problems, strange vibration, or machine errors.

---

## Safety Notes

The CNC mill is a high-risk machine. It can cut metal and hard materials using a fast rotating tool.

Main risks:

- Rotating spindle
- Sharp cutting tools
- Flying chips
- Broken tool fragments
- Moving axes
- Pinch points
- Sharp machined edges
- Hot chips
- Hot workpiece
- Coolant exposure
- Workpiece coming loose
- Tool crash
- Loud noise
- Heavy vise or workpiece handling
- Electrical risk if machine is damaged

Safe behavior:

- Wear safety glasses.
- Keep the enclosure closed during cutting.
- Keep hands away from the spindle and table during operation.
- Do not wear loose clothing.
- Tie back long hair.
- Remove jewelry, loose lanyards, and hanging accessories.
- Do not wear gloves near the rotating spindle.
- Use a brush or tool to remove chips, not bare hands.
- Do not touch hot chips or freshly machined parts.
- Know where the emergency stop is.
- Stop immediately if the cutting sound becomes abnormal.
- Stop immediately if the workpiece moves.
- Stop immediately if the tool breaks.

---

## Personal Protective Equipment

Required or recommended PPE:

- Safety glasses
- Closed shoes
- Hearing protection when needed
- Apron or lab coat if approved by staff
- Gloves only for handling raw stock, sharp edges, or cleaning after the spindle has stopped

Do not wear gloves near a rotating spindle.

Do not wear:

- Loose sleeves
- Loose hoodie strings
- Scarves
- Hanging ID cards
- Loose jewelry
- Untied long hair

---

## Approved Materials

Approved material list should be confirmed by GerLab staff.

Common CNC mill materials may include:

- Aluminum
- Brass
- Copper, if approved
- Mild steel, if approved
- Stainless steel, if approved
- Engineering plastics
- Delrin / acetal, if approved
- Nylon, if approved
- Acrylic, if approved
- Tooling board, if approved
- Wax
- Soft machinable materials

Use only clean, dry, and stable material.

---

## Prohibited or Restricted Materials

Do not machine unknown material.

Restricted or prohibited materials may include:

- Unknown metal
- Hardened steel unless setup is approved
- Glass
- Ceramic
- Stone
- Carbon fiber
- Fiberglass
- Toxic composite materials
- Magnesium, unless specifically approved by trained staff
- Dirty or contaminated material
- Material with hidden hard inclusions
- Loose or cracked material
- Material that cannot be clamped securely
- Material that creates unsafe dust, fumes, or fire risk
- Oversized material that exceeds safe machine capacity

Some materials require special tooling, coolant, speeds, feeds, and chip control. Ask GerLab staff before machining unfamiliar material.

---

## Cutting Tools

Cutting tools must match the material, operation, and machine setup.

Common CNC mill tools:

- Flat end mill
- Ball end mill
- Chamfer mill
- Drill bit
- Spot drill
- Center drill
- Face mill
- Fly cutter, if approved
- Thread mill
- Tap, if approved
- Engraving tool
- Reamer, if approved

Tool choice depends on:

- Material
- Tool diameter
- Flute count
- Tool coating
- Cutting depth
- Cutting width
- Required tolerance
- Surface finish
- Workholding rigidity
- Spindle speed
- Feed rate
- Coolant or lubrication

Do not use damaged, chipped, dull, bent, or unknown tools.

---

## Tool Types

### Flat end mill

Used for:

- Profile milling
- Pocketing
- Slotting
- Facing small areas
- General material removal

### Ball end mill

Used for:

- 3D surface finishing
- Curved surfaces
- Mold surfaces
- Relief shapes

### Drill bit

Used for:

- Holes
- Pilot holes
- Clearance holes
- Preparation before tapping

### Spot drill

Used for:

- Starting accurate holes
- Preventing drill wandering

### Chamfer mill

Used for:

- Edge chamfering
- Deburring
- Countersink-like features

### Face mill

Used for:

- Flattening large surfaces
- Facing stock
- Producing a clean top surface

### Thread mill

Used for:

- Internal threads
- External threads
- Controlled thread machining

---

## Workholding

The workpiece must not move during machining.

Possible workholding methods:

- Milling vise
- Step clamps
- Toe clamps
- T-slot clamps
- Fixture plate
- Soft jaws
- Parallels
- Double-sided tape for light plastic/wax work, if approved
- Custom fixture
- Sacrificial plate

Before machining:

- Check that the workpiece is clamped securely.
- Check that the vise is tight.
- Check that clamps are outside the toolpath.
- Check that the tool will not hit clamps, vise jaws, screws, or fixture parts.
- Check that the workpiece has enough support.
- Check that the part will not become loose after cut-through.
- Check that the setup is rigid enough for the cut.

Poor workholding can cause tool breakage, part damage, machine damage, or injury.

---

## Software

Common software:

- PathPilot
- Fusion 360
- SolidWorks CAM
- FreeCAD CAM
- Autodesk Inventor CAM
- Other CAM software approved by GerLab staff

Common file formats:

- STEP
- STL
- DXF
- SVG, if converted correctly
- IGES
- Fusion 360 project files
- G-code generated by approved post-processor

Recommended workflow:

1. Design or prepare CAD model.
2. Check scale and units.
3. Choose material.
4. Choose workholding method.
5. Choose cutting tools.
6. Create CAM setup.
7. Set work coordinate system.
8. Create toolpaths.
9. Simulate toolpaths.
10. Check collisions.
11. Check tool length and tool holder clearance.
12. Post-process G-code for Tormach / PathPilot.
13. Load material and clamp securely.
14. Install correct tool.
15. Set work offsets.
16. Set tool length offsets.
17. Run safe test / air cut if needed.
18. Start machining while monitoring.
19. Inspect part.
20. Record useful settings and result.

---

## File Preparation

Before CNC milling:

- Check units.
- Check model size.
- Check material size.
- Check stock dimensions.
- Check work coordinate system.
- Check zero position.
- Check tool diameter.
- Check tool length.
- Check tool holder clearance.
- Check cutting depth.
- Check step-down.
- Check step-over.
- Check feed rate.
- Check spindle speed.
- Check coolant setting.
- Check operation order.
- Check roughing and finishing strategy.
- Check if the tool can reach small features.
- Check if internal corners need smaller tools.
- Simulate every toolpath before machining.

Bad CAM setup can break tools, damage material, or crash the machine.

---

## Toolpath Types

### Facing

Removes material from the top surface to make it flat.

Used for:

- Preparing stock
- Creating flat reference surfaces
- Cleaning rough material

### Adaptive clearing / roughing

Removes large amounts of material.

Used for:

- Roughing pockets
- Removing stock before finishing
- Efficient material removal

### Pocketing

Removes material inside a defined area.

Used for:

- Recesses
- Pockets
- Slots
- Internal features

### Contour milling

Cuts around a shape or edge.

Used for:

- Outside profiles
- Inside walls
- Finishing edges
- Cutting part outlines, if setup allows

### Drilling

Creates holes.

Used for:

- Mounting holes
- Alignment holes
- Pilot holes
- Tapping preparation

### Tapping

Creates internal threads.

Only use tapping if:

- Tool is correct
- Workholding is rigid
- Material is suitable
- Machine setup is approved
- Staff approve the operation

### Thread milling

Creates threads using a thread mill.

Useful for:

- Controlled thread machining
- Larger threads
- Safer threading in some setups

### 3D finishing

Uses ball end mills or finishing tools for curved surfaces.

Used for:

- Molds
- Sculpted surfaces
- Smooth 3D shapes

---

## CNC Mill Workflow

### 1. Prepare design

Check:

- Part size
- Units
- Required tolerances
- Material
- Tool access
- Corner radii
- Hole sizes
- Thread requirements
- Surface finish requirements

### 2. Prepare CAM

In CAM software:

- Define stock.
- Define work coordinate system.
- Select tools.
- Set spindle speed.
- Set feed rate.
- Set cutting depth.
- Set step-over.
- Set coolant.
- Simulate toolpaths.
- Check for collisions.
- Export correct G-code.

### 3. Prepare material

Before loading:

- Confirm material is approved.
- Cut stock to suitable size.
- Deburr sharp edges.
- Clean oil, dirt, or chips.
- Check that material fits the vise or fixture.

### 4. Secure material

Use approved workholding.

Check:

- Workpiece is tight.
- Vise is tight.
- Clamps are tight.
- Parallels are seated correctly.
- Toolpath will not hit clamps or vise.
- Workpiece will not move during roughing.

### 5. Install tool

- Select correct tool.
- Check tool condition.
- Install tool in correct holder.
- Tighten properly.
- Check tool stick-out.
- Do not use damaged tools.

### 6. Set origin and offsets

Set:

- X origin
- Y origin
- Z origin
- Work coordinate system
- Tool length offset

Wrong origin or tool length can cause a crash.

### 7. Final check

Before pressing start:

- Correct file
- Correct tool
- Correct material
- Correct workholding
- Correct origin
- Correct tool offset
- Correct spindle speed
- Correct feed rate
- Correct coolant setting
- Door/enclosure closed
- Emergency stop accessible
- Area clear

### 8. Start machining

During machining:

- Stay nearby.
- Listen to cutting sound.
- Watch chip formation.
- Watch coolant.
- Watch vibration.
- Stop if anything looks or sounds wrong.

### 9. Finish

After machining:

- Wait for spindle to stop.
- Remove chips with brush or vacuum method approved by staff.
- Remove part carefully.
- Deburr sharp edges.
- Measure part.
- Clean machine.
- Record successful settings.

---

## Common Starting Notes

CNC mill settings are not universal.

Good settings depend on:

- Material
- Tool diameter
- Tool type
- Flute count
- Tool coating
- Tool stick-out
- Spindle speed
- Feed rate
- Depth of cut
- Width of cut
- Coolant or lubrication
- Workholding rigidity
- Desired tolerance
- Desired surface finish

Start with conservative settings and test on scrap material.

---

## Recommended Beginner Settings

| Item | Suggested starting point |
|---|---|
| First material | Wax, plastic, or aluminum if approved |
| First project | Simple facing, pocket, or drilled hole pattern |
| First tool | Small flat end mill approved by staff |
| Workholding | Milling vise with parallels |
| CAM strategy | Simple 2D pocket or contour |
| Cutting depth | Shallow passes |
| Feed rate | Conservative / slow |
| Coolant | Use staff-approved method |
| First user goal | Learn workholding, origin, tool length, and safe CAM workflow |

---

## GerLab Tested Settings Record

Use this table to record real GerLab results.

| Date | Material | Tool | Spindle Speed | Feed Rate | Depth of Cut | Width of Cut | Coolant | Result | Notes | Tested by |
|---|---|---|---:|---:|---:|---:|---|---|---|---|
| YYYY-MM-DD | Aluminum | TBD | TBD | TBD | TBD | TBD | TBD | TBD | TBD | Name |
| YYYY-MM-DD | Mild steel | TBD | TBD | TBD | TBD | TBD | TBD | TBD | TBD | Name |
| YYYY-MM-DD | Brass | TBD | TBD | TBD | TBD | TBD | TBD | TBD | TBD | Name |
| YYYY-MM-DD | Delrin / acetal | TBD | TBD | TBD | TBD | TBD | TBD | TBD | TBD | Name |
| YYYY-MM-DD | Wax | TBD | TBD | TBD | TBD | TBD | TBD | TBD | TBD | Name |

---

## Test Result Notes

When recording a test, describe the result clearly.

Useful result words:

- Good cut
- Good chip formation
- Poor chip evacuation
- Chatter
- Vibration
- Tool broke
- Tool wore quickly
- Workpiece moved
- Good surface finish
- Rough surface
- Burrs
- Overheating
- Coolant problem
- Cut too deep
- Cut too shallow
- Wrong dimension
- Good tolerance
- Failed result

Example:

| Date | Material | Tool | Result | Notes |
|---|---|---|---|---|
| 2026-07-11 | Aluminum | 6 mm 3-flute end mill | Good cut | Good chips, clean surface |
| 2026-07-11 | Mild steel | 6 mm end mill | Chatter | Reduce stick-out, reduce depth, check workholding |

---

## Common Problems and Fixes

| Problem | Possible Cause | Fix |
|---|---|---|
| Tool breaks | Feed too high, depth too deep, wrong tool, bad workholding | Reduce load, use correct tool, improve clamping |
| Chatter | Tool stick-out too long, weak setup, wrong speed/feed | Shorten tool, improve rigidity, adjust speed/feed |
| Poor surface finish | Dull tool, wrong feed/speed, vibration | Use sharp tool, tune settings, improve workholding |
| Workpiece moves | Weak clamping, high cutting force | Stop, re-clamp, reduce cutting load |
| Tool rubs instead of cuts | Feed too low, RPM too high, dull tool | Adjust feed/speed, replace tool |
| Overheating | Poor coolant, feed/speed issue, dull tool | Improve coolant, adjust settings, use sharp tool |
| Burrs | Material behavior, dull tool, wrong finishing pass | Use sharp tool, add finishing pass, deburr |
| Wrong dimension | Tool diameter wrong, offset wrong, CAM error | Check tool library, offsets, simulation |
| Machine crash | Wrong origin, wrong tool length, bad CAM | Stop, inspect, reset setup, review CAM |
| Drill walks | No spot drill, wrong speed/feed | Spot drill first, adjust settings |
| Tap breaks | Wrong hole size, wrong speed, poor lubrication | Check drill size, use approved tapping method |
| Coolant problem | Empty coolant, clogged nozzle, wrong aim | Check coolant level and nozzle |
| Chips build up | Poor chip evacuation, no coolant/air, deep slot | Clear chips safely, adjust strategy |
| Loud cutting sound | Tool overloaded, wrong settings, bad setup | Pause or stop and inspect |

---

## Maintenance Notes

Possible maintenance items:

- Clean chips after every job.
- Clean table and T-slots.
- Clean vise and fixtures.
- Check tool holders.
- Check collets.
- Check cutting tools.
- Check coolant level.
- Check coolant concentration if applicable.
- Check way covers.
- Check lubrication system if required.
- Check enclosure.
- Check emergency stop.
- Report unusual sound, vibration, coolant leak, or machine error.
- Do not disassemble machine without staff permission.

---

## Tool Holder Notes

The 1100MX uses BT30 tool holders.

Good tool holder practice:

- Keep tool holders clean.
- Keep taper surfaces clean.
- Do not drop tool holders.
- Check pull studs if used.
- Check tool tightness.
- Keep tool stick-out as short as practical.
- Use correct holder for the tool.
- Store holders safely.
- Do not use damaged holders.

Dirty or damaged tool holders can reduce accuracy and cause poor cutting.

---

## Coolant Notes

Coolant or lubrication helps:

- Reduce heat
- Improve surface finish
- Extend tool life
- Improve chip evacuation
- Reduce built-up edge in some materials

Coolant use depends on:

- Material
- Tool
- Operation
- GerLab procedure
- Machine setup

General rules:

- Use only approved coolant or lubricant.
- Check coolant level before machining.
- Aim coolant correctly.
- Do not splash coolant outside the machine.
- Clean spills.
- Report bad smell, contamination, low level, or leak.

---

## Chip Handling Notes

Metal chips can be sharp and hot.

Safe chip handling:

- Do not remove chips with bare hands.
- Use brush, hook, or approved vacuum method.
- Wait for spindle to stop.
- Watch sharp chip edges.
- Wear gloves only when machine is stopped and safe.
- Dispose of chips according to material type.
- Keep aluminum, steel, brass, and other chips separated if GerLab requires it.

---

## Measuring Notes

After machining, check the part.

Possible measuring tools:

- Caliper
- Micrometer
- Dial indicator
- Edge finder
- Height gauge, if available
- Thread gauge
- Pin gauge, if available

Check:

- Overall dimensions
- Hole diameter
- Hole position
- Pocket depth
- Surface finish
- Burrs
- Thread quality
- Fit with other parts

---

## Beginner Workflow

1. Wear safety glasses.
2. Choose approved material.
3. Prepare simple CAD model.
4. Create simple CAM toolpath.
5. Simulate toolpath.
6. Prepare material stock.
7. Clamp material securely.
8. Install correct tool.
9. Set work origin.
10. Set tool length offset.
11. Check file and offsets.
12. Close enclosure.
13. Start machining carefully.
14. Monitor sound, chips, coolant, and vibration.
15. Stop if anything looks wrong.
16. Remove part after spindle stops.
17. Deburr and measure part.
18. Clean machine.
19. Record useful settings and result.

---

## Good Practice

Before machining:

- Start with simple operations.
- Use safe material first.
- Use conservative cutting settings.
- Keep tool stick-out short.
- Use rigid workholding.
- Simulate toolpaths.
- Check tool length and holder clearance.
- Check work coordinate system.
- Check tool number and tool offset.
- Use coolant correctly.
- Listen to the cut.
- Measure the result.
- Record successful and failed settings.

---

## Source

This page is based on GerLab equipment information, GerLab use notes, and official Tormach 1100MX technical information.

Useful references:

- [Tormach 1100MX Machine Specifications](https://knowledgebase.tormach.com/1100mx/machine-specifications)
- [Tormach 1100MX System Basics](https://knowledgebase.tormach.com/1100mx/system-basics)
- [Tormach Support and Documentation](https://tormach.com/support)

---

**Made with care in Mongolia.**
