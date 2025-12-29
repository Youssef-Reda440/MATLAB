# Report – Electrostatic Force Analysis and Coordinate Transformations

## Overview
This report presents a detailed analysis of electrostatic forces between three point charges using Coulomb’s Law. 
The forces acting on each charge are computed, visualized in two and three dimensions, and transformed between different coordinate systems using MATLAB.

The report emphasizes numerical accuracy, correct vector manipulation, and validation of MATLAB results through analytical calculations.

---

## Given
- Charge **q₁ = −10 nC** located at point **A (0, 0, 0)**  
- Charge **q₂ = −5 nC** located at point **B (0.5, 0, 0.4)**  
- Charge **q₃ = +8 nC** located at point **C (0, 0.8, 0.1)**  

The three charges form the corners of a **right-angle triangle**.

---

## Tasks Description

### Task 1 – 2D Electrostatic Force Visualization
**Aim:**  
To compute and visualize the force vector acting on each charge in the XY-plane.

**Method:**
- Coulomb’s Law is applied in vector form.
- The net force on each charge is calculated using vector superposition.
- Forces are visualized in 2D using MATLAB vector plots.

---

### Task 2 – 3D Electrostatic Force Visualization
**Aim:**  
To compute and visualize the force vector acting on each charge in three-dimensional space.

**Method:**
- Charge positions are defined in 3D Cartesian coordinates.
- Force vectors are computed using full 3D vector operations.
- Results are visualized using 3D vector plots.

---

### Task 3 – Cartesian to Cylindrical Coordinate Transformation
**Aim:**  
To convert the force vectors obtained in Task 1 into cylindrical coordinates.

**Method:**
- Force vectors are expressed as Cartesian vectors.
- A cylindrical coordinate transformation matrix is applied at the specified point.
- The transformation is performed on vectors, not points.

---

### Task 4 – Cartesian to Spherical Coordinate Transformation
**Aim:**  
To convert the force vectors obtained in Task 2 into spherical coordinates.

**Method:**
- Spherical angles are determined from the given reference point.
- A spherical coordinate transformation matrix is used to transform the force vectors.
- MATLAB built-in point conversion functions are avoided for vector transformation.

---

### Task 5 – Validation of Results
**Aim:**  
To verify the MATLAB results using mathematical calculations.

**Method:**
- Analytical calculations based on Coulomb’s Law and vector algebra are performed.
- Numerical results obtained from MATLAB are compared with theoretical values.

---

### Task 6 – Discussion and Comments
**Aim:**  
To analyze MATLAB performance and comment on the obtained results.

**Discussion:**
- MATLAB provides accurate numerical results consistent with analytical calculations.
- Vector scaling is applied only for visualization purposes.
- The direction and magnitude of force vectors correctly represent electrostatic interactions.

---

## Conclusion
This report demonstrates the correct application of electrostatic theory, vector superposition, and coordinate system transformations.
It highlights the importance of distinguishing between point conversion and vector transformation and confirms the reliability of MATLAB as a tool for electromagnetic field analysis.
