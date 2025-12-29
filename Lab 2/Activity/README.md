# Activity – Electrostatic Force Analysis and Visualization

## Overview
This activity studies the electrostatic interaction between three point charges placed at the corners of a right-angle triangle. 
Coulomb’s Law is used to compute the force vector acting on each charge, and MATLAB is employed to visualize the results.

---

## Given
- Charge **q₁ = −3 nC** located at point **A (0, 0, 0)**  
- Charge **q₂ = +7 nC** located at point **B (0.7, 0, 0.25)**  
- Charge **q₃ = +10 nC** located at point **C (0, 0.24, 0.1)**  

The three charges represent the corners of a **right-angle triangle**.

---

## Objectives
- Calculate the electrostatic force vector acting on each charge.
- Visualize the force vectors acting on each charge in **2D**.
- Visualize the force vectors acting on each charge in **3D**.
- Validate the MATLAB results using mathematical calculations.
- Comment on MATLAB performance and calculated results.

---

## Implementation
- Coulomb’s Law is applied in vector form to calculate the force between each pair of charges.
- The net force on each charge is obtained using vector superposition.
- In **2D analysis**, force vectors are projected onto the XY-plane.
- In **3D analysis**, force vectors are represented using full Cartesian components.
- MATLAB plotting tools are used for visualization, with scaling applied only for clarity.

---

## Output
- A 2D plot showing:
  - Charge locations
  - Net electrostatic force vectors acting on each charge
- A 3D plot showing:
  - Spatial distribution of charges
  - Electrostatic force vectors in three-dimensional space

---

## Notes
- Vector addition is required to determine the net force on each charge.
- Geometry strongly affects both force magnitude and direction.
- 3D visualization helps in understanding spatial electrostatic interactions.
- MATLAB provides an efficient platform for modeling and visualizing physical systems.
