# CNC Router

This page documents GerLab’s CNC router, including machine information, technical specifications, basic use, materials, safety notes, file preparation, toolpath workflow, troubleshooting, and maintenance notes.

---

## Machine Information

| Item | Details |
|---|---|
| Machine type | CNC router |
| Brand | ShopBot Tools |
| Model | PRSalpha 96 CNC Router |
| Origin | USA |
| Quantity | 1 set |
| Category | CNC — Wood |
| Main use | Large-format CNC cutting, carving, drilling, and machining |
| Status | Available |

---

## Photos

---

## Technical Specifications

| Specification | Value |
|---|---|
| Machine type | Large-format CNC router |
| Brand | ShopBot Tools |
| Model | PRSalpha 96 CNC Router |
| Common format | 96 × 48 in / 4 × 8 ft class machine |
| Reference cut / movement area | 103 × 49 × 8 in / 2616 × 1245 × 200 mm |
| Reference footprint | 120 × 79 × 67 in / 3050 × 2000 × 1700 mm |
| Motion system | Closed-loop control system |
| Drive system | Rack-and-pinion power transmission |
| Spindle option reference | 2.2 hp HSD spindle |
| Collet type | ER25 |
| Included collet sizes reference | 1/4 in and 1/2 in |
| Maximum cutting speed reference | Up to 720 in/min |
| Maximum rapid speed reference | Up to 1800 in/min |
| Positional resolution reference | 0.0004 in / 0.01 mm |
| Common control software | ShopBot Control Software / SB3 |
| Common CAD/CAM software | VCarve Pro, Aspire, Fusion 360, or other CAM software |
| Common file output | ShopBot part file / toolpath file |
| Dust collection | Dust skirt connected to dust collector |
| Quantity at GerLab | 1 set |

---

## What this machine is used for

The CNC router is a large-format subtractive manufacturing machine.

It cuts material using a rotating cutting tool controlled by computer. It is useful for making large parts that are difficult or slow to make by hand.

Common uses:

- Furniture parts
- Plywood cutting
- MDF cutting
- Wood panels
- Signs
- Large prototypes
- 2D profile cutting
- 2.5D pocket cutting
- Relief carving
- Joinery parts
- Molds
- Jigs and fixtures
- Exhibition structures
- Educational fabrication projects
- Large maker projects
- Mongolian pattern-based panels and decorative parts

The CNC router is one of the most powerful machines in the workshop, but it also requires careful file preparation, workholding, tool selection, and safety control.

---

## Basic Rules

- Use the CNC router only after training or staff permission.
- Use only approved materials.
- Use only approved cutting bits.
- Check material size and thickness before cutting.
- Fix material securely before starting.
- Check that screws, clamps, or hold-downs are outside the cutting path.
- Check spindle speed and feed rate before cutting.
- Check toolpath preview before cutting.
- Turn on dust collection before cutting.
- Keep hands away from the machine during operation.
- Stay near the machine while it is cutting.
- Stop the job if material moves, tool breaks, smoke appears, or strange sound occurs.
- Clean the table and floor after use.
- Report broken bits, damaged spoilboard, loose parts, abnormal sound, or machine errors.

---

## Safety Notes

The CNC router is a high-risk machine because it has a fast rotating tool, large moving gantry, sharp chips, dust, and heavy material.

Main risks:

- Rotating cutting tool
- Moving gantry
- Pinch points
- Flying chips
- Broken tool fragments
- Dust from wood, MDF, or plastic
- Loud noise
- Material coming loose
- Workholding failure
- Toolpath crash
- Fire or smoke from wrong feed/speed
- Electrical risk if machine or cable is damaged
- Heavy sheet lifting risk

Safe behavior:

- Wear safety glasses.
- Wear hearing protection when needed.
- Use dust collection.
- Keep loose clothing, hair, jewelry, and lanyards away from the machine.
- Keep hands away from the spindle and cutting area.
- Do not reach across the machine while it is running.
- Never stand on the machine bed.
- Do not leave the machine unattended during cutting.
- Know where the emergency stop is.
- Stop immediately if cutting sound becomes abnormal.
- Stop immediately if material moves.
- Stop immediately if smoke or burning smell appears.

---

## Personal Protective Equipment

Required or recommended PPE:

- Safety glasses
- Hearing protection
- Closed shoes
- Dust mask or respirator when cutting dusty materials
- Gloves only for handling raw material, not near the rotating spindle

Do not wear gloves near the rotating spindle during machine operation.

Do not wear:

- Loose sleeves
- Loose hoodie strings
- Hanging ID cards
- Scarves
- Loose jewelry
- Untied long hair

---

## Approved Materials

Approved material list should be confirmed by GerLab staff.

Common CNC router materials may include:

- Plywood
- MDF
- Solid wood
- Soft wood
- Hard wood, if approved
- Acrylic, if approved
- HDPE, if approved
- Foam
- Modeling board
- Chemical wood
- Soft plastics, if approved
- Aluminum, only if GerLab staff approve the setup

Use only clean, dry, and flat material.

---

## Prohibited or Restricted Materials

Do not cut unknown material.

Restricted or prohibited materials may include:

- Unknown plastic
- PVC / vinyl
- Glass
- Ceramic
- Stone
- Carbon fiber
- Fiberglass
- Toxic composite materials
- Wet wood
- Dirty or contaminated material
- Loose or cracked material
- Material with hidden nails, screws, staples, or metal pieces
- Material that cannot be fixed securely
- Material that creates unsafe dust or fumes
- Material thicker than safe cutting capacity
- Metal unless staff approve the tool, spindle speed, feed rate, and workholding

PVC / vinyl should not be machined because it can release hazardous fumes and contaminate the workspace.

---

## Cutting Tools

Cutting tools must match the material and operation.

Common CNC router tools:

- Flat end mill
- Upcut end mill
- Downcut end mill
- Compression bit
- Ball nose bit
- V-bit
- Drill bit
- Surfacing bit
- Engraving bit

Tool choice depends on:

- Material
- Thickness
- Cut type
- Desired edge quality
- Surface finish
- Cutting depth
- Detail size
- Toolpath type
- Machine condition

Do not use damaged, dull, bent, or unknown bits.

---

## Tool Types

### Upcut bit

Pulls chips upward.

Useful for:

- Good chip removal
- Pocketing
- Deep cutting

Risk:

- Can tear the top surface of plywood or laminated material.

### Downcut bit

Pushes chips downward.

Useful for:

- Cleaner top surface
- Shallow profile cutting
- Plywood top face quality

Risk:

- Poor chip evacuation in deep cuts.
- Can create heat if chips are trapped.

### Compression bit

Combines upcut and downcut geometry.

Useful for:

- Cleaner top and bottom edges
- Full-depth sheet cutting
- Plywood and laminated boards

Risk:

- Requires correct depth engagement.
- Not ideal for very shallow cuts.

### Ball nose bit

Has rounded tip.

Useful for:

- 3D carving
- Smooth surface finishing
- Relief models

### V-bit

Has angled tip.

Useful for:

- Engraving
- Lettering
- V-carving
- Decorative patterns

---

## Workholding

The material must not move during cutting.

Possible workholding methods:

- Screws into spoilboard
- Clamps
- Vacuum hold-down, if available
- Double-sided tape
- Tabs in toolpath
- Fixtures
- Sacrificial board
- Combination of methods

Before cutting:

- Check that the sheet is flat.
- Check that it cannot move.
- Check that the tool will not hit screws or clamps.
- Check that tabs are strong enough.
- Check that small parts will not fly loose.
- Check that the cutting path stays inside the material.

Poor workholding can break the bit, damage the machine, or throw material.

---

## Software

Common software:

- VCarve Pro
- Aspire
- Fusion 360
- RhinoCAM, if available
- FreeCAD, if workflow is approved
- ShopBot Control Software / SB3

Common design file formats:

- DXF
- SVG
- PDF, if converted correctly
- EPS
- AI
- STL, for 3D carving workflows
- STEP, if using CAD/CAM workflow

Common output:

- ShopBot part file / toolpath file
- CNC toolpath file generated by approved CAM software

Recommended workflow:

1. Design or prepare vector/CAD file.
2. Check scale and units.
3. Choose material size and thickness.
4. Choose cutting tool.
5. Create toolpaths in CAM software.
6. Preview all toolpaths.
7. Check cutting depth.
8. Check tabs and hold-down positions.
9. Export toolpath using correct ShopBot post-processor.
10. Load material on CNC bed.
11. Fix material securely.
12. Install correct cutting bit.
13. Set X, Y, and Z origin.
14. Turn on dust collection.
15. Run air cut or preview if needed.
16. Start cut while monitoring.
17. Remove finished parts safely.
18. Clean machine and record useful settings.

---

## File Preparation

Before CNC routing:

- Check units.
- Check final size.
- Check material thickness.
- Check design fits inside material.
- Remove duplicate lines.
- Remove hidden objects.
- Join open vectors if needed.
- Check closed vectors for profile cuts.
- Check inside and outside cut directions.
- Add dogbones if parts need square internal corners.
- Add tabs for small or loose parts.
- Check tool diameter against small details.
- Check clearance between parts.
- Check screw or clamp positions.
- Preview every toolpath before cutting.

Bad files can cause broken tools, wrong dimensions, wasted material, or unsafe cutting.

---

## Toolpath Types

### Profile cut

Cuts along the outline of a shape.

Used for:

- Cutting parts out of sheet material
- Outside profiles
- Inside holes
- Contour cutting

Important checks:

- Inside or outside cut direction
- Cut depth
- Tabs
- Tool diameter
- Final part size

### Pocket cut

Removes material inside a closed area.

Used for:

- Recesses
- Slots
- Pockets
- Inlays
- Material removal

Important checks:

- Pocket depth
- Step-down
- Step-over
- Tool size
- Chip evacuation

### Drill toolpath

Creates holes.

Used for:

- Screw holes
- Alignment holes
- Assembly holes
- Fixture holes

Important checks:

- Drill diameter
- Hole depth
- Material thickness
- Spoilboard protection

### V-carve

Uses a V-bit for engraved shapes or text.

Used for:

- Signage
- Decorative patterns
- Lettering
- Engraving

### 3D roughing and finishing

Used for relief carving or 3D surface machining.

Important checks:

- Model height
- Tool reach
- Roughing allowance
- Finishing tool
- Machining time

---

## CNC Router Workflow

### 1. Prepare design

Check:

- Size
- Units
- Vectors
- Tool diameter
- Material thickness
- Cut direction
- Detail size
- Assembly tolerance

### 2. Prepare toolpaths

In CAM software:

- Set material size.
- Set material thickness.
- Choose correct origin.
- Choose correct tool.
- Set spindle speed.
- Set feed rate.
- Set pass depth.
- Add tabs.
- Preview toolpath.
- Export with correct post-processor.

### 3. Prepare material

Before loading:

- Confirm material is approved.
- Check material thickness.
- Check material flatness.
- Check for hidden metal.
- Mark material orientation if needed.
- Place material on spoilboard.

### 4. Secure material

Use approved workholding.

Check:

- No movement.
- No clamp collision.
- No screw collision.
- Enough support under the cut.
- Small parts will stay attached.

### 5. Install bit

- Select correct bit.
- Check bit condition.
- Insert bit into collet correctly.
- Tighten collet properly.
- Do not leave bit too far out.
- Do not use wrong collet size.

### 6. Set origin

Set:

- X origin
- Y origin
- Z origin

Z origin is critical. Wrong Z height can cut too deep, fail to cut through, or break the bit.

### 7. Final check

Before pressing start:

- Correct file
- Correct material
- Correct tool
- Correct origin
- Correct feed/speed
- Correct cutting depth
- Dust collection on
- Emergency stop accessible
- Area clear

### 8. Start cut

During cutting:

- Stay nearby.
- Listen to cutting sound.
- Watch dust extraction.
- Watch material movement.
- Pause or stop if anything looks wrong.

### 9. Finish

After cutting:

- Wait for spindle to stop.
- Remove loose parts carefully.
- Remove tabs.
- Sand edges if needed.
- Clean bed and floor.
- Record successful settings.

---

## Common Starting Notes

CNC router settings are not universal.

Good settings depend on:

- Material
- Material thickness
- Bit diameter
- Bit type
- Number of flutes
- Spindle speed
- Feed rate
- Pass depth
- Step-over
- Workholding
- Desired edge quality
- Dust extraction
- Machine condition

Start with conservative settings and test on scrap material.

---

## Recommended Beginner Settings

| Item | Suggested starting point |
|---|---|
| First material | Plywood or MDF |
| First project | Simple 2D profile cut |
| Tool | 6 mm flat end mill or approved shop bit |
| Cut type | Profile cut with tabs |
| Pass depth | Shallow passes |
| Feed rate | Conservative / moderate |
| Workholding | Screws or approved clamps outside toolpath |
| Dust collection | Always on |
| First user goal | Learn file setup, origin, tabs, and safe cutting |

---

## GerLab Tested Settings Record

Use this table to record real GerLab results.

| Date | Material | Thickness | Tool | Spindle Speed | Feed Rate | Pass Depth | Toolpath | Result | Notes | Tested by |
|---|---|---:|---|---:|---:|---:|---|---|---|---|
| YYYY-MM-DD | Plywood | 12 mm | TBD | TBD | TBD | TBD | Profile | TBD | TBD | Name |
| YYYY-MM-DD | MDF | 12 mm | TBD | TBD | TBD | TBD | Profile | TBD | TBD | Name |
| YYYY-MM-DD | Acrylic | 5 mm | TBD | TBD | TBD | TBD | Profile | TBD | TBD | Name |
| YYYY-MM-DD | Wood | TBD | TBD | TBD | TBD | TBD | Pocket | TBD | TBD | Name |
| YYYY-MM-DD | Foam | TBD | TBD | TBD | TBD | TBD | 3D carve | TBD | TBD | Name |

---

## Test Result Notes

When recording a test, describe the result clearly.

Useful result words:

- Good cut
- Clean edge
- Rough edge
- Tear-out
- Burning
- Smoke
- Tool chatter
- Tool broke
- Material moved
- Cut too deep
- Did not cut through
- Tabs too weak
- Tabs too strong
- Good pocket
- Poor pocket
- Dust extraction good
- Dust extraction poor
- Good result
- Failed result

Example:

| Date | Material | Thickness | Tool | Result | Notes |
|---|---|---:|---|---|---|
| 2026-07-11 | Plywood | 12 mm | 6 mm compression bit | Good cut | Clean top and bottom edge |
| 2026-07-11 | MDF | 18 mm | 6 mm flat end mill | Burning | Feed too slow or tool dull |

---

## Common Problems and Fixes

| Problem | Possible Cause | Fix |
|---|---|---|
| Tool breaks | Pass depth too deep, feed too high, wrong tool, material moved | Reduce pass depth, check feed, improve workholding |
| Material moves | Weak hold-down, no tabs, cutting force too high | Add screws/clamps/tabs, reduce cutting load |
| Cut does not go through | Z origin wrong, material thicker than expected, cut depth too shallow | Measure material, reset Z, adjust final depth |
| Cuts too deep into spoilboard | Z origin wrong, cut depth too deep | Reset Z, check material thickness and toolpath |
| Burning or smoke | Feed too slow, spindle too fast, dull bit, poor chip removal | Increase feed, reduce RPM, change bit, improve dust extraction |
| Rough edge | Wrong bit, dull bit, wrong feed/speed | Use correct bit, replace dull bit, tune settings |
| Tear-out on plywood | Wrong bit direction, poor material support | Use downcut or compression bit, improve support |
| Chatter | Tool stick-out too long, feed/speed mismatch, weak workholding | Shorten tool stick-out, tune settings, fix material better |
| Tabs break during cutting | Tabs too small, material moves, cutting order issue | Use larger tabs, improve hold-down |
| Tabs hard to remove | Tabs too thick or too many | Reduce tab size or number |
| Dust everywhere | Dust collector off, clogged hose, dust skirt issue | Turn on dust collector, check hose and skirt |
| Wrong part size | Wrong units, wrong tool diameter, wrong inside/outside path | Check file units, tool database, cut direction |
| Machine makes unusual sound | Tool overloaded, loose part, bad setup | Pause/stop and inspect |
| Router cuts clamps or screws | Poor toolpath planning | Mark hold-down positions and preview toolpath |

---

## Maintenance Notes

Possible maintenance items:

- Clean spoilboard.
- Clean dust and chips.
- Check dust skirt.
- Check dust collector hose.
- Check collets.
- Check cutting bits.
- Remove broken bit pieces.
- Check spoilboard flatness.
- Surface spoilboard when needed.
- Check emergency stop.
- Check cables.
- Check gantry movement.
- Report unusual sound, vibration, loose parts, or errors.
- Do not disassemble machine without staff permission.

---

## Collet Notes

The collet holds the cutting tool.

Good collet practice:

- Use correct collet size.
- Keep collet clean.
- Do not insert tool too shallow.
- Do not insert tool too deep into the flute area.
- Tighten properly.
- Remove dust from collet before use.
- Do not use damaged collets.

Bad collet setup can cause tool slip, vibration, poor cuts, or broken tools.

---

## Dust Collection Notes

Dust collection is required for most CNC router jobs.

Dust control helps:

- Keep the workspace clean
- Improve visibility
- Reduce dust exposure
- Improve chip evacuation
- Reduce fire risk
- Protect machine components

Before cutting:

- Turn on dust collector.
- Check hose connection.
- Check dust skirt position.
- Check that airflow is not blocked.
- Empty dust collection system if needed.

MDF dust and some plastic dust can be harmful. Use dust control and PPE.

---

## Sheet Lifting Notes

Large sheets can be heavy.

Safe handling:

- Use two people for large sheets.
- Lift with proper posture.
- Watch fingers under sheet edges.
- Keep walking path clear.
- Do not drag heavy sheet across people or tools.
- Store sheet materials safely.
- Avoid leaning sheets where they can fall.

---

## Beginner Workflow

1. Wear safety glasses.
2. Prepare a simple vector design.
3. Choose approved material.
4. Measure material thickness.
5. Create toolpath in CAM software.
6. Add tabs.
7. Preview toolpath.
8. Load material on CNC bed.
9. Secure material.
10. Install correct bit.
11. Set X/Y origin.
12. Set Z origin carefully.
13. Turn on dust collection.
14. Start cut and monitor.
15. Stop if anything looks or sounds wrong.
16. Remove finished part after spindle stops.
17. Clean machine and floor.
18. Record useful settings and result.

---

## Good Practice

Before cutting:

- Start with simple projects.
- Use scrap material for first tests.
- Measure real material thickness.
- Use correct tool diameter in CAM.
- Preview all toolpaths.
- Add tabs to profile cuts.
- Mark screw and clamp positions.
- Keep small parts attached.
- Use dust collection.
- Listen to the machine.
- Record successful settings.
- Record failed tests too.

---

## Source

This page is based on GerLab equipment information, GerLab use notes, FabLabs.io machine inventory information, and official ShopBot technical information.

Useful references:

- [ShopBot PRS5 Alpha Product Page](https://shopbottools.com/products/shopbot-prs5-alpha/)
- [FabLabs.io PRSAlpha 96x48 Machine Page](https://www.fablabs.io/machines/prsalpha-96x48)
- [ShopBot Tools Support and Documentation](https://shopbottools.com/support/)

---

**Made with care in Mongolia.**
