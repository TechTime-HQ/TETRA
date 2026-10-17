# TETRA Standard

🌐 **Languages:** [English](README.md) | [Русский](README.ru.md)

**TETRA** is a universal, open-source space scaling and layout standard developed by the **TechTime** brand. The purpose of the standard is to establish a unified, end-to-end system of geometric and physical constants applicable across all scales: from nanometer-sized silicon chips to server rack dimensions and macro-constructors.

## 📐 Base Philosophy and Universal Formula

The TETRA standard is based on the end-to-end scaling of space across two domains: a two-dimensional grid (area) and a vertical axis (height).

### 1. Planar Scaling (Area and Grid)
*   **Micro and Macro Worlds (The A-Series):** The international **A4** paper format is adopted as the base unit of area. Scaling up (macro world) and down (microelectronics) follows the strict geometric principle of the **ISO 216 A-series** (with an aspect ratio of \(1 : \sqrt{2}\)).
*   **Architectural and Furniture Space:** For interior design, furniture layout, and spatial planning, a fixed grid step of **60 × 60 cm** is applied, which seamlessly integrates into the global coordinate system.
*   **Global Logistics:** On the corresponding macro-scale, the A-system defines the dimensions of a standard **cargo container** (a stretched geometry equivalent to an A-format sheet divided exactly in half along its long side).

### 2. Vertical Scaling (Height)
To measure the height of any physical object, a dedicated unit of measurement is introduced — the **TETRA Unit (TU)**.
*   **1 TU** = exactly `20 mm`.
*   **Minimum Step:** For high-precision systems (microcontrollers, PCB layout, small components), a subdivision step of **0.5 TU** (`10 mm`) is allowed.

### 3. TETRA Cargo Logistics and Architectural Standard
As a unified macro-world constant, the **TETRA Cargo** standard is established — an open specification for freight and structural building blocks. The project is completely cleaned of legacy non-metric units (feet, inches) and is fully optimized for international road regulations (100% legal for standard European and Russian road platforms).

The master reference is the **High-Space Core** module, whose parameters perfectly bridge transportation logistics, IT infrastructure, and human-centric architecture.

#### TETRA Cargo Blueprint:
*   **External Length:** exactly `12 500 mm` (12.5 meters) — 625 TU.
*   **External Width:** exactly `2 500 mm` (2.5 meters) — 125 TU.
*   **External Height:** exactly `3 000 mm` (3.0 meters) — 150 TU.

#### System Advantages of the TETRA Cargo Constant:
1.  **Flawless Area Modularity (5 : 1):** The length-to-width ratio is exactly `5 : 1`. Five modules placed side-by-side along their longitudinal sides form a perfect macro-grid square (\(12.5 \times 12.5\text{ m}\)). A single module can turn 90 degrees and interlock seamlessly against five longitudinal units, eliminating dead zones during block construction and stacking.
2.  **Internal Spatial Layout (60 × 60 cm Grid):** With 50 mm thick exterior walls, the net internal width is exactly `2 400 mm` (perfectly fitting 4 spatial modules of 60 cm). The net internal length is exactly `12 400 mm`, allowing a dense allocation of exactly **20 living/working modules of 60 cm** and leaving an extra `400 mm` (40 cm) zone.
3.  **Dedicated Engineering & Tech Zone:** The remaining 40 cm of internal length serves as a built-in technical compartment. This isolated area is designed for power distribution, climate-control hardware, inverters, server inputs, or air ventilation, preserving the main living/working layout.
4.  **Electronics Integration:** The external width of 2,500 mm equals exactly `1,000 pins` of the **TETRA 2.5 mm PCB grid**, locking the macro-building and the micro-chip into a single mathematical ecosystem.


---

## 🛠️ Implementation Specs (Sub-Projects)

The TETRA standard is implemented as an end-to-end constant across key industries:

*   **Silicon & ICs (Microelectronics):** Standardization of die dimensions and chip footprints.
*   **PCB Layout (Electronics Grid):** Unified grid pitch, fixed clearances, and mounting zones for printed circuit boards.
*   **Displays:** Standards for aspect ratios, pixel density, and physical screen boundaries.
*   **Server Equipment (Server Infrastructure):** Optimization of unit-based server rack dimensions and internal space according to the TETRA standard.
*   **Macro-Constructors:** Integration of the grid pitch with modular building blocks (similar to LEGO-type modules) for seamless interlocking of physical enclosures and electronics.

---

## ⚡ First Physical Implementation: Tetrino NANO

The **Tetrino NANO** project is a reference microcontroller module (within the ecosystem of Arduino-compatible boards), fully designed according to the canons of the **TETRA** standard.

*   **Physical Board Width:** exactly `18 mm`.
*   **Pin Pitch:** exactly `2.5 mm` (instead of the traditional 2.54 mm / 0.1 inch pitch).
*   **Compatibility:** The standardized TETRA PCB layout allows Tetrino NANO to be seamlessly integrated into any next-generation physical modules and breadboards.

---

## 👥 Authorship and Contribution

*   **Project Founder & Concept Author:** Romanov Serge (`rummind`)
*   **Brand:** TechTime

This project is developed as **Open-Source**. Any proposals for integrating the standard into new spheres of life are welcome in the **Issues** and **Pull Requests** sections.
