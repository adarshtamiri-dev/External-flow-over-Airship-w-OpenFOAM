# External Flow over Complex Bodies with k-Epsilon Model – OpenFOAM Case File
## Force Coefficients
## Drag Coefficients

This repository contains a tuned and ready-to-use OpenFOAM case setup for external aerodynamic flow simulations using the k-Epsilon turbulence model. Though originally tested on a specific geometry, the setup is highly adaptable and can be easily extended to similar external flow problems.
🔧 Features

  k-Epsilon RANS Model: Balanced for accuracy and stability in external aerodynamic scenarios.

  Optimized Mesh Generation: Utilizes cfMesh for automated, high-quality meshing suitable for complex external domains.

  Efficient Case Tuning: Boundary conditions, solver settings, and relaxation factors are pre-optimized to reduce iteration time and promote convergence.

✅ Applications

This setup is ideal for:

   External flow over streamlined bodies

   Initial testing of aerodynamic shapes

   Parametric studies with different configurations

🚀 For Usage

   Clone the repo

   Adjust geometry (constant/triSurface or STL file)

   Edit meshDict and mesh the domain using cfMesh

   Run the simulation using simpleFoam

📁 Structure

   system/ – Simulation controls and solver settings

   constant/ – Mesh, turbulence model, and physical properties

   0/ – Initial and boundary conditions

📝 Notes

   Designed with adaptability in mind

   Can be extended to more advanced turbulence models or refined further

   Suitable for educational or research-level aerodynamic testing.
