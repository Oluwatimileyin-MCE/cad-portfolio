# Start here (for contractors and reviewers)

**What this is:** a 750 mL clear takeaway container. One base and one snap-fit lid with an integral plug seal. This page tells you what to open first and what is and is not finished.

**Units:** millimetres. **Material (per spec):** clear PET, base walls 0.65 mm, lid 0.5 mm. Material behaviour has not been simulated.

---

## 1. Which file do I open?

| I want to... | Open this |
|---|---|
| Import the model into my CAD tool | [`cad/takeaway-container-750.step`](cad/takeaway-container-750.step) |
| Edit the design in Autodesk Fusion | [`cad/takeaway-container-750.f3d`](cad/takeaway-container-750.f3d) |
| See the 2D drawing | [`docs/CTC-750-004_revD_drawing.svg`](docs/CTC-750-004_revD_drawing.svg) (see warning in section 4) |
| See every dimension and which ones can be changed | [`data/fusion_parameters.csv`](data/fusion_parameters.csv) |
| See how the fit was tested and the raw numbers | [`data/verification_results.csv`](data/verification_results.csv) |
| Understand the design process and results | [`README.md`](README.md) |
| See what changed between revisions | [`CHANGELOG.md`](CHANGELOG.md) |
| Just look at it | [`docs/images/`](docs/images/) |

## 2. Check the import worked

The STEP file contains **two bodies**: `Base` and `Lid`. The lid is in the **closed** position. The origin is at the centre of the footprint with Z pointing up. After import, check:

- Base flange measures **190 × 130 mm**.
- Base height (bottom to flange top) is **52 mm**.
- Lid sits on the flange, with a thumb tab sticking out of one short end (to x = 108 mm).

If these do not match, the import scale is wrong. Check your import unit setting.

The STEP file is in millimetres. Its overall extents are x -95.8 to 108.0, y -65.8 to 65.8 and z 0 to 54 mm (108 is the end of the thumb tab; 54 is the top of the lid stacking ring). The internal product name is a date stamp from Fusion; ignore it. The solids are named `Base` and `Lid`.

## 3. Key numbers at a glance

| | |
|---|---|
| Capacity | 750 mL at a fill line **39.31 mm** above the inside floor |
| Flange | 190 × 130 mm, R12 corners, 0.65 mm thick |
| Footprint | 164 × 104 mm |
| Wall draft | 12.09° per side |
| Lid clearance to flange | 0.30 mm per side |
| Snap catch | 6 pads, 0.8 mm capture under the flange |
| Seal | Plug wall 3 mm deep, 0.10 mm radial interference |
| Thumb tab | 13 × 20 × 0.5 mm, on one short end |

## 4. What is done and what is not

**Done**
- Drawing and spec audited; errors found and fixed (see `CHANGELOG.md`).
- Fully parametric CAD model.
- Digital close/open fit test: lid enters without a jam point, seats fully, and catch pads end up under the flange.

**Not done: please do not assume these**
- **No physical prototype or leak test has been made.**
- **The 2D drawing is out of date.** It shows the older Rev D values (catch capture 0.50, pad height 0.8, lead-in 0.4) and has no release chamfer or thumb tab. **Use the STEP file and the parameter table for current dimensions, not the drawing.**
- **No tolerances are defined** on the drawing or spec.
- Lid ribs and stacking ring are solid stand-ins for formed features.
- Worst-case catch capture is only **0.3 mm** (lid shifted to the clearance limit). Under review.
- Sheet gauge and the real thermoformed thickness have not been confirmed with a thermoformer.

## 5. Decisions still open

1. Catch capture: keep 0.8 mm, or raise to 1.0 mm for a safer worst-case margin (needs about 1.0 mm lid deflection on entry).
2. Whether to tighten the lid clearance below 0.30 mm.
3. Tolerance scheme for the drawing re-issue.

## 6. Questions?

**Oluwatimileyin Oluleye**, CAD Designer
[oluwatimileyinoluleye@gmail.com](mailto:oluwatimileyinoluleye@gmail.com) · [LinkedIn](https://www.linkedin.com/in/oluwatimileyinoluleye)
