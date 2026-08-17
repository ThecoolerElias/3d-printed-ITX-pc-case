# 3d-printed-Mini-ATX-pc-case

A custom designed and 3D printed Micro-ATX PC case with laser cut wood and acrylic side panels. Built around a zero cost Frankenstein gaming build running CachyOS.

---

### Project Status

- Designing skeleton frame in Fusion 360

---

### Inspiration

<img width="447" height="331" alt="image" src="https://github.com/user-attachments/assets/d0c9ac23-1919-487e-9a7f-13d117e3f133" />

---

### Design Goals

- As compact as possible while maintaining adequate airflow
- Skeleton frame design with laser cut panels for a clean aesthetic
- PETG skeleton for heat resistance near components
- 3mm plywood and acrylic side panels cut via school laser cutter
- Panels exported as DXF from Fusion 360 for direct use in laser cutter software
- Designed around a 120mm AIO radiator mounted as a structural/visual element

---

### Specifications

#### Main Linux Gaming Build

A zero cost Frankenstein build combining parts from two old PCs into a capable Linux gaming machine running CachyOS.

| Component | Spec |
|---|---|
| **CPU** | Intel Core i5-8400 (Coffee Lake, LGA1151, 6 core) |
| **GPU** | Asus GeForce GTX 1070 Ti 8GB ROG Strix |
| **Motherboard** | ASUS PRIME H310M-D (Micro-ATX, LGA1151) |
| **CPU Cooler** | 120mm AIO |
| **RAM** | 16GB DDR4 |
| **Primary Storage** | 1TB NVMe M.2 SSD |
| **PSU** | Corsair VS650 650W |
| **Fan Hub** | Powered PWM fan hub (dedicated SATA power connector) |
| **Case Fans** | 2x 120mm intake + 1x 120mm AIO radiator fan |

---

#### Operating System

- **Distro** — CachyOS (Arch-based)
- **Kernel** — CachyOS kernel with BORE scheduler patches
- **GPU Driver** — NVIDIA proprietary
- **Gaming Layer** — Steam + Proton

---

#### Build Notes

- Fan hub draws power from molex connector on PSU — all fans connect to hub, single PWM signal wire runs to motherboard chassis header
- Total build cost — $0

---

#### Parts Origin

| Component | Source |
|---|---|
| i5-8400, GTX 1070 Ti, H310M-D, DDR4, Corsair VS650 | scrap pc i found in the trash |
| 1TB NVMe, 2TB HDD, 500GB HDD | found in other trashed pcs and old workstations|

---

### Bill of Materials

| Item | Material | Notes |
|---|---|---|
| Skeleton frame | PETG | Heat resistant, strong layer adhesion |
| Side panels | 3mm plywood | Laser cut at school |
| Window panel | 3mm acrylic | Laser cut at school |
| Screws | M3 | For joining printed parts and mounting components |
| Standoffs | Brass M3 | Motherboard mounting |
| AIO | 120mm | LGA1151 compatible |
| Fans | 120mm | 2x intake |

---

### Tools Used

| Tool | Purpose |
|---|---|
| Fusion 360 (Education license) | Primary CAD — 3D modelling and DXF panel exports |
| SolidWorks (maybe) | Secondary CAD if needed |
| Cura / Bambu Studio | Slicing |
| Creality CR-10 V3 | 3D printing (300x300x400mm build volume) |
|Bambulab p2s| 3D printing|
| School laser cutter | Cutting plywood and acrylic panels |

---

### Print Settings

> To be documented as design is finalised

Planned settings:
- **Material** — PETG
- **Layer height** — 0.2mm
- **Infill** — 30-40% for structural parts
- **Supports** — as needed

---

### Design Files

> To be added as design progresses

- STL files for printed skeleton parts

---

### Assembly Guide

> To be documented after first prototype

---

### Iterations / Changelog

| Version | Changes |
|---|---|
| v0.1 | Initial layout sketch — component positioning in Fusion 360 |

---

### Photos

> To be added

---

### Known Issues / Future Improvements

> To be updated as build progresses
