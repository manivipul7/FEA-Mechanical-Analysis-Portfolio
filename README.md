# Finite Element Analysis Portfolio

This repository is a curated collection of finite element analysis (FEA) projects implemented in ANSYS Workbench, inspired by the structure of “Finite Element Simulations with ANSYS Workbench 2021” by Huei‑Huang Lee, and extended with additional engineering insight, hand calculations, and verification studies. All descriptions, commentary, and post-processing are written in my own words and are intended purely as a demonstration of my FEA skills and understanding.

I respect intellectual property and copyright. No copyrighted text, figures, or files from the book are included here; only my own models, notes, and results built while studying FEA.

---

## 1. Overview

This repository showcases practical FEA experience across:

- Linear static analysis of beams, plates, 3D solid parts, and assemblies  
- Meshing and convergence studies, including treatment of stress singularities  
- Buckling and stress stiffening of beams and truss structures  
- Modal and vibration analysis of mechanical and structural systems  
- Transient and harmonic response analyses  
- Nonlinear analysis (geometric, contact, and material)  
- Explicit dynamics for high-speed impact and drop tests  

Each project folder contains:

- Problem description (in my own words)  
- Modeling approach (geometry, materials, contacts, boundary conditions)  
- Meshing strategy and convergence checks where relevant  
- Post-processing of results and key engineering conclusions  

---

## 2. Repository Structure

- `01_Static_Structural_Projects/`
  - `Pneumatic_Fingers/`
  - `Spur_Gear/`
  - `Pressure_Cylinder/`
  - `Lifting_Fork/`
- `02_Modal_and_Vibrational_Analysis/`
  - `Gearbox/`
  - `Two-Story_Building/`
- `03_Transient_Dynamics_and_Harmonic_Response/`
  - `Two_Story_Building_Cont/`
  - `Disk_and_Block/`
- `04_Nonlinear_Analysis/`
  - `Geometric_or_contact_nonlinearity/`
    - `Translational_Joint/`
    - `Microgripper/`
    - `Snap_Fit/`
  - `Material_nonlinearity/`
    - `Planar_Seal/`
- `05_Explicit_Dynamics/`
  - `High-Speed_Impact/`
  - `Drop_Test/`


Each leaf folder contains:

- `images/` with key plots and contour screenshots (`.png`)  
- `videos/` with short result animations (`.mp4`)  
- `simulation-files/` with ANSYS Workbench project files

---

## 3. Project Library

| Category                     | Project                            | Main Focus                                  |
|-----------------------------|-------------------------------------|---------------------------------------------|
| Static Structural           | Pneumatic Fingers                   | Pressure loading, large deflection trends   |
|                             | Spur Gear                           | Tooth contact stresses, mesh refinement     |
|                             | Pressure Cylinder                   | Membrane vs bending stresses, hoop stress   |
|                             | Lifting Fork                        | Load path, stress hotspots at fillets       |
| Modal & Vibrational         | Gearbox                             | Natural frequencies and mode shapes         |
|                             | Two-Story Building                  | Global modes, floor response                |
| Transient & Harmonic        | Two-Story Building (Continued)     | Time-history excitation, damping            |
|                             | Disk and Block                      | Harmonic response and resonance behavior    |
| Nonlinear (Geom/Contact)    | Translational Joint                 | Contact nonlinearity, stiffness changes     |
|                             | Microgripper                        | Large deflection, contact, micro-scale FEA  |
|                             | Snap Fit                            | Snap-through, contact status evolution      |
| Nonlinear (Material)        | Planar Seal                         | Hyperelastic / nonlinear material response  |
| Explicit Dynamics           | High-Speed Impact                   | Short-duration impact, stress waves         |
|                             | Drop Test                           | Energy absorption and plastic deformation   |

---

## 4. How to Navigate

- Start with **01_Static_Structural_Projects** to see basic stress analysis and meshing strategy.  
- Move to **02_Modal_and_Vibrational_Analysis** for eigenfrequencies and mode shapes.  
- Explore **03_Transient_Dynamics_and_Harmonic_Response** for dynamic loading and resonance.  
- Review **04_Nonlinear_Analysis** to see geometric, contact, and material nonlinear behavior.  
- Finish with **05_Explicit_Dynamics** for high-strain-rate problems and impact simulations.  

Each project `README.md` provides:

1. Problem statement and engineering context  
2. Modeling and boundary-condition setup  
3. Mesh details and any convergence checks performed  
4. Key plots, animations, and numerical results  
5. Short discussion of engineering implications and possible design changes  

---

## 5. Tools and Environment

- **FEA Solver:** ANSYS Workbench (Structural)  
- **Post-processing:** ANSYS, plus exported plots and animations  
- **Documentation:** Markdown (`README.md` per project)

If you have questions about any specific project (assumptions, boundary conditions, or how a result was obtained), feel free to open an issue or contact me.


