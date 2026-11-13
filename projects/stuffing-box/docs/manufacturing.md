# Manufacturing Plan

## 1. Process summary

| Part | Stock | Primary process | Finishing |
|---|---|---|---|
| 1 Body | Casting, stress-relieved | CNC milling | Bore finishing to H8 / H7, tapping |
| 2 Gland | Brass bar / plate | CNC milling and turning | Ream bore to H9 |
| 3 Bush | Brass bar | CNC lathe | Grind or finish-turn spigot to p6 |
| 4 Stud | Ø12 mild steel bar | CNC lathe | Thread rolling or cutting, 6g |
| 5 Nut | AF 19 hex bar | CNC lathe | Tap M12 x 1.75-6H |
| 6 Shaft | Ø24 steel bar | Bought-in | - |

A standard M12 hex nut may be substituted for Part 5.

## 2. Body - CNC milling (Fusion Manufacture setup S1)

Stock: casting with 2 mm machining allowance. Work coordinate origin at the top centre of the stock; datum Z on the machined top face.

| Op | Operation | Tool | Notes |
|---|---|---|---|
| 1 | Face top | Face mill Ø50 | Ra 3.2 |
| 2 | Drill 2 x tap-drill holes | Drill Ø10.2 | Through top flange, 84 mm centres |
| 3 | Bore chamber Ø42 H8 | Flat end mill Ø16, helical | 41 mm deep, Ra 1.6 |
| 4 | Tap M12 x 1.75 | Tap, M12 right hand | 2 holes |
| 5 | Bore shaft hole Ø33 H7 | Flat end mill Ø16, helical | Through the chamber floor, 9 mm long |

Toolpaths for operations 1 to 5 were generated and validated in Fusion with no errors or warnings.

## 3. Gland - CNC milling (Fusion Manufacture setup S2)

Stock: brass with 2 mm side and 1 mm top allowance.

| Op | Operation | Tool | Notes |
|---|---|---|---|
| 1 | Face top | Face mill Ø50 | Ra 3.2 |
| 2 | Profile flange outline | Flat end mill Ø16 | 120 x 72 mm, R18 / R76 |
| 3 | Drill stud holes | Drill Ø13 | 2 holes, through |
| 4 | Bore shaft hole | Flat end mill Ø12 | Finish ream to Ø24 H9 |

Toolpaths for operations 1 to 4 were generated and validated in Fusion with no errors or warnings. The Ø42 f8 spigot and the Ø50 lead-in cone are produced by turning.

## 4. Turned parts

| Part | Sequence |
|---|---|
| Bush | Face, turn Ø42 collar and Ø33 spigot, drill and bore Ø24 H8, chamfer, part off |
| Stud | Face both ends, chamfer, cut or roll M12 x 1.75 (15 mm and 58 mm), part off |
| Nut | Face, drill Ø10.2, chamfer 30 degrees both faces, tap M12 x 1.75, part off |

## 5. Inspection plan

| Characteristic | Method |
|---|---|
| Flange outline, 84 mm stud centres, 50 mm height | CMM or calipers / height gauge |
| Bores Ø42 H8, Ø33 H7, Ø24 H8 / H9 | Bore gauge or plug gauge |
| Spigots Ø33 p6, Ø42 f8 | Micrometer |
| M12 threads | Go / no-go thread gauges (6g ring, 6H plug) |
| Surface finish | Ra 1.6 on bores and spigots, Ra 3.2 elsewhere (comparator or profilometer) |
| Casting | Visual and dimensional; no cracks or porosity at machined faces |

## 6. Assembly

1. Press the bush into the body shaft hole (Ø33 H7 / p6).
2. Screw the studs into the body to full thread depth.
3. Insert the shaft through the bush.
4. Place the packing in the chamber, then fit the gland over the studs.
5. Fit the nuts and tighten evenly, working travel up to about 4 mm.
