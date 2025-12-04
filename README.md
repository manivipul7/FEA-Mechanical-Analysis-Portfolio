# Finite Element Analysis Portfolio

This repository is a curated collection of finite element analysis (FEA) projects implemented in ANSYS Workbench, inspired by the structure of “Finite Element Simulations with ANSYS Workbench 2021” by Huei‑Huang Lee, and extended with additional engineering insight, hand calculations, and verification studies. All descriptions, commentary, and post-processing are written in my own words and are intended purely as a demonstration of my FEA skills and understanding.

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

### 01 Static Structural Projects

### 1A Pneumatic Fingers

<p align="center">
  <img src="01_Static_Structural_Projects/01_Pneumatic_Fingers/Directional_Deformation.png"
       alt="Directional deformation of pneumatic fingers under pressure"
       width="90%">
</p>

<p align="center">
  <em>Directional deformation of pneumatically actuated fingers in a static structural analysis.</em>
</p>

---

### 1B Spur Gear

<p align="center">
  <img src="01_Static_Structural_Projects/02_Spur Gear/Equivalent_Stress_(von-Mises).png"
       alt="Equivalent von Mises stress in a spur gear"
       width="90%">
</p>

<p align="center">
  <em>Equivalent (von-Mises) stress distribution in a loaded spur gear tooth.</em>
</p>

---

### 1C Pressure Cylinder Cover

<p align="center">
  <img src="01_Static_Structural_Projects/03_Pressure_Cylinder/Total_Deformation.png"
       alt="Total deformation of pressure cylinder"
       width="70%">

<p align="center">
  <img src="01_Static_Structural_Projects/03_Pressure_Cylinder/Equivalent_Stress_(von-Mises).png"
       alt="von Mises stress in pressure cylinder"
       width="70%">

<p align="center">
  <img src="01_Static_Structural_Projects/03_Pressure_Cylinder/Circularity_check.png"
       alt="Circularity check at critical section of pressure cylinder"
       width="70%">
</p>

<p align="center">
  <em>Pressure vessel study: stress, deformation, and circularity check at the critical cross‑section.</em>
</p>

---

### 1D Lifting Fork

<p align="center">
   <img src="01_Static_Structural_Projects/04_Lifting_Fork/Directional_Deformation_Earth_Gravity.png"
       alt="Directional deformation of lifting fork under gravity"
       width="32%">
  <img src="01_Static_Structural_Projects/04_Lifting_Fork/Directional_Deformation_Transient_.png"
       alt="Transient directional deformation of lifting fork"
       width="32%">
  <img src="01_Static_Structural_Projects/04_Lifting_Fork/Maximum_Principal_Stress.png"
       alt="Maximum principal stress in lifting fork"
       width="32%"> 
</p>

<p align="center">
  <em>Lifting fork under static and transient loading: principal stresses and directional deformations.</em>
</p>

---

### 02 Modal and Vibrational Analysis

### 2A Gearbox – Mode Shapes

<p align="center">
  <img src="02_Modal_and_Vibrational_Analysis/01_Gearbox/Mode_1.gif"
       alt="Gearbox mode shape 1"
       width="45%">
  <img src="02_Modal_and_Vibrational_Analysis/01_Gearbox/Mode_2.gif"
       alt="Gearbox mode shape 2"
       width="45%">
</p>

<p align="center">
  <img src="02_Modal_and_Vibrational_Analysis/01_Gearbox/Mode_3.gif"
       alt="Gearbox mode shape 3"
       width="45%">
  <img src="02_Modal_and_Vibrational_Analysis/01_Gearbox/Mode_4.gif"
       alt="Gearbox mode shape 4"
       width="45%">
</p>

<p align="center">
  <img src="02_Modal_and_Vibrational_Analysis/01_Gearbox/Mode_5.gif"
       alt="Gearbox mode shape 5"
       width="45%">
  <img src="02_Modal_and_Vibrational_Analysis/01_Gearbox/Mode_6.gif"
       alt="Gearbox mode shape 6"
       width="45%">
</p>

<p align="center">
  <em>First six mode shapes of the gearbox housing, highlighting global bending and local dynamics.</em>
</p>

---

### 2B Two-Story Building – Mode Shapes

<p align="center">
  <img src="02_Modal_and_Vibrational_Analysis/02_Two-Story_Building/Mode_1.gif"
       alt="Two-story building mode shape 1"
       width="45%">
  <img src="02_Modal_and_Vibrational_Analysis/02_Two-Story_Building/Mode_2.gif"
       alt="Two-story building mode shape 2"
       width="45%">
</p>

<p align="center">
  <img src="02_Modal_and_Vibrational_Analysis/02_Two-Story_Building/Mode_3.gif"
       alt="Two-story building mode shape 3"
       width="45%">
  <img src="02_Modal_and_Vibrational_Analysis/02_Two-Story_Building/Mode_4.gif"
       alt="Two-story building mode shape 4"
       width="45%">
</p>

<p align="center">
  <img src="02_Modal_and_Vibrational_Analysis/02_Two-Story_Building/Mode_5.gif"
       alt="Two-story building mode shape 5"
       width="45%">
  <img src="02_Modal_and_Vibrational_Analysis/02_Two-Story_Building/Mode_6.gif"
       alt="Two-story building mode shape 6"
       width="45%">
</p>

<p align="center">
  <em>First six mode shapes of a two-story building model, illustrating floor sway, torsion, and higher-order modes.</em>
</p>


---


### 03 Transient Dynamics and Harmonic Response


<p align="center">
  <img src="03_Transient Dynamics and Harmonic Response/02_Disk_and_Block/Total_Deformation.gif"
       alt="Total deformation of disk and block assembly in transient dynamics"
       width="80%">
</p>

<p align="center">
  <em>Time-dependent total deformation of the disk–block system under dynamic loading.</em>
</p>


---


### 04 Nonlinear Analysis – Geometric / Contact Nonlinearity


### 4A Translational Joint


<p align="center">
  <img src="04_Nonlinear_Analysis/Geometric_or_contact_nonlinearity/01_Translational_Joint/Geometry.png"
       alt="Geometry of translational joint model"
       width="35%">
  <img src="04_Nonlinear_Analysis/Geometric_or_contact_nonlinearity/01_Translational_Joint/Total_Deformation.gif"
       alt="Total deformation of translational joint with contact nonlinearity"
       width="45%">
</p>

<p align="center">
  <em>Translational joint model: contact-driven nonlinear stiffness and resulting deformation under load.</em>
</p>

---

### 4B Microgripper


<p align="center">
  <img src="04_Nonlinear_Analysis/Geometric_or_contact_nonlinearity/02_Microgripper/Problem Statement.png"
       alt="Problem statement and setup for microgripper"
       width="45%">
  <img src="04_Nonlinear_Analysis/Geometric_or_contact_nonlinearity/02_Microgripper/Total_Deformation.gif"
       alt="Total deformation of microgripper under actuation"
       width="45%">
</p>

<p align="center">
  <em>Microgripper case: geometric and contact nonlinearity driving large, localized deformations at the gripper tips.</em>
</p>

---

### 4C Snap Fit


<p align="center">
  <img src="04_Nonlinear_Analysis/Geometric_or_contact_nonlinearity/03_Snap_Fit/Mesh.png"
       alt="Finite element mesh for snap-fit assembly"
       width="42%">
  <img src="04_Nonlinear_Analysis/Geometric_or_contact_nonlinearity/03_Snap_Fit/Total_Deformation_gif.gif"
       alt="Total deformation during snap-fit engagement"
       width="42%">
</p>

<p align="center">
  <em>Snap-fit assembly: from CAD geometry and meshing to highly nonlinear engagement and release deformation.</em>
</p>

---

### 04 Nonlinear Analysis – Material Nonlinearity


### 4D Planar Seal


<p align="center">
  <img src="04_Nonlinear_Analysis/Material_nonlinearity/Planar Seal/Displacement.png"
       alt="Planar seal displacement field"
       width="45%">
  <img src="04_Nonlinear_Analysis/Material_nonlinearity/Planar Seal/Max_Principal_Stress_gif.gif"
       alt="Maximum principal stress in planar seal"
       width="45%">
  
</p>

<p align="center">
  <em>Planar seal model and deformed configuration under compression.</em>
</p>


<p align="center">

  <img src="04_Nonlinear_Analysis/Material_nonlinearity/Planar Seal/Shear_Elastic_Strain_gif.gif"
       alt="Shear elastic strain distribution in planar seal"
       width="45%">

  <img src="04_Nonlinear_Analysis/Material_nonlinearity/Planar Seal/Min_Principal_Stress_gif.gif"
       alt="Minimum principal stress in planar seal"
       width="45%">
</p>

<p align="center">
  <em>Evolution of maximum and minimum principal stresses in the hyperelastic seal.</em>
</p>

<p align="center">
  <img src="04_Nonlinear_Analysis/Material_nonlinearity/Planar Seal/Max_Principal_Elastic_Strain_gif.gif"
       alt="Maximum principal elastic strain in planar seal"
       width="45%">
  <img src="04_Nonlinear_Analysis/Material_nonlinearity/Planar Seal/Min_Principal_Elastic_Strain_gif.gif"
       alt="Minimum principal elastic strain in planar seal"
       width="45%">
</p>

<p align="center">
  <em>Maximum and minimum principal elastic strain fields highlighting highly strained regions in the seal.</em>
</p>

<p align="center">
  <img src="04_Nonlinear_Analysis/Material_nonlinearity/Planar Seal/Shear_Stress_gif.gif"
       alt="Shear stress distribution in planar seal"
       width="45%">

</p>

<p align="center">
  <em>Shear stress and shear elastic strain response of the seal under nonlinear material behavior.</em>
</p>


---


### 05 Explicit Dynamics

### 5A High-Speed Impact

<p align="center">
  <img src="05_Explicit_Dynamics/01_High-Speed_Impact/Initial_Velocity.png"
       alt="Initial velocity conditions for high-speed impact"
       width="45%">
  <img src="05_Explicit_Dynamics/01_High-Speed_Impact/Mesh.png"
       alt="Finite element mesh used for high-speed impact simulation"
       width="45%">
</p>

<p align="center">
  <em>High-speed impact setup: initial velocity definition and refined mesh in the impact region.</em>
</p>

<p align="center">
  <img src="05_Explicit_Dynamics/01_High-Speed_Impact/Total_Deformation_gif.gif"
       alt="Total deformation during high-speed impact"
       width="45%">
  <img src="05_Explicit_Dynamics/01_High-Speed_Impact/Equivalent_Stress_gif.gif"
       alt="Equivalent stress during high-speed impact"
       width="45%">
</p>

<p align="center">
  <em>Transient deformation and von Mises stress evolution under high strain-rate impact loading.</em>
</p>


---


### 5B Drop Test


<p align="center">
  <img src="05_Explicit_Dynamics/02_Drop_Test/Geomtery.png"
       alt="Drop test geometry"
       width="45%">
  <img src="05_Explicit_Dynamics/02_Drop_Test/Mesh.png"
       alt="Finite element mesh for drop test"
       width="45%">
</p>

<p align="center">
  <em>Drop test specimen geometry and meshing strategy.</em>
</p>

<p align="center">
  <img src="05_Explicit_Dynamics/02_Drop_Test/Boun_Cond_1.png"
       alt="First boundary condition view for drop test"
       width="45%">
  <img src="05_Explicit_Dynamics/02_Drop_Test/Boun_Cond_2.png"
       alt="Second boundary condition view for drop test"
       width="45%">
</p>

<p align="center">
  <em>Boundary condition definitions capturing impact surface and constraints.</em>
</p>

<p align="center">
  <img src="05_Explicit_Dynamics/02_Drop_Test/Total_Deformation_gif.gif"
       alt="Total deformation during drop test"
       width="45%">
  <img src="05_Explicit_Dynamics/02_Drop_Test/Equivalent_Stress_2_gif.gif"
       alt="Equivalent stress during drop test impact"
       width="45%">
</p>

<p align="center">
  <em>Explicit dynamic response of the component under drop impact: deformation and stress propagation.</em>
</p>



---
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


