# Product specification: Four-Side Clip-Lock Food Container

All dimensions in millimetres unless stated. Full table: [`../data/design_parameters.csv`](../data/design_parameters.csv).

## 1. Product

A rectangular food container with a gasketed lid held shut by four polypropylene latch clips, one centred on each side. The four clips pull the lid evenly onto a silicone seal. The lid has a recessed centre panel for stiffness and labelling.

| | |
|---|---|
| Overall size (closed, clips fitted) | 204 x 154 x 72 |
| Body footprint at rim | 188 x 138 |
| Body height | 65 |
| Brim-full capacity | approx. 1.37 L |
| Total mass | 200.8 g |
| Number of parts | 7 (body, lid, gasket, four identical clips) |

## 2. Parts

### Container body

| Feature | Value |
|---|---|
| Wall envelope / inner cavity | 180 x 130 (R14) / 176 x 126 (R12) |
| Wall thickness / floor thickness | 2.0 / 2.5 |
| Rim collar | 188 x 138 (R18), 3.0 thick, at 62 to 65 height |
| Floor fillet | R3 |
| Catch pads | 4 pcs, 50 wide x 5 high, project 3.5 from the wall, at 50 to 55 height |
| Material | Polypropylene (PP) |

### Container lid

| Feature | Value |
|---|---|
| Plate | 188 x 138 x 3 (R18), matches the body rim collar |
| Recessed centre panel | 140 x 90, 1.0 deep |
| Gasket groove | 1.5 deep, in the underside of the plate |
| Catch ears | 4 sets of two 4 mm prongs, one set per side, projecting to 202 x 152 overall |
| Overall height | 7 |
| Material | Polypropylene (PP) |

### Sealing gasket

| Feature | Value |
|---|---|
| Cross-section | 2.0 wide x 1.5 thick |
| Outer / inner size | 185 x 135 (R16.5) / 181 x 131 (R14.5) |
| Material | Silicone rubber |

### Latch clip (x4)

| Feature | Value |
|---|---|
| Size | 40 wide x 10 deep x 27 high |
| Strap | 2.0 thick, flexing length approx. 19 |
| Lip | 1.0 ledge with a 90 degree return face |
| Material | Polypropylene (PP) |

## 3. Materials

| Material | Used for | Key properties (from the Fusion material library) |
|---|---|---|
| Polypropylene (PP) | Body, lid, four clips | E 1.34 GPa; yield 30.3 MPa; tensile 36.5 MPa; density 0.899 g/cm3; Poisson 0.39 |
| Silicone rubber | Sealing gasket | Compliant seal, 1.5 mm section |

## 4. Bill of materials

| Item | Part | Qty | Material | Mass each (g) | Mass total (g) |
|---|---|---|---|---|---|
| 1 | Container Body | 1 | PP | 128.2 | 128.2 |
| 2 | Container Lid | 1 | PP | 59.9 | 59.9 |
| 3 | Sealing Gasket | 1 | Silicone | 2.3 | 2.3 |
| 4 | Latch Clip | 4 | PP | 2.6 | 10.4 |
| | **Total** | **7** | | | **200.8** |

## 5. Function

- **Closing:** the lid sits on the body rim with the gasket between them. Each clip strap flexes about 1 mm to pass over the lid catch, then returns and locks on a flat 90 degree ledge. Closing force is about 16 N per clip.
- **Sealing:** the four clips load the gasket evenly around the full 185 x 135 seal path.
- **Opening:** each clip releases individually by hand.
- **Cleaning:** the gasket lifts out of its groove and the clips are separate parts.

## 6. Tolerances

General tolerances ISO 2768-m unless otherwise stated on the drawing.

## 7. Performance summary

| Check | Result |
|---|---|
| Part interference | None (0 of 7 components) |
| Clip stress at closing | 11.1 MPa against 30.3 MPa yield (safety factor 2.7) |
| Clip strain at closing | 0.83 % against 2.26 % yield strain |
| Maximum elastic clip deflection | 2.7 mm |
| Clip tensile capacity | 2.4 kN per clip |

Full results: [`../data/validation_results.csv`](../data/validation_results.csv).
