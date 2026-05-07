# 3d-printed-ITX-pc-case
I want to design and print a new ITX case for my pc


---

### Project Status
testing how i can 3d print a mesh

---

### Inspiration 
<img width="451" height="431" alt="image" src="https://github.com/user-attachments/assets/02b77c19-4b5e-4ffe-bb2f-5fbfe3987d19" />

---

### Specifications
#### Main Linux Gaming Build

A zero cost Frankenstein build combining parts from two old PCs into a capable Linux gaming machine running CachyOS.

---

| Component | Spec |
|---|---|
| **CPU** | Intel Core i5-8400 (Coffee Lake, LGA1151, 6 core) |
| **GPU** | NVIDIA GeForce GTX 1070 Ti 8GB |
| **Motherboard** | ASUS PRIME H310M-D (Mini-ITX, LGA1151) |
| **CPU Cooler** | Aftermarket (sourced from donor build) |
| **RAM** | 16GB DDR4 |
| **Primary Storage** | 1TB NVMe M.2 SSD |
| **Secondary Storage** | 2TB HDD |
| **Tertiary Storage** | 500GB HDD |
| **PSU** | Corsair VS650 650W |
| **Case** | NZXT ATX (White) |
| **Fan Hub** | Powered PWM fan hub (dedicated power connector) |
| **Case Fans** | 3x case fans — 2 front intake, 1 rear exhaust |

---

#### Storage Layout

| Drive | Mount | Purpose |
|---|---|---|
| 1TB NVMe M.2 | `/` | OS + active games |
| 2TB HDD | `/mnt/games` | Game library overflow + media |
| 500GB HDD | `/mnt/backup` | Backups + secondary storage |

---

#### Operating System

- **Distro** — CachyOS (Arch-based)
- **Kernel** — CachyOS kernel with BORE scheduler patches
- **GPU Driver** — NVIDIA proprietary
- **Gaming Layer** — Steam + Proton

---

#### Build Notes

- Motherboard is Mini-ITX mounted inside an ATX case using only the 4 relevant standoff positions
- Front panel headers may need extension cables due to ITX board position in ATX case
- Fan hub draws power from SATA connector on PSU — all 3 fans connect to hub, single PWM signal wire runs to motherboard chassis header
- Positive air pressure configuration (2 intake, 1 exhaust) to minimise dust intake
- Total build cost — $0

---

#### Parts Origin

| Component | Source |
|---|---|
| i5-8400, GTX 1070 Ti, H310M-D, DDR4, 250GB NVMe, Corsair VS650 | Scrap PC |
| NZXT Case, CPU Cooler, Club ATX PSU (not used), Z97 board (not used) | White Monster PC |
| 1TB NVMe, 2TB HDD, 500GB HDD | Various |
---

---

### Design Goals
i want the case to be as compact as possible while keeping things like airflow, size, aesthetics etc  in mind

---

### Bill of Materials
- Filament PLA and so far alot
- screws
- standoffs
- fans etc)

---

### Tools Used
- CAD software Fusion 360 (maybe also some solidworks)
- Slicer Cura or bamboolab 
- Printer model (creality cr 10 v2)

---

### Design Files
Links to STL/STEP files, CAD source files

---

### Print Settings
Layer height, infill, supports, material etc

---

### Assembly Guide
Step by step how to put it together

---

### Iterations / Changelog
Document each version and what you changed and why

---

### Photos
Progress shots, finished build

---

### Known Issues / Future Improvements


