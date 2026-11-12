# Start here (for contractors and reviewers)

**What this is:** a rectangular food container with a gasketed lid and four latch clips. Seven parts: body, lid, silicone gasket and four identical clips. This page tells you which file to open and what to check first.

**Units:** millimetres. **Materials:** polypropylene (body, lid, clips) and silicone (gasket).

---

## 1. Which file do I open?

| I want to... | Open this |
|---|---|
| Import the model into my CAD tool | [`cad/clip-lock-container.step`](cad/clip-lock-container.step) |
| Edit the design in Autodesk Fusion | [`cad/clip-lock-container.f3d`](cad/clip-lock-container.f3d) |
| See the technical drawings | [`docs/clip-lock-container_drawing.pdf`](docs/clip-lock-container_drawing.pdf) |
| Read the full specification and materials | [`docs/SPECIFICATION.md`](docs/SPECIFICATION.md) |
| See every dimension | [`data/design_parameters.csv`](data/design_parameters.csv) |
| See the bill of materials | [`data/bill_of_materials.csv`](data/bill_of_materials.csv) |
| See the validation numbers | [`data/validation_results.csv`](data/validation_results.csv) |
| Understand the design | [`README.md`](README.md) |
| Just look at it | [`docs/images/`](docs/images/) |

## 2. Check the import worked

The STEP file contains four unique solids: `Body`, `Lid`, `Gasket` and `Clip` (the clip is placed four times). The assembly is closed, the origin is the centre of the body footprint and Z points up. After import, check:

- Body rim collar measures **188 x 138 mm** and the body is **65 mm** tall.
- Overall extents are **x -102 to 102, y -77 to 77, z 0 to 72 mm**.
- One clip sits centred on each of the four sides.

If these do not match, check your import unit setting (millimetres).

## 3. Key numbers at a glance

| | |
|---|---|
| Overall size (closed) | 204 x 154 x 72 mm |
| Body | 188 x 138 x 65 mm, 2.0 mm walls, 2.5 mm floor |
| Capacity | approx. 1.37 L brim-full |
| Lid | 188 x 138 x 3 mm plate, 140 x 90 x 1.0 mm recessed panel |
| Gasket | 2.0 x 1.5 mm silicone, 185 x 135 mm seal path |
| Clips | 4 x PP, 40 mm wide, 2 mm strap, 90 degree locking ledge |
| Mass | 200.8 g |
| Clip stress at closing | 11.1 MPa (yield 30.3 MPa, safety factor 2.7) |
| Closing force | approx. 16 N per clip |
| Interference | None |

## 4. What is included

- Complete 3D assembly with materials assigned
- 6-sheet A3 drawing set: assembly plus body, lid, gasket and clip
- Specification, bill of materials and parameter table
- Interference check and snap-fit analysis with results

## 5. Questions?

**Oluwatimileyin Oluleye**, CAD Designer
[oluwatimileyinoluleye@gmail.com](mailto:oluwatimileyinoluleye@gmail.com) · [LinkedIn](https://www.linkedin.com/in/oluwatimileyinoluleye)
