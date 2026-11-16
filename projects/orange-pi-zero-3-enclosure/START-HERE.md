# Start here: Orange Pi Zero 3 Enclosure

**One-page guide for contractors and reviewers**

## Which file to open

| You want to | Open |
|---|---|
| Edit the design in Fusion | `cad/orange-pi-zero-3-enclosure.f3d` |
| Open it in any other CAD tool | `cad/orange-pi-zero-3-enclosure.step` |
| Print it | `print/` (3 STL files, already in print orientation) |
| Read the drawings | `docs/drawings/` (4 SVG sheets, A3) |
| See every dimension and material | `docs/SPECIFICATION.md` |
| Build it | `docs/ASSEMBLY.md` |

## Import check

After importing the STEP file you should see **3 bodies** in the same coordinate frame:

| Body | Volume | Bounding box (X x Y x Z) |
|---|---|---|
| Base tray | 46.03 cm3 | 96.4 x 64.4 x 33 mm (z -3 to 30) |
| Front lid | 10.06 cm3 | 96.4 x 64.4 x 3 mm (z 30 to 33) |
| TPU gasket | 0.78 cm3 | 94.8 x 62.8 x 1.6 mm (z 28.8 to 30.4) |

The lid and gasket overlap by 0.195 cm3. This is the designed 0.4 mm gasket compression.

## Status

Complete design release, Rev A: parametric 3D assembly, four-sheet drawing set, specification, assembly guide, print-ready STL files and interference-checked model.

## Key facts

- Footprint 96.4 x 64.4 mm, height 36 mm including feet
- ASA or PETG tray and lid, TPU 95A gasket
- Standard hardware: M3 heat-set inserts, M3 x 8 and M2.5 x 6 screws
- No supports needed on any part
