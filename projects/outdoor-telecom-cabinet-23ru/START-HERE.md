# Start here: 23RU Outdoor Telecom Cabinet

**One-page guide for contractors and reviewers**

## Which file to open

| You want to | Open |
|---|---|
| Edit the design in Fusion | `cad/outdoor-telecom-cabinet-23ru.f3d` |
| Open it in any other CAD tool | `cad/outdoor-telecom-cabinet-23ru.step` |
| Use the mesh | `cad/outdoor-telecom-cabinet-23ru.stl` |
| Read the drawings | `docs/drawings/` (4 SVG sheets and the PDF set, A2) |
| See every dimension, tolerance and fabrication note | `docs/SPECIFICATION.md` |
| See the model from every angle | `docs/images/` |
| Read the parts list and parameters | `data/` |

## Import check

After importing the STEP file you should see **2 bodies** in the same coordinate frame (Z up, X = 0 at the left edge of the cabinet in the front view, rear face at Y = 0, front face at Y = -965.2, door closed):

| Body | Qty | Volume | Size (X x Y x Z) |
|---|---|---|---|
| Cabinet | 1 | 17,982 cm3 | 761 x 965.2 x 1933 mm (includes roof eyes and mast) |
| Front door with handle | 1 | 1,690 cm3 | 705 x 21.5 x 1672 mm (Y -985.2 to -963.7) |

Overall envelope: 761 x 985.2 x 1933 mm.

## Status

Complete design release, Rev A: parametric 3D model, STEP, STL and Fusion exports, four-sheet dimensioned drawing set with bill of materials, tolerances, bend and weld schedules and fabrication notes, specification, parts list and multi-angle model views.

Model scope: shell, door, rack, mudroom and roof features. The temperature range, IP55 and 65 dB(A) values are design targets, not test results.

## Key facts

- 23RU, 19-inch rack (1022.35 mm), four rails with the EIA-310 hole pattern
- Shell 761 x 842.9 x 1778 mm, overall 761 x 985.2 x 1933 mm with rear housing, handle and mast
- 1.5 mm galvanised sheet steel (SGCC), RAL 7035 light grey powder coat
- Hinged front door with 13-slot louvre; rear filter housing
- Monopole side port, sloped mudroom, 4 M12 mounting holes
- Calculated mass 154.4 kg empty
