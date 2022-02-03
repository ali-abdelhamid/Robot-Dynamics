# Robot-Dynamics

Script Breakdown:
1. Forward Kinematics (Product of Exponentials)
2. Use POE Array to find each specific transformation matrix from base frame to tool frame and centers of mass (COM)
3. Euler-Lagrange Method
    * Use chain rule to compute velocities of COMs
    * Use velocities to compute kinetic energies and masses to compute potential energies
    * Find the Lagrangian term
    * Simplify into Dynamical model with Torque = Inertia Matrix(q_dd) + Corriolis Matrix(q_d) + the Gravity Term
4. Newtonian Method
