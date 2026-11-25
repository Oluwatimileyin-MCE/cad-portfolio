# Start here: Outdoor Telecom Cabinet System

**One-page guide for contractors and reviewers**

## Which file to open

| You want to | Open |
|---|---|
| Edit the design in Fusion | `cad/outdoor-telecom-cabinet-system.f3d` |
| Open it in any other CAD tool | `cad/outdoor-telecom-cabinet-system.step` |
| Use a mesh | `cad/outdoor-telecom-cabinet-system.stl` |
| Read the drawing | `docs/drawings/OTC-001_general-arrangement.pdf` |
| See every dimension and material | `docs/SPECIFICATION.md` |
| See the model from every angle | `docs/images/` |
| Read the parts and parameter data | `data/` |

## Import check

After importing the STEP file you should see **248 bodies** in one coordinate frame (Z up, equipment cabinet front-left-bottom corner at the origin, front face at Y = 0, doors closed, battery cabinet offset 914 mm along X):

| Item | Size (X x Y x Z) |
|---|---|
| Equipment cabinet body | 762 x 1204 x 1829 mm (depth includes both hoods) |
| Battery cabinet body | 373 x 726 x 1829 mm |
| Overall envelope | 1292 x 1204 x 2019 mm (including GPS mast and lifting eyes) |

## Status

Complete design release, Rev A: parametric 3D assembly with working door joints, section view, STEP, STL and Fusion exports, dimensioned general-arrangement drawing, specification, parts list and multi-angle model views.

## Key facts

- Equipment cabinet 1829 x 762 x 1204 mm with 23RU of 19" rack space
- External battery cabinet 1829 x 373 x 726 mm
- 12 kW DC power system, dual 22-position PDUs, three battery strings
- Direct-air cooling with front intake and rear exhaust hoods
- 208–240 VAC input, 100 A maximum feed
