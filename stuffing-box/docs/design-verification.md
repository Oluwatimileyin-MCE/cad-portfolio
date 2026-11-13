# Design Verification

## 1. Design basis

| Parameter | Value |
|---|---|
| Fluid pressure | 1 MPa (10 bar) |
| Packing annulus (Ø42 / Ø24) | 933 mm² |
| Gland stress on packing | 10 MPa (seating) |
| Gland load | 9.33 kN total, 4.67 kN per stud |
| Pressure thrust at 1 MPa | 0.93 kN (seating load governs) |

Material strengths (handbook values): AISI 1018 hot-rolled yield about 220 MPa; gray iron ASTM A48 Class 30 tensile strength about 207 MPa; soft brass yield about 124 MPa (conservative).

## 2. Strength results

Analytical checks using standard beam, tension and shear models.

| Check | Stress | Allowable | Factor of safety |
|---|---|---|---|
| Stud tension (M12, 84.3 mm² stress area) | 55.3 MPa | 220 MPa | 4.0 |
| Gland flange bending (84 mm span) | 28.1 MPa | 124 MPa | 4.4 |
| Body top-flange bending | 28.0 MPa | 207 MPa | 7.4 |
| Stud thread shear in cast iron | 16.5 MPa | about 190 MPa | > 10 |
| Neck hoop stress at 1 MPa (Ø66 / Ø42) | 2.4 MPa | - | very high |

Method:
- **Studs:** axial load of 4.67 kN over the 84.3 mm² tensile stress area. Studs can carry about 22 kN total gland load at 0.6 x yield, so the packing is the practical limit.
- **Gland flange:** simply supported beam between the studs with a central load, M = F.L/4 = 196 N.m. Section properties (area 1143 mm², I = 183,871 mm⁴) were integrated numerically from the real cross-section including bore, spigot and lead-in cone.
- **Body flange:** cantilever from the neck (radius 33 mm) to the stud axis (radius 42 mm).
- **Thread shear:** 15 mm engagement, shear area 0.5 x pi x d x L = 283 mm².
- **Neck:** Lame thick-wall cylinder at 1 MPa.

Design notes:
- Thread engagement in the body is 15 mm (1.25 x d). Stress is well within limits; a local boss increasing this to 18 mm (1.5 x d) is the usual practice for cast iron if the stud is expected to be frequently removed.
- Nut height 10 mm is 0.83 x d, meeting the 0.8 x d minimum.

## 3. Kinematic study (Autodesk Fusion)

Joint set: Body grounded; Bush, Studs and Nuts rigid; Gland on a slider along the stud axis (limits +5 / -8 mm); Shaft on a revolute joint in the Bush. The gland was stepped through its full travel and the shaft rotated 360 degrees in 45 degree steps, with interference analysis at every position.

| Gland position | Flange-to-body gap | Packing depth | Interference |
|---|---|---|---|
| Fully loosened (+5 mm) | 18 mm | 23 mm | None |
| Home (0 mm) | 13 mm | 18 mm | None |
| Fully tightened (-8 mm) | 5 mm | 10 mm | None |
| Shaft 0 to 360 degrees | - | - | None |

Working-travel guidance: packing compression of about 22% (4 mm of gland travel) is recommended; full mechanical travel compresses the packing space by 44%.

## 4. Dimensional conformance

The CAD model reproduces the source layout: body 120 x 72 x 50 mm with 15 mm flanges, Ø42 chamber, Ø33 bore, Ø66 neck, 84 mm stud centres; gland Ø42 x 30 spigot, 15 mm flange, 45 mm height, Ø24 bore, Ø13 holes; bush Ø33 / Ø42 / Ø24 and 15 mm long; Ø12 x 90 mm stud; M12 nut. Parts list quantities and materials match.

## 5. Conclusion

Under the stated design basis every stressed component has a factor of safety of at least 4, and the assembly operates through its full range of motion without interference. The design is suitable for manufacture as specified.
