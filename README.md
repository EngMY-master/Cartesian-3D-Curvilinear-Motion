# Cartesian-3D-Curvilinear-Motion

## Theory Behind the Code

This program deals with the motion of objects in three-dimensional space and involves concepts of vectors, differentiation, and integration. Below is a breakdown of the underlying theory:

### 1. **Vectors in 3D Space**
   - A vector is represented by its components along the `i`, `j`, and `k` directions.
   - For example, a position vector is represented as:
     ```
     r(t) = x(t) i + y(t) j + z(t) k
     ```

### 2. **Magnitude of a Vector**
   - The magnitude (or length) of a vector is computed using the Pythagorean theorem:
     ```
     |v| = sqrt(v_x^2 + v_y^2 + v_z^2)
     ```

### 3. **Directional Cosines**
   - Directional cosines of a vector are the cosines of the angles it makes with the coordinate axes.
   - They are calculated as:
     ```
     cos(alpha) = v_x / |v|
     cos(beta) = v_y / |v|
     cos(gamma) = v_z / |v|
     ```

### 4. **Differentiation of Vectors**
   - The derivative of a position vector gives the velocity vector:
     ```
     v(t) = dr(t) / dt
     ```
   - The derivative of a velocity vector gives the acceleration vector:
     ```
     a(t) = dv(t) / dt
     ```

### 5. **Integration of Vectors**
   - The integral of an acceleration vector gives the velocity vector (adding initial conditions):
     ```
     v(t) = integral(a(t) dt) + v_0
     ```
   - The integral of a velocity vector gives the position vector (adding initial conditions):
     ```
     r(t) = integral(v(t) dt) + r_0
     ```

### 6. **Evaluating Vectors**
   - Vectors can be evaluated at a specific time to determine the position, velocity, or acceleration at that instant.
   - Displacement, velocity changes, and acceleration changes over a time interval are calculated as differences of vector evaluations.

---
