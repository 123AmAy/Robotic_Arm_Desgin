# Robotic_Arm_Desgin
# Robotic Arm Manipulator

> 4-DOF aluminium robotic arm designed for pick-and-place and fine assembly tasks.
> Built by P1 Group 5, BITS Pilani — Section P1 (Jan – Apr 2025).

![Isometric View](media/isometric.png)

## Overview

A robotic manipulator fabricated entirely from aluminium, designed for precision
handling in industrial automation workflows. The project covered end-to-end
mechanical design, engineering drawings, and full fabrication across four
manufacturing labs.

> **Note:** Servo actuation was planned but not implemented in this phase.
> Motor mounts and encoder brackets were designed and are ready for integration.

## Features

- 4 degrees of freedom with parallelogram linkage for end-effector orientation stability
- Bell-crank mechanism constraining arm motion throughout full range
- Complete 28-part aluminium Bill of Materials with engineering drawings
- Servo and encoder mounts designed for future actuation integration
- Standard M3 / M4 / M6 stainless steel fasteners throughout

## CAD Views

| Side View | Isometric View |
|-----------|---------------|
| ![side](media/side_view.png) | ![iso](media/isometric.png) |

| Top View | Front View |
|----------|-----------|
| ![top](media/top_view.png) | ![front](media/front_view.png) |

Assembly videos: [Google Drive](https://drive.google.com/drive/folders/1t2eTLGanw_q-xP1X9Zex6FVyx89WHU4U?usp=sharing)

## Bill of Materials (summary)

| # | Part | Material | Qty |
|---|------|----------|-----|
| 1 | Base assembly (bottom, sides, top, bearing parts) | Aluminium | 8 |
| 2 | Arm linkage (Arm 1A, 1A-B, 2-1A, 2-1A-B) | Aluminium | 4 |
| 3 | Levers & bell-crank (lifting levers, actuator arm) | Aluminium | 5 |
| 4 | End effector & servo platform | Aluminium | 2 |
| 5 | Spacers (1–6) | Aluminium | 6 |
| 6 | Clamps & mounts | Aluminium | 3 |
| 7 | Fasteners (M3 / M4 / M6 screws, washers, standoffs) | Stainless steel | 74+ |

Full BOM in [`docs/report.pdf`](docs/report.pdf)

## Manufacturing Processes

- **Metal cutting** — raw aluminium stock to size
- **Sheet metal forming** — bends in structural components
- **Lathe** — spacers and cylindrical parts
- **CNC milling** — hole drilling and surface profiling

## Repository Structure

```
robotic-arm/
├── README.md
├── CAD/
│   ├── Final_Assembly.SLDASM
│   └── parts/              ← individual .SLDPRT files
├── Drawings/               ← corrected engineering drawings
├── docs/
│   └── report.pdf
└── media/
    ├── side_view.png
    ├── top_view.png
    ├── front_view.png
    ├── back_view.png
    └── isometric.png
```

## Team

| Member | ID |
|--------|----|
| Vivek Gunuganti (Group Leader) | 20230395 |
| Pulkit Maheshwari | 20230413 |
| Raj Vardhan Jain | 20230433 |
| Shivansh Srivastava | 20221124 |
| Shobhit Methi | 20230469 |
| Ayush Aman | 20230228 |
| Divyansh Bohara | 20230448 |
| Himanshu Gupta | 20230160 |
| NageswaraSatyaShirdinadh Avupati | 20230446 |
| Harshit Jaiswal | 20231286 |

Section P1, Group 5 — BITS Pilani (2025)

## License

MIT — CAD files free to use for educational purposes.
