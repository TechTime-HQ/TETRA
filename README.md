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

As a unified macro-world constant, the **TETRA Cargo** standard is established — an open specification for freight and structural building blocks. The project is completely cleaned of legacy non-metric units (feet, inches) and is subordinated to the rules of harmonic spatial composition.

The master reference is the **High-Space Core** module, whose parameters perfectly bridge transportation logistics, IT infrastructure, and human-centric architecture.

#### TETRA Cargo Blueprint:
*   **Length:** exactly `13 456 mm` — defined by the **128A0** macro-format of your universal grid.
*   **Width:** exactly `4 756 mm` — calculated as the shorter side of the 128A0 format divided exactly in half along the long axis (`9512 / 2`).
*   **Height:** exactly `3 000 mm` — equals exactly **150 TU** (TETRA Unit).

#### System Advantages of the TETRA Cargo Constant:
1.  **Area Modularity (\(2\sqrt{2}\)):** The length-to-width ratio is approximately `2.83 : 1`. Two modules placed side-by-side along their longitudinal sides form a flawless square in the macro-grid. This eliminates any dead zones or gaps during block construction and stacking.
2.  **Architectural Harmony (60 × 60 cm Step):** The `3 000 mm` height equals exactly 5 spatial steps of the TETRA interior grid (`5 × 600 mm`). Thanks to this, the modules serve as perfect ready-made cells for living spaces and labs — any furniture, partitions, and wall panels matching the 60 cm grid fit from floor to ceiling without adjustment.
3.  **IT Infrastructure and Server Racks:** The **150 TU** height provides the optimal cubic capacity for seamless integration of TETRA-standard server racks, leaving perfect overhead space for backbone cable routing, ventilation, and raised floor systems.

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
