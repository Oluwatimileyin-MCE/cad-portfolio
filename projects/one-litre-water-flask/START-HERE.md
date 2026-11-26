# Start here: One-Litre Threaded Water Flask

**One-page guide for contractors and reviewers**

## Which file to open

| You want to | Open |
|---|---|
| Edit the design in Fusion | `cad/one-litre-water-flask.f3d` |
| Open it in any other CAD tool | `cad/one-litre-water-flask.step` |
| 3D print or view the mesh | `print/` (assembly STL and one STL per part) |
| Read the drawings | `docs/drawings/` (5 SVG sheets, A3, plus a combined PDF) |
| See every dimension and material | `docs/SPECIFICATION.md` |
| Assemble and use it | `docs/ASSEMBLY_AND_OPERATION.md` |
| See adjustable values and the bill of materials | `data/` |

## Import check

After importing the STEP file you should see **6 bodies** in one coordinate frame (closed position, Z is the bottle axis):

| Body | Volume | Bounding box (X x Y x Z) |
|---|---|---|
| Flask body | 187.97 cm3 | 82.0 x 82.0 x 245.9 mm (z 0 to 245.9) |
| Cap | 17.13 cm3 | 88.5 x 58.0 x 19.0 mm (z 231.4 to 250.4) |
| Cap gasket | 0.96 cm3 | 54.0 x 54.0 x 2.0 mm (z 245.4 to 247.4) |
| Strap | 3.22 cm3 | 75.0 x 56.0 x 5.0 mm (z 224.4 to 229.4) |
| Link ring A | 0.24 cm3 | 26.0 x 2.0 x 26.0 mm (z 211 to 237) |
| Link ring B | 0.18 cm3 | 2.0 x 20.0 x 20.0 mm (z 220 to 240) |

The gasket overlaps the neck land by 0.5 mm. This is the designed gasket squeeze.

## Status

Complete design release, Rev B: six-body 3D assembly, five-sheet drawing set, specification, assembly guide, STEP and STL files, and fit, clearance and motion checks in CAD.

## Key facts

- Capacity 1000 mL to the brim, 250.4 mm tall, 82 mm diameter
- 3-start thread, lead 9.0 mm: the cap releases after about 1.6 turns (14.5 mm)
- 2.0 mm silicone face gasket with 0.5 mm squeeze
- Cap stays attached through a strap ring and two interlinked silicone link rings
- Food-contact PP body and cap; food-grade silicone gasket, strap and rings; 190.9 g empty

## Questions?

**Oluwatimileyin Oluleye**, CAD Designer: oluwatimileyinoluleye@gmail.com
