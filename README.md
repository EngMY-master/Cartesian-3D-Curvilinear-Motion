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
# Detailed Comments and Theory on the Code

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

## Example Input and Output

### Example Input:
```plaintext
Please choose the type of vector you are entering:
1. Position Vector
2. Velocity Vector
3. Acceleration Vector
Enter 1, 2, or 3: 2
Enter the components of the velocity vector:
Enter the i-component (can be a function of t): 16*t**2
Enter the j-component (can be a function of t): 4*t**3
Enter the k-component (can be a function of t): 5*t+2
You entered a velocity vector. We will compute the position and acceleration vectors from velocity.
Enter the initial x-position: 0
Enter the initial y-position: 0
Enter the initial z-position: 0
Enter the initial x-velocity: 0
Enter the initial y-velocity: 0
Enter the initial z-velocity: 0
Do you need to evaluate the vectors at an exact time or calculate displacement? (Enter 'time' for exact time or 'displacement' for displacement): time
Enter the time value to evaluate the vectors: 2
```

### Example Output:
```plaintext
Position Vector at t = 2.0: Matrix([[42.6666666666667], [16.0000000000000], [14.0000000000000]])
Magnitude of Position Vector at t = 2.0: 47.6701630419327
Velocity Vector at t = 2.0: Matrix([[64.0000000000000], [32.0000000000000], [12.0000000000000]])
Magnitude of Velocity Vector at t = 2.0: 72.5534285888682
Acceleration Vector at t = 2.0: Matrix([[64.0000000000000], [48.0000000000000], [5]])
Magnitude of Acceleration Vector at t = 2.0: 80.1560977094070
```

---
