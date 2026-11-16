# Specification: Orange Pi Zero 3 Enclosure

| | |
|---|---|
| Product | Orange Pi Zero 3 enclosure with LCD window, card reader, power switch and reset pin |
| Drawing set | OPZ3-ENC-001 to OPZ3-ENC-004, Rev A, 2026-11-16 |
| Designer | Oluwatimileyin Oluleye |
| Software | Autodesk Fusion |
| Units | Millimetres |

## 1. Compatibility

- Board: Orange Pi Zero 3 (H618), 50 x 55 mm, with heat sink up to 14.5 mm tall
- Display: 2.8 in LCD module, 58 x 43.5 mm viewing window
- Card reader: microSD reader module, 13 x 2.2 mm front slot
- Controls: panel switch (12 mm hole) and reset pin (2.5 mm hole)

## 2. Coordinate system

Origin at the centre of the cavity. X runs along the 96.4 mm length, Y across the 64.4 mm width, Z from the rear face (z = 0) to the lid. Rear feet extend to z = -3. The +Y wall carries USB-C, HDMI, the switch and the reset hole. The -Y wall carries RJ45 and USB-A.

## 3. Overall dimensions

| Dimension | Value |
|---|---|
| Footprint | 96.4 x 64.4 mm, 4 mm corner radius |
| Height without feet | 33 mm (base 30 + lid 3) |
| Height with feet | 36 mm |
| Cavity | 90 x 58 mm, 0.8 mm corner radius |
| Cavity depth | 27.6 mm (30 mm tray height minus 2.4 mm rear wall) |
| Side wall / rear wall / lid | 3.2 / 2.4 / 3.0 mm |

## 4. Base tray (OPZ3-ENC-002)

| Feature | Specification |
|---|---|
| Corner bosses | 4x D8, centres at +/-41, +/-25; M3 insert hole D4.2 x 8 deep |
| Board standoffs | 4x D6, 14.5 mm tall, centres at +/-21.5, +/-24; pilot hole D2.2 x 6 deep |
| Vent louvers | 6x, 16 mm long (X), 2.2 mm opening, 45 deg, pitch 4.4, centres y = +/-2.2, +/-6.6, +/-11 |
| Rear feet | 4x D10 x 3 high at +/-40, +/-24 |
| Gasket groove | 1.8 mm wide x 1.2 mm deep in the rim (groove outline 91.4 x 59.4 inner, 95 x 63 outer) |

## 5. Front lid (OPZ3-ENC-003)

| Feature | Specification |
|---|---|
| Plate | 96.4 x 64.4 x 3.0 mm |
| LCD window | 58 x 43.5 mm through, centre X = -6 |
| Pane recess (underside) | 62 x 47.5 x 1.5 mm, centre X = -6, holds a 1 mm clear pane |
| Card-reader slot | 2.2 x 13 mm through, centre X = 35 |
| Screw holes | 4x D3.4 through at +/-41, +/-25, counterbore D6.4 x 1.4 deep |

## 6. Gasket (OPZ3-ENC-004)

| Feature | Specification |
|---|---|
| Section | 1.6 x 1.6 mm |
| Outline | 94.8 x 62.8 mm outer, 91.6 x 59.6 mm inner |
| Material | TPU 95A |
| Compression | 0.4 mm (25 %) when the lid is closed |

## 7. Openings

| Opening | Wall | Size (W x H) | Centre X, Z | Corner radius |
|---|---|---|---|---|
| USB-C power | +Y | 12.5 x 7.0 | -12.0, 15.2 | 2.0 |
| HDMI | +Y | 14.0 x 7.0 | 8.0, 15.3 | 2.0 |
| RJ45 | -Y | 17.5 x 14.5 | -12.0, 10.2 | 1.5 |
| USB-A | -Y | 15.0 x 9.0 | 13.0, 13.65 | 1.5 |
| Panel switch | +Y | D12 | -30.0, 14.0 | |
| Reset pin | +Y | D2.5 | 30.0, 14.0 | |

Openings are sized to pass standard plug overmolds.

## 8. Thermal and sealing design

- The board is mounted component-side down, so the heat sink sits in the 14.5 mm space between the board and the rear wall, over the vent field.
- The six vent slots pass through the 2.4 mm rear wall at 45 deg, which lets warm air out and stops drizzle passing straight through. Rear feet lift the unit 3 mm for airflow and drip clearance.
- The lid seals on a TPU gasket in a rim groove, and the LCD window is closed by a 1 mm clear pane held in a recess.
- Unused port openings can be fitted with printed or silicone caps for outdoor use.

## 9. Fasteners and inserts

| Item | Qty | Location |
|---|---|---|
| M3 heat-set insert, 5 mm | 4 | Base corner bosses |
| M3 x 8 pan-head screw | 4 | Lid to base |
| M2.5 x 6 self-tapping screw | 4 | Board to standoffs |

## 10. Materials, tolerances and printing

- Tray and lid: ASA (outdoor use) or PETG. Gasket: TPU 95A.
- General tolerance +/-0.2 mm (FDM). Press-fit clearances 0.2 mm, sliding clearances 0.3 mm.
- Orientation: tray feet down and open side up; lid outer face on the bed; gasket flat. No supports.
- Layer height 0.2 mm, 0.4 mm nozzle, 4 perimeters, 40 % infill (gasket: 3 perimeters, 100 % infill).
- Solid-model mass: 49.2 g tray, 10.8 g lid, 0.9 g gasket in ASA and TPU (60.9 g); 72.2 g with PETG.
