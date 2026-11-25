# Outdoor Telecom Cabinet System

![Outdoor telecom cabinet system, doors closed](docs/images/01-closed-front-right.png)

A fully modelled, dimensioned and documented **outdoor telecom cabinet system**: a RAN equipment cabinet paired with an external battery cabinet, designed in Autodesk Fusion. It combines direct-air cooling hoods, a 23RU rack, a 12 kW DC power system and three VRLA battery strings in a 72" (1829 mm) tall steel enclosure platform.

**Designer:** Oluwatimileyin Oluleye, CAD Designer
**Software:** Autodesk Fusion
**Drawing:** OTC-001, Rev A

## Design at a glance

| Parameter | Equipment cabinet | Battery cabinet |
|---|---|---|
| Overall size (H x W x D) | 1829 x 762 x 1204 mm | 1829 x 373 x 726 mm |
| Shell weight | ~272 kg (600 lb) | ~91 kg (200 lb) |
| Construction | Sheet steel 1.5 mm, white finish, galvanized hardware | Sheet steel, white finish, galvanized hardware |
| Doors | Front and rear, 120° swing | Single door, 110° swing |
| Cooling | Direct air: louvered intake hood, slotted exhaust hood, fans, filters | Direct air: intake louvers, filter, top exhaust fan |
| Heating | Door-mounted heater | — |
| Interior | 19" rails, 23RU, 12 kW DC power system | 4 shelves, 2 battery strings (8 blocks) |
| Input power | 208–240 VAC, 100 A maximum feed, 10 kAIC | — |

## Key features

- **Front intake hood** with two filter panels and two fans, and a **rear exhaust hood** with slotted outlet, filter and fan, for direct-air cooling.
- **Door kinematics:** revolute hinge joints with motion limits (equipment cabinet 120°, battery cabinet 110°), combination-lock handles and wind latches.
- **23RU 19" rack** with front and rear rails and RU markings.
- **12 kW DC power system:** 6-position rectifier shelf, controller with display, dual 22-position PDUs with independent LVDs, DC surge arrestors.
- **AC distribution:** load center with surge protection.
- **Battery system:** string 1 inside the equipment cabinet; strings 2 and 3 on four shelves in the external cabinet, with DC distribution panel and exhaust fan.
- **Monitoring:** front and rear door intrusion switches, clogged-filter switches, battery thermal probes.
- **Roof features:** screw-on GPS antenna mast and four lifting eye bolts on each cabinet.

## 3D design gallery

### Doors closed

| Front-right | Front-left |
|---|---|
| ![Front-right](docs/images/01-closed-front-right.png) | ![Front-left](docs/images/02-closed-front-left.png) |
| **Rear-right** | **Rear-left** |
| ![Rear-right](docs/images/03-closed-rear-right.png) | ![Rear-left](docs/images/04-closed-rear-left.png) |
| **High angle** | **Low angle** |
| ![High angle](docs/images/05-closed-high-angle.png) | ![Low angle](docs/images/06-closed-low-angle.png) |

### Doors open

| Front-right | Front-left |
|---|---|
| ![Open, front-right](docs/images/07-open-front-right.png) | ![Open, front-left](docs/images/08-open-front-left.png) |
| **High angle** | **Low angle** |
| ![Open, high angle](docs/images/09-open-high-angle.png) | ![Open, low angle](docs/images/10-open-low-angle.png) |

### Section A-A (interior)

| Front section | Isometric section |
|---|---|
| ![Section A-A front](docs/images/17-section-a-a-front.png) | ![Section A-A isometric](docs/images/18-section-a-a-isometric.png) |

### Orthographic views

| Front | Rear |
|---|---|
| ![Front view](docs/images/11-front-view.png) | ![Rear view](docs/images/12-rear-view.png) |
| **Left** | **Right** |
| ![Left view](docs/images/13-left-view.png) | ![Right view](docs/images/14-right-view.png) |
| **Top (doors closed)** | **Top (doors open)** |
| ![Top view](docs/images/15-top-view.png) | ![Top view, doors open](docs/images/16-open-top-view.png) |

## Technical drawing

**OTC-001**, A3, scale 1:20, third-angle projection: front elevation, section A-A, right side elevation, top plan with door swing, full dimensioning and a numbered parts list.

[`docs/drawings/OTC-001_general-arrangement.pdf`](docs/drawings/OTC-001_general-arrangement.pdf)

## Project files

| Path | Contents |
|---|---|
| `cad/outdoor-telecom-cabinet-system.f3d` | Editable Fusion design with feature history, joints and section view |
| `cad/outdoor-telecom-cabinet-system.step` | STEP assembly for any CAD tool |
| `cad/outdoor-telecom-cabinet-system.stl` | STL mesh of the assembly |
| `docs/drawings/` | General-arrangement drawing (PDF) |
| `docs/SPECIFICATION.md` | Full product specification |
| `docs/images/` | 18 model views |
| `data/` | Bill of materials and design parameters (CSV) |

## Component structure

```
Outdoor Telecom Cabinet System
├── Equipment Cabinet (RAN)
│   ├── EC-01 Shell and Plinth
│   ├── EC-02 Front Door Assembly
│   ├── EC-03 Rear Door Assembly
│   ├── EC-04 Door Hinges
│   ├── EC-05 GPS Antenna Mast
│   ├── EC-06 Lifting Eye Bolts
│   ├── EC-07 Side Interface Panel
│   ├── EC-08 19in Rack Rails 23RU
│   ├── EC-09 12kW DC Power System
│   ├── EC-10 Dual PDUs
│   ├── EC-11 AC Load Center and Surge Protection
│   ├── EC-12 Alarm and Sensors
│   └── EC-13 Internal Battery String 1
└── Battery Cabinet (External)
    ├── BC-01 Shell
    ├── BC-02 Door Assembly
    ├── BC-03 Door Hinges
    ├── BC-04 Battery Strings 2 and 3
    ├── BC-05 DC Distribution
    ├── BC-06 Exhaust Fan
    ├── BC-07 Alarm and Sensors
    └── BC-08 Lifting Eye Bolts
```
