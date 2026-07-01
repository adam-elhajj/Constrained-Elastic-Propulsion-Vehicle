# Constrained Elastic Propulsion Vehicle (CEP)

A high-efficiency, potential-energy-storage vehicle designed under strict physical boundary constraints and modeled using AutoCAD. Inspired by the aerodynamic profile of the Audi R8, this project focuses on maximizing mechanical energy transfer, optimizing traction dynamics, and minimizing structural mass to significantly outperform baseline performance design criteria.

## 🚀 Engineering Metrics & Performance
*   **Dimensional Constraints:** Bound tightly within a strict $5" \times 5" \times 5"$ spatial envelope.
*   **Target Distance:** 6.0 ft (Baseline Requirement)
*   **Achieved Distance:** **9.0+ ft** (A 50% performance increase achieved through mass optimization and slip reduction).

---

## 🛠️ Design Requirements & Constraints

The system architecture was developed to meet rigorous structural and performance boundaries outlined in the project specifications:
*   **Spatial Budgeting:** Designing an aerodynamic shell and an internal energy release mechanism that fits completely within the small form-factor envelope without component interference.
*   **Energy Storage Optimization:** Maximizing potential energy conversion from a purely elastic-band source without inducing mechanical deformation in the rear axle or frame under peak tension.
*   **Material Minimization:** Strategic removal of non-critical structural mass to maximize the vehicle's power-to-weight ratio while maintaining structural rigidity.

---

## 📐 Technical Specifications & CAD Analysis

The vehicle was fully modeled as a complete top-level assembly (`CEP_V1_MASTER_ASSEMBLY.dwg`) to ensure precise tolerance margins and a stable center of mass before manufacturing.

### 🏎️ Traction & Wheel Dynamics
*   **High-Grip Geometry:** Custom wheels engineered with directional tread patterns to prevent wheel-spin and eliminate initial kinetic energy loss on low-friction surfaces.
*   **Hub Rigidity:** Designed with a reinforced core hub structure capable of transferring abrupt high-torque loads from the elastic contraction to the driving axle.

### ✈️ Chassis & Aerodynamics
*   **Mid-Engine Silhouette:** Modeled with a low-profile, sloping shell to minimize the frontal cross-sectional area, reducing aerodynamic drag.
*   **Integrated Styling:** Incorporates clean aesthetic detailing, including a custom integrated rear fascia featuring a stylized license plate design.

---

## 🖼️ Visual Layout & CAD Renderings

<p align="center">
  <img src="Media/Top-side view.jpg" alt="Top-side Isometric View" width="31%" />
  <img src="Media/Custom Wheel Design for Audi R8-Inspired Vehicle.jpg" alt="Custom Wheel and Tread Geometry" width="31%" />
  <img src="Media/Back View.jpg" alt="Rear Assembly and Custom Fascia" width="31%" />
</p>
<p align="center">
  <em>Figure 1: Isometric layout, custom tread/hub architecture, and rear chassis profiling featuring integrated design elements.</em>
</p>

---

## 🗂️ Repository Architecture

```text
├── cad-models/
│   └── CEP_V1_MASTER_ASSEMBLY.dwg      # Top-level AutoCAD master assembly
├── design-specifications/
│   └── Project Rubric and Expectations .jpg # Target engineering criteria
├── Media/
│   ├── Top-side view.jpg                # Full vehicle geometry
│   ├── Custom Wheel Design... .jpg      # High-traction tread blueprint
│   └── Back View.jpg                    # Rear fascia detailing
└── README.md                            # Technical documentation
