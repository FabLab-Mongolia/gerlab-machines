# Resin 3D Printers

[← Previous: FDM 3D Printers](fdm-3d-printers.md) · [↑ Machine Library](README.md) · [Next: Vinyl Cutter →](vinyl-cutter.md)

> **Documentation status:** Draft · **Reviewed:** 2026-07-17 · GerLab verification is still required for photos, approved materials, and tested settings.

This page documents GerLab’s resin 3D printers, including machine information, technical specifications, basic use, materials, file preparation, safety notes, post-processing, troubleshooting, and maintenance notes.

---

## Machine Information

| Item | Details |
|---|---|
| Machine type | SLA resin 3D printer |
| Brand | Formlabs |
| Model | Form 3+ SLA Printer |
| Origin | USA |
| Quantity | 2 sets |
| Category | 3D Printing — Resin |
| Main use | High-detail resin 3D printing |
| Status | Available |

---

## Photos

> Photo required: printer group, individual model label, resin cartridge, resin tank, build platform, control panel, wash station, cure station, and resin-work PPE area.

---

## Technical Specifications

| Specification | Value |
|---|---|
| Machine type | SLA resin 3D printer |
| Brand | Formlabs |
| Model | Form 3+ |
| Technology | Low Force Stereolithography / SLA resin printing |
| Light source | 405 nm laser |
| Build volume | 145 × 145 × 185 mm |
| Layer thickness | 25–300 microns, depending on material |
| Resin system | Formlabs resin cartridge system |
| Resin tank | Replaceable resin tank |
| Build platform | Removable build platform |
| Main software | PreForm |
| Print monitoring | Formlabs Dashboard |
| Common input files | STL, OBJ, 3MF |
| Print preparation output | FORM file / PreForm print job |
| Post-processing | Washing and UV curing required |
| Quantity at GerLab | 2 sets |

---

## What this machine is used for

Resin 3D printers create highly detailed parts by curing liquid photopolymer resin with light.

Compared with FDM printing, resin printing gives smoother surfaces, sharper details, and better small features. It is useful when visual quality, fine detail, or small part accuracy is more important than fast, low-cost printing.

Common uses:

- Detailed prototypes
- Miniatures
- Smooth visual models
- Fine mechanical parts
- Small product samples
- Mold masters
- Jewelry-style models
- Educational models
- Medical or dental-style demonstration models, if approved
- High-detail art and design pieces
- Parts that need smooth surface finish

Resin printing is powerful, but it requires more careful handling because liquid resin, solvent, and UV curing are involved.

---

## Basic Rules

- Use the resin printer only after instruction or staff permission.
- Always wear nitrile gloves when handling resin, resin tanks, uncured prints, or contaminated tools.
- Wear eye protection when handling resin or solvent.
- Do not touch liquid resin with bare skin.
- Do not eat or drink near resin printing or washing areas.
- Do not mix different resins unless staff approve it.
- Do not use unknown resin.
- Do not pour resin or contaminated solvent into the sink.
- Keep resin away from direct sunlight.
- Clean spills immediately using approved method.
- Wash and cure printed parts properly.
- Report resin spills, damaged tanks, leaking cartridges, failed prints, or strange printer errors.

---

## Safety Notes

Resin printing has more chemical safety risk than FDM printing.

Main risks:

- Skin irritation from uncured resin
- Eye irritation from resin or solvent splash
- Solvent fumes
- Flammable solvent such as IPA
- UV light exposure during curing
- Sharp support marks or scraper tools
- Resin spills
- Contaminated gloves, tissues, tools, and surfaces
- Improper waste disposal

Safe behavior:

- Wear nitrile gloves.
- Wear safety glasses.
- Work in a clean and ventilated area.
- Keep resin bottles and cartridges closed when not in use.
- Keep solvent containers closed when not in use.
- Avoid breathing strong solvent fumes.
- Keep IPA and other solvents away from flame, sparks, and heat.
- Cure resin-contaminated waste before disposal if required by GerLab procedure.
- Follow GerLab staff instructions for resin and solvent waste.

---

## Personal Protective Equipment

Required PPE when handling resin or post-processing:

- Nitrile gloves
- Safety glasses
- Lab coat or apron, if available

Recommended:

- Closed shoes
- Long sleeves
- Respiratory protection only if required by resin SDS, solvent SDS, or GerLab staff

Do not use latex gloves for resin handling unless approved. Nitrile gloves are preferred.

---

## Approved Materials

Approved material list should be confirmed by GerLab staff.

Common Formlabs resin categories may include:

- Standard resins
- Tough and Durable resins
- Flexible and Elastic resins
- High Temperature resin
- Rigid resin
- Draft resin
- Clear resin
- Grey resin
- Black resin
- White resin
- Castable resin
- BioMed or Dental resins, only if GerLab staff approve the workflow

Use only resin that matches the printer, resin tank, and PreForm material profile.

---

## Prohibited or Restricted Materials

Do not use unknown or unapproved resin.

Restricted materials may include:

- Unknown third-party resin
- Expired resin
- Contaminated resin
- Mixed resin
- Resin with unknown SDS
- Resin not compatible with Formlabs Form 3+
- Resin that requires special ventilation or special curing conditions
- Dental, medical, or biocompatible resin unless the correct workflow is approved
- Resin tank with damaged film
- Resin tank with cured debris inside

---

## Software

Common software:

- PreForm
- Formlabs Dashboard
- CAD software such as Fusion 360, SolidWorks, Blender, FreeCAD, Tinkercad, or Onshape

Common file formats:

- STL
- OBJ
- 3MF
- FORM

Recommended workflow:

1. Design or download model.
2. Check model scale and units.
3. Export as STL, OBJ, or 3MF.
4. Open the file in PreForm.
5. Choose the correct printer.
6. Choose the correct resin material.
7. Choose layer thickness.
8. Orient the part.
9. Generate supports.
10. Check support contact points.
11. Check printability warnings.
12. Send print job to printer.
13. Print the part.
14. Wash the part.
15. Dry the part.
16. Remove supports.
17. Cure the part.
18. Record useful settings and results.

---

## File Preparation

Before printing:

- Check model size.
- Check model orientation.
- Check if the model is printable.
- Avoid large flat surfaces directly parallel to the build platform.
- Hollow large solid parts when appropriate.
- Add drain holes for hollow parts.
- Use supports where needed.
- Check support contact points.
- Avoid trapped resin pockets.
- Check part thickness.
- Check surface details.
- Preview the full print setup in PreForm.
- Rename the file clearly before printing.

---

## Resin Printing Workflow

### 1. Prepare the file

Open the model in PreForm and choose:

- Printer model
- Resin type
- Layer thickness
- Orientation
- Support settings

### 2. Check the printer

Before printing:

- Check resin cartridge.
- Check resin tank.
- Check build platform.
- Check printer cleanliness.
- Check that the selected resin matches the installed resin.

### 3. Print

Start the job from PreForm or the printer touchscreen.

During printing:

- Do not open the printer cover unnecessarily.
- Watch for early failure if possible.
- Do not touch resin or printer internals without gloves.

### 4. Remove the part

After printing:

- Wear gloves.
- Remove the build platform carefully.
- Avoid dripping resin onto the printer or floor.
- Transfer the print to the washing area.

### 5. Wash

Wash the print using the approved solvent and washing method.

Common washing solvents may include:

- IPA
- TPM
- Other approved resin washing solvent

Follow GerLab staff instructions for wash time.

### 6. Dry

After washing:

- Let the part dry fully.
- Make sure solvent has evaporated before curing.
- Check for sticky or shiny uncured resin.

### 7. Cure

Cure the part using the approved UV curing system.

Curing depends on:

- Resin type
- Part thickness
- Material requirements
- Desired mechanical properties
- Formlabs resin instructions

### 8. Finish

After curing:

- Remove supports if not already removed.
- Sand support marks if needed.
- Inspect final surface.
- Record print result.

---

## Common Starting Settings

Resin printing settings are usually controlled by PreForm material profiles.

Do not manually guess exposure settings unless GerLab staff approve it.

| Use case | Suggested starting point |
|---|---|
| General resin printing | Use PreForm default profile |
| Fast draft print | Use Draft Resin if available |
| High detail model | Use 50 micron or 25 micron layer height |
| General prototype | Use 100 micron layer height |
| Smooth visual part | Use smaller layer height and good orientation |
| Stronger part | Use suitable engineering resin and correct post-cure |
| Hollow model | Add drain holes and wash internal cavities |
| Large part | Check suction forces, orientation, supports, and wash capacity |

---

## Recommended Beginner Settings

| Setting | Suggested value |
|---|---|
| Software | PreForm |
| Material | Standard resin, if approved |
| Layer height | 100 microns |
| Orientation | Angled, not flat against build platform |
| Supports | Auto-generated, then manually checked |
| Hollowing | Only when user understands drain holes |
| First user material | Grey Resin or Clear Resin, if available |
| Post-processing | Wash, dry, cure |

---

## GerLab Tested Settings Record

Use this table to record real GerLab results.

| Date | Printer | Resin | Layer Height | Supports | Wash Time | Cure Time | Result | Notes | Tested by |
|---|---|---|---:|---|---:|---:|---|---|---|
| YYYY-MM-DD | Form 3+ | Grey Resin | 100 µm | Auto | TBD | TBD | TBD | TBD | Name |
| YYYY-MM-DD | Form 3+ | Clear Resin | 100 µm | Auto | TBD | TBD | TBD | TBD | Name |
| YYYY-MM-DD | Form 3+ | Tough Resin | 100 µm | Auto | TBD | TBD | TBD | TBD | Name |
| YYYY-MM-DD | Form 3+ | Draft Resin | TBD | Auto | TBD | TBD | TBD | TBD | Name |

---

## Test Result Notes

When recording a test, describe the result clearly.

Useful result words:

- Print successful
- Print failed
- Supports failed
- Part detached
- Surface smooth
- Surface sticky
- Surface cloudy
- Cracked after curing
- Warped after curing
- Too many support marks
- Supports removed cleanly
- Details printed clearly
- Details missing
- Resin trapped inside
- Hollow part washed properly
- Good result
- Needs retest

Example:

| Date | Resin | Layer Height | Result | Notes |
|---|---|---:|---|---|
| 2026-07-11 | Grey Resin | 100 µm | Good print | Clean surface, supports removed well |
| 2026-07-11 | Clear Resin | 50 µm | Sticky surface | Wash longer or use cleaner solvent next time |

---

## Common Problems and Fixes

| Problem | Possible Cause | Fix |
|---|---|---|
| Print failed completely | Poor adhesion, wrong setup, dirty build platform | Clean platform, check resin, restart with correct setup |
| Part detached from supports | Weak supports, bad orientation, high peel force | Reorient part, increase support strength, check PreForm warnings |
| Supports failed | Support points too small or too few | Add stronger supports or change orientation |
| Part is sticky after washing | Not washed enough, dirty solvent, resin trapped | Rewash in clean solvent, dry fully, cure after drying |
| White residue after washing | Water/IPA contamination, drying issue, dirty solvent | Use clean solvent and dry fully before curing |
| Part warped | Poor orientation, thin geometry, over-curing, internal stress | Adjust orientation, support better, follow cure instructions |
| Cracks after curing | Hollow part trapped resin, over-curing, bad drain holes | Add drain holes, wash inside, adjust cure process |
| Details missing | Layer height too large, orientation issue, resin issue | Use smaller layer height, reorient, check resin |
| Surface roughness | Support placement, bad orientation, contaminated resin | Reorient, move support points, filter resin |
| Resin tank has cured debris | Failed print pieces in tank | Stop use, inspect tank, filter resin if approved |
| Cartridge not recognized | Cartridge issue, chip/contact issue | Reinstall cartridge, check printer message, ask staff |
| Bad smell or strong fumes | Solvent open, poor ventilation, resin spill | Close containers, ventilate, clean spill safely |
| Cloudy tank film | Tank wear or resin residue | Inspect tank, replace if required |

---

## Maintenance Notes

Possible maintenance items:

- Keep printer clean.
- Clean resin spills immediately.
- Inspect resin tank before printing.
- Check resin tank film for cloudiness, scratches, or cured debris.
- Keep resin cartridges closed.
- Store resin away from sunlight.
- Keep build platform clean.
- Filter resin only using approved method.
- Replace resin tank when worn.
- Keep washing solvent clean.
- Replace dirty IPA or solvent when needed.
- Keep curing unit clean.
- Report repeated print failures.
- Do not disassemble printer without staff permission.

---

## Resin Tank Notes

Before printing, check the resin tank.

Do not use the tank if:

- Film is damaged
- Film is cloudy
- Cured resin pieces are inside
- Resin is contaminated
- Resin type is unknown
- Tank has visible leak
- Tank is not installed correctly

Use separate tanks for different resin types when required.

---

## Waste Handling

Resin and solvent waste must be handled carefully.

General rules:

- Do not pour uncured resin into the sink.
- Do not pour contaminated IPA or solvent into the sink.
- Do not throw wet resin-contaminated tissues directly into normal trash unless GerLab procedure allows it.
- Cure resin-contaminated waste if required.
- Keep waste containers closed.
- Label waste containers clearly.
- Follow GerLab staff instructions and local waste rules.

---

## Beginner Workflow

1. Wear gloves and safety glasses.
2. Prepare model in PreForm.
3. Choose the correct printer.
4. Choose the correct resin.
5. Orient the model.
6. Generate supports.
7. Check printability.
8. Send file to printer.
9. Check resin cartridge and tank.
10. Start print.
11. Remove build platform carefully after printing.
12. Wash the print.
13. Let the print dry.
14. Remove supports carefully.
15. Cure the print.
16. Inspect final part.
17. Clean tools and workspace.
18. Record useful settings and result.

---

## Good Practice

Before printing:

- Start with a small test part.
- Use PreForm default settings first.
- Avoid printing large flat surfaces directly on the build platform.
- Angle parts to reduce suction forces.
- Use enough supports.
- Avoid hollow parts unless drain holes are properly designed.
- Keep resin away from sunlight.
- Keep solvent containers closed.
- Label resin tanks and resin cartridges clearly.
- Record successful settings.

---

## Source

This page is based on GerLab equipment information, GerLab use notes, and official Formlabs information.

Useful references:

- [Formlabs Form 3+ Desktop SLA 3D Printer](https://formlabs.com/3d-printers/form-3/)
- [Formlabs SLA 3D Printer Tech Specs](https://formlabs.com/3d-printers/resin/tech-specs/)

---

**Made with care in Mongolia.**

[← Previous: FDM 3D Printers](fdm-3d-printers.md) · [↑ Machine Library](README.md) · [Next: Vinyl Cutter →](vinyl-cutter.md)
