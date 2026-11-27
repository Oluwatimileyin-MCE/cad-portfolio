# Start here: Outdoor Telecom Cabinet 900 x 900 x 2060

**One-page guide for contractors and reviewers**

## Which file to open

| You want to | Open |
|---|---|
| Edit the design in Fusion | `cad/outdoor-telecom-cabinet-900.f3d` |
| Open it in any other CAD tool | `cad/outdoor-telecom-cabinet-900.step` |
| Use the mesh | `cad/outdoor-telecom-cabinet-900.stl` |
| Read the drawing | `docs/drawings/OTC-900-001_general-arrangement.svg` (A1) |
| See every specification | `docs/SPECIFICATION.md` |
| See the model from every angle | `docs/images/` |
| Read the parts list and parameters | `data/` |

## Model check

The model is one assembly in a single coordinate frame (Z up, origin at the centre of the plinth on the floor plane, front face towards -Y, door closed):

| Item | Value |
|---|---|
| Bodies | 122 in 27 components (36 instances) |
| Overall envelope | 1075 x 995 x 2060 mm (includes air conditioner and door handle) |
| Plinth | 950 x 950 x 100 mm |
| Body | 900 x 900 mm, Z 100 to 1957.3 mm |
| Roof | Z 1957.3 to 2060 mm |

## Status

Complete design release, Rev A: jointed 3D assembly with opening door, STEP, STL and Fusion exports, dimensioned general arrangement drawing, specification, parts list and multi-angle model views.

Model scope: enclosure, door, rack, battery compartment, air conditioner and sensors. Batteries, rectifiers, DC distribution, fibre panel, monitoring unit and air conditioner are modelled as dimensioned envelopes, and their masses are modelled values.

## Key facts

- 2 mm galvanised sheet steel body, roof and door; 5 mm plinth
- Door with 3 hinges, handle with barrel lock and gasket; opens to 110 degrees
- 19-inch rack, 30U, 3 equipment shelves, 450 mm clear width
- 1500 W air conditioner on the right-hand wall
- Plinth with 4 hoisting holes (dia 40) and 4 anchor holes (dia 18)
- Enclosure shell mass 235.4 kg (CAD)
