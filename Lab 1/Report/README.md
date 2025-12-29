# Report – Vector Operations and Coordinate Transformations

## Overview
This report presents the implementation and validation of vector operations using MATLAB, based on the given vector fields and specified evaluation points.

## Given
- Vector **A**:  
  A = −3y² uₓ − 2x uᵧ + z u_z  
  evaluated at point **P (0, 1, 0)**

- Vector **B**:  
  B = 7 u_r − 5 u_θ + 8 u_φ  
  evaluated at point **Q (0, 1, 1)**

## Objectives
- Compute **A + B** at point **Q**.
- Compute **A − B** at point **P**.
- Convert vectors between Cartesian and Spherical coordinate systems.
- Validate MATLAB results using analytical calculations.

## Implementation
- Vector **A** is evaluated directly in Cartesian coordinates at the specified points.
- Vector **B** is transformed from spherical to Cartesian coordinates using unit vector transformation matrices.
- Vector addition and subtraction are performed after expressing both vectors in the same coordinate system.
- MATLAB is used to verify the correctness of the analytical results.

## Output
- Cartesian representation of **A + B** at point Q.
- Cartesian representation of **A − B** at point P.
- Results consistent with theoretical vector analysis principles.

## Notes
All calculations follow standard definitions and conventions used in vector analysis and electromagnetic field theory.
